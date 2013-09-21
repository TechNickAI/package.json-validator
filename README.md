# About
`package.json` files are central for node.js/npm projects. Beyond just valid json, there are required fields to follow the specifications. Of course, there are multiple ones to follow, which makes it trickier.

* [NPM](https://github.com/isaacs/npm/blob/master/doc/cli/json.md)
* [CommonJS Packages 1.0](http://wiki.commonjs.org/wiki/Packages/1.0)
* [CommonJS Packages 1.1](http://wiki.commonjs.org/wiki/Packages/1.1)

This tool verifies the package.json against the specification of your choice, letting you know if you have a valid file. The validation reports required fields that you MUST have, warns for fields that you SHOULD have, and recommends optional fields that you COULD have.

# Usages

### Command line
`npm install package-json-validator`

Then it's in node_modules/bin/pjv

See `node_modules/bin/pjv --help` for usage:

```
Options:
  --filename, -f         package.json file to validate                      [default: "package.json"]
  --spec, -s             which spec to use - npm|commonjs_1.0|commonjs_1.1  [default: "npm"]
  --warnings, -w         display warnings                                   [default: false]
  --recommendations, -r  display recommendations                            [default: false]
  --quiet, -q            less output                                        [default: false]
  --help, -h, -?         this help message                                  [default: false]
```


### Online
Online copy hosted courtesy of Nick Sullivan at [http://package-json-validator.com/](http://package-json-validator.com/). Want to run your own copy? You are welcome to clone or fork this repo.

# Future
* An API
* Unit tests


# Issues/Requests
Please check out [the existing issues](https://github.com/gorillamania/package.json-validator/issues), 
and if you don't see that your problem is already being worked on, 
please [file an issue](https://github.com/gorillamania/package.json-validator/issues/new).

### Fork and Pull request
Since you are probably a developer, you can probably just make the change yourself and submit a 
[pull request](https://help.github.com/articles/using-pull-requests)

# License
See [LICENSE](https://github.com/gorillamania/package.json-validator/blob/master/LICENSE)
