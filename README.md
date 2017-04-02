# api documentation for  [path-to-regexp (v1.7.0)](https://github.com/pillarjs/path-to-regexp#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-path-to-regexp.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-path-to-regexp) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-path-to-regexp.svg)](https://travis-ci.org/npmdoc/node-npmdoc-path-to-regexp)
#### Express style path to RegExp utility

[![NPM](https://nodei.co/npm/path-to-regexp.png?downloads=true)](https://www.npmjs.com/package/path-to-regexp)

[![apidoc](https://npmdoc.github.io/node-npmdoc-path-to-regexp/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-path-to-regexp_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-path-to-regexp/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-path-to-regexp/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/pillarjs/path-to-regexp/issues"
    },
    "component": {
        "scripts": {
            "path-to-regexp": "index.js"
        }
    },
    "dependencies": {
        "isarray": "0.0.1"
    },
    "description": "Express style path to RegExp utility",
    "devDependencies": {
        "chai": "^2.3.0",
        "istanbul": "~0.3.0",
        "mocha": "~2.2.4",
        "standard": "~3.7.3",
        "ts-node": "^0.5.5",
        "typescript": "^1.8.7",
        "typings": "^1.0.4"
    },
    "directories": {},
    "dist": {
        "shasum": "59fde0f435badacba103a84e9d3bc64e96b9937d",
        "tarball": "https://registry.npmjs.org/path-to-regexp/-/path-to-regexp-1.7.0.tgz"
    },
    "files": [
        "index.js",
        "index.d.ts",
        "LICENSE"
    ],
    "gitHead": "a99ec3c149e8c1d91fa533aa54d3ee7e34449bb3",
    "homepage": "https://github.com/pillarjs/path-to-regexp#readme",
    "keywords": [
        "express",
        "regexp",
        "route",
        "routing"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "amasad",
            "email": "amjad.masad@gmail.com"
        },
        {
            "name": "anthonyshort",
            "email": "antshort@gmail.com"
        },
        {
            "name": "blakeembrey",
            "email": "hello@blakeembrey.com"
        },
        {
            "name": "calvinfo",
            "email": "calvin@calv.info"
        },
        {
            "name": "clintwood",
            "email": "clint@anotherway.co.za"
        },
        {
            "name": "coreh",
            "email": "thecoreh@gmail.com"
        },
        {
            "name": "cristiandouce",
            "email": "cristiandouce@gmail.com"
        },
        {
            "name": "defunctzombie",
            "email": "shtylman@gmail.com"
        },
        {
            "name": "dfcreative",
            "email": "df.creative@gmail.com"
        },
        {
            "name": "dominicbarnes",
            "email": "dominic@dbarnes.info"
        },
        {
            "name": "dougwilson",
            "email": "doug@somethingdoug.com"
        },
        {
            "name": "forbeslindesay",
            "email": "forbes@lindesay.co.uk"
        },
        {
            "name": "ianstormtaylor",
            "email": "ian@ianstormtaylor.com"
        },
        {
            "name": "jonathanong",
            "email": "jonathanrichardong@gmail.com"
        },
        {
            "name": "jongleberry",
            "email": "jonathanrichardong@gmail.com"
        },
        {
            "name": "juliangruber",
            "email": "julian@juliangruber.com"
        },
        {
            "name": "kelonye",
            "email": "kelonyemitchel@gmail.com"
        },
        {
            "name": "mattmueller",
            "email": "mattmuelle@gmail.com"
        },
        {
            "name": "nami-doc",
            "email": "vendethiel@hotmail.fr"
        },
        {
            "name": "queckezz",
            "email": "fabian.eichenberger@gmail.com"
        },
        {
            "name": "rauchg",
            "email": "rauchg@gmail.com"
        },
        {
            "name": "retrofox",
            "email": "rdsuarez@gmail.com"
        },
        {
            "name": "stagas",
            "email": "gstagas@gmail.com"
        },
        {
            "name": "stephenmathieson",
            "email": "me@stephenmathieson.com"
        },
        {
            "name": "swatinem",
            "email": "arpad.borsos@googlemail.com"
        },
        {
            "name": "thehydroimpulse",
            "email": "dnfagnan@gmail.com"
        },
        {
            "name": "timaschew",
            "email": "timaschew@gmail.com"
        },
        {
            "name": "timoxley",
            "email": "secoif@gmail.com"
        },
        {
            "name": "tjholowaychuk",
            "email": "tj@vision-media.ca"
        },
        {
            "name": "tootallnate",
            "email": "nathan@tootallnate.net"
        },
        {
            "name": "trevorgerhardt",
            "email": "trevorgerhardt@gmail.com"
        },
        {
            "name": "yields",
            "email": "yields@icloud.com"
        }
    ],
    "name": "path-to-regexp",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pillarjs/path-to-regexp.git"
    },
    "scripts": {
        "lint": "standard",
        "prepublish": "typings install",
        "test": "npm run lint && npm run test-cov",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --require ts-node/register -R spec test.ts",
        "test-spec": "mocha --require ts-node/register -R spec --bail test.ts"
    },
    "typings": "index.d.ts",
    "version": "1.7.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module path-to-regexp](#apidoc.module.path-to-regexp)
1.  [function <span class="apidocSignatureSpan">path-to-regexp.</span>compile (str, options)](#apidoc.element.path-to-regexp.compile)
1.  [function <span class="apidocSignatureSpan">path-to-regexp.</span>parse (str, options)](#apidoc.element.path-to-regexp.parse)
1.  [function <span class="apidocSignatureSpan">path-to-regexp.</span>tokensToFunction (tokens)](#apidoc.element.path-to-regexp.tokensToFunction)
1.  [function <span class="apidocSignatureSpan">path-to-regexp.</span>tokensToRegExp (tokens, keys, options)](#apidoc.element.path-to-regexp.tokensToRegExp)



# <a name="apidoc.module.path-to-regexp"></a>[module path-to-regexp](#apidoc.module.path-to-regexp)

#### <a name="apidoc.element.path-to-regexp.compile"></a>[function <span class="apidocSignatureSpan">path-to-regexp.</span>compile (str, options)](#apidoc.element.path-to-regexp.compile)
- description and source-code
```javascript
function compile(str, options) {
  return tokensToFunction(parse(str, options))
}
```
- example usage
```shell
...
## Usage

'''javascript
var pathToRegexp = require('path-to-regexp')

// pathToRegexp(path, keys, options)
// pathToRegexp.parse(path)
// pathToRegexp.compile(path)
'''

- **path** An Express-style string, an array of strings, or a regular expression.
- **keys** An array to be populated with the keys found in the path.
- **options**
- **sensitive** When 'true' the route will be case sensitive. (default: 'false')
- **strict** When 'false' the trailing slash is optional. (default: 'false')
...
```

#### <a name="apidoc.element.path-to-regexp.parse"></a>[function <span class="apidocSignatureSpan">path-to-regexp.</span>parse (str, options)](#apidoc.element.path-to-regexp.parse)
- description and source-code
```javascript
function parse(str, options) {
  var tokens = []
  var key = 0
  var index = 0
  var path = ''
  var defaultDelimiter = options && options.delimiter || '/'
  var res

  while ((res = PATH_REGEXP.exec(str)) != null) {
    var m = res[0]
    var escaped = res[1]
    var offset = res.index
    path += str.slice(index, offset)
    index = offset + m.length

    // Ignore already escaped sequences.
    if (escaped) {
      path += escaped[1]
      continue
    }

    var next = str[index]
    var prefix = res[2]
    var name = res[3]
    var capture = res[4]
    var group = res[5]
    var modifier = res[6]
    var asterisk = res[7]

    // Push the current path onto the tokens.
    if (path) {
      tokens.push(path)
      path = ''
    }

    var partial = prefix != null && next != null && next !== prefix
    var repeat = modifier === '+' || modifier === '*'
    var optional = modifier === '?' || modifier === '*'
    var delimiter = res[2] || defaultDelimiter
    var pattern = capture || group

    tokens.push({
      name: name || key++,
      prefix: prefix || '',
      delimiter: delimiter,
      optional: optional,
      repeat: repeat,
      partial: partial,
      asterisk: !!asterisk,
      pattern: pattern ? escapeGroup(pattern) : (asterisk ? '.*' : '[^' + escapeString(delimiter) + ']+?')
    })
  }

  // Match any characters still remaining.
  if (index < str.length) {
    path += str.substr(index)
  }

  // If the path exists, push it onto the end.
  if (path) {
    tokens.push(path)
  }

  return tokens
}
```
- example usage
```shell
...

## Usage

'''javascript
var pathToRegexp = require('path-to-regexp')

// pathToRegexp(path, keys, options)
// pathToRegexp.parse(path)
// pathToRegexp.compile(path)
'''

- **path** An Express-style string, an array of strings, or a regular expression.
- **keys** An array to be populated with the keys found in the path.
- **options**
- **sensitive** When 'true' the route will be case sensitive. (default: 'false')
...
```

#### <a name="apidoc.element.path-to-regexp.tokensToFunction"></a>[function <span class="apidocSignatureSpan">path-to-regexp.</span>tokensToFunction (tokens)](#apidoc.element.path-to-regexp.tokensToFunction)
- description and source-code
```javascript
function tokensToFunction(tokens) {
  // Compile all the tokens into regexps.
  var matches = new Array(tokens.length)

  // Compile all the patterns before compilation.
  for (var i = 0; i < tokens.length; i++) {
    if (typeof tokens[i] === 'object') {
      matches[i] = new RegExp('^(?:' + tokens[i].pattern + ')$')
    }
  }

  return function (obj, opts) {
    var path = ''
    var data = obj || {}
    var options = opts || {}
    var encode = options.pretty ? encodeURIComponentPretty : encodeURIComponent

    for (var i = 0; i < tokens.length; i++) {
      var token = tokens[i]

      if (typeof token === 'string') {
        path += token

        continue
      }

      var value = data[token.name]
      var segment

      if (value == null) {
        if (token.optional) {
          // Prepend partial segment prefixes.
          if (token.partial) {
            path += token.prefix
          }

          continue
        } else {
          throw new TypeError('Expected "' + token.name + '" to be defined')
        }
      }

      if (isarray(value)) {
        if (!token.repeat) {
          throw new TypeError('Expected "' + token.name + '" to not repeat, but received '' + JSON.stringify(value) + ''')
        }

        if (value.length === 0) {
          if (token.optional) {
            continue
          } else {
            throw new TypeError('Expected "' + token.name + '" to not be empty')
          }
        }

        for (var j = 0; j < value.length; j++) {
          segment = encode(value[j])

          if (!matches[i].test(segment)) {
            throw new TypeError('Expected all "' + token.name + '" to match "' + token.pattern + '", but received '' + JSON.stringify
(segment) + ''')
          }

          path += (j === 0 ? token.prefix : token.delimiter) + segment
        }

        continue
      }

      segment = token.asterisk ? encodeAsterisk(value) : encode(value)

      if (!matches[i].test(segment)) {
        throw new TypeError('Expected "' + token.name + '" to match "' + token.pattern + '", but received "' + segment + '"')
      }

      path += token.prefix + segment
    }

    return path
  }
}
```
- example usage
```shell
...
**Note:** The generated function will throw on invalid input. It will do all necessary checks to ensure the generated path is valid
. This method only works with strings.

### Working with Tokens

Path-To-RegExp exposes the two functions used internally that accept an array of tokens.

* 'pathToRegexp.tokensToRegExp(tokens, options)' Transform an array of tokens into a matching regular expression.
* 'pathToRegexp.tokensToFunction(tokens)' Transform an array of tokens into a path generator function.

#### Token Information

* 'name' The name of the token ('string' for named or 'number' for index)
* 'prefix' The prefix character for the segment ('/' or '.')
* 'delimiter' The delimiter for the segment (same as prefix or '/')
* 'optional' Indicates the token is optional ('boolean')
...
```

#### <a name="apidoc.element.path-to-regexp.tokensToRegExp"></a>[function <span class="apidocSignatureSpan">path-to-regexp.</span>tokensToRegExp (tokens, keys, options)](#apidoc.element.path-to-regexp.tokensToRegExp)
- description and source-code
```javascript
function tokensToRegExp(tokens, keys, options) {
  if (!isarray(keys)) {
    options = /** @type {!Object} */ (keys || options)
    keys = []
  }

  options = options || {}

  var strict = options.strict
  var end = options.end !== false
  var route = ''

  // Iterate over the tokens and create our regexp string.
  for (var i = 0; i < tokens.length; i++) {
    var token = tokens[i]

    if (typeof token === 'string') {
      route += escapeString(token)
    } else {
      var prefix = escapeString(token.prefix)
      var capture = '(?:' + token.pattern + ')'

      keys.push(token)

      if (token.repeat) {
        capture += '(?:' + prefix + capture + ')*'
      }

      if (token.optional) {
        if (!token.partial) {
          capture = '(?:' + prefix + '(' + capture + '))?'
        } else {
          capture = prefix + '(' + capture + ')?'
        }
      } else {
        capture = prefix + '(' + capture + ')'
      }

      route += capture
    }
  }

  var delimiter = escapeString(options.delimiter || '/')
  var endsWithDelimiter = route.slice(-delimiter.length) === delimiter

  // In non-strict mode we allow a slash at the end of match. If the path to
  // match already ends with a slash, we remove it for consistency. The slash
  // is valid at the end of a path match, not in the middle. This is important
  // in non-ending mode, where "/test/" shouldn't match "/test//route".
  if (!strict) {
    route = (endsWithDelimiter ? route.slice(0, -delimiter.length) : route) + '(?:' + delimiter + '(?=$))?'
  }

  if (end) {
    route += '$'
  } else {
    // In non-ending mode, we need the capturing groups to match as much as
    // possible by using a positive lookahead to the end or next path segment.
    route += strict && endsWithDelimiter ? '' : '(?=' + delimiter + '|$)'
  }

  return attachKeys(new RegExp('^' + route, flags(options)), keys)
}
```
- example usage
```shell
...

**Note:** The generated function will throw on invalid input. It will do all necessary checks to ensure the generated path is valid
. This method only works with strings.

### Working with Tokens

Path-To-RegExp exposes the two functions used internally that accept an array of tokens.

* 'pathToRegexp.tokensToRegExp(tokens, options)' Transform an array of tokens into a matching regular expression.
* 'pathToRegexp.tokensToFunction(tokens)' Transform an array of tokens into a path generator function.

#### Token Information

* 'name' The name of the token ('string' for named or 'number' for index)
* 'prefix' The prefix character for the segment ('/' or '.')
* 'delimiter' The delimiter for the segment (same as prefix or '/')
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
