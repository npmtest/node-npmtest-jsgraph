# npmtest-jsgraph

#### basic test coverage for  [jsgraph (v0.7.1)](https://github.com/Encapsule/jsgraph)  [![npm package](https://img.shields.io/npm/v/npmtest-jsgraph.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jsgraph) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jsgraph.svg)](https://travis-ci.org/npmtest/node-npmtest-jsgraph)

#### DirectedGraph container class + BFT/DFT/transpose algorithms inspired by Boost C++ Graph Library API.

[![NPM](https://nodei.co/npm/jsgraph.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jsgraph)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jsgraph/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsgraph/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jsgraph/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jsgraph/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jsgraph/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jsgraph/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jsgraph/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jsgraph/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jsgraph/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsgraph/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jsgraph/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jsgraph/build/test-report.html](https://npmtest.github.io/node-npmtest-jsgraph/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jsgraph/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jsgraph/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jsgraph/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jsgraph/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsgraph/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsgraph/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jsgraph/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jsgraph/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "ChrisRus"
    },
    "bugs": {
        "url": "https://github.com/Encapsule/jsgraph/issues"
    },
    "dependencies": {},
    "description": "DirectedGraph container class + BFT/DFT/transpose algorithms inspired by Boost C++ Graph Library API.",
    "devDependencies": {
        "chai": "^1.10.0",
        "grunt": "^0.4.5",
        "grunt-contrib-clean": "^0.6.0",
        "grunt-contrib-jshint": "~0.10.0",
        "grunt-mocha-test": "^0.12.7",
        "mocha": "^2.1.0",
        "node-uuid": "^1.4.2"
    },
    "directories": {},
    "dist": {
        "shasum": "74c01a659d806b9bbb03b5a1639250f9aedcfba5",
        "tarball": "https://registry.npmjs.org/jsgraph/-/jsgraph-0.7.1.tgz"
    },
    "gitHead": "d9d0fc7e75552ca40fb9866097211d8dd305db34",
    "homepage": "https://github.com/Encapsule/jsgraph",
    "keywords": [
        "graph",
        "vertex",
        "vertices",
        "edge",
        "edges",
        "node",
        "nodes",
        "link",
        "algorithm",
        "depth-first search",
        "breadth-first search",
        "BFS",
        "DFS",
        "data modeling",
        "data",
        "JSON",
        "data semantics",
        "semantic data",
        "container",
        "dependency",
        "topological",
        "transpose",
        "filter",
        "transform",
        "route",
        "model",
        "classify",
        "classification",
        "analysis",
        "sorting",
        "in-memory",
        "database",
        "relational",
        "hyper-relational",
        "design pattern",
        "visit",
        "visitor"
    ],
    "license": "MIT",
    "main": "src/arc_core_graph.js",
    "maintainers": [
        {
            "name": "chrisrus"
        }
    ],
    "name": "jsgraph",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/Encapsule/jsgraph.git"
    },
    "scripts": {
        "test": "mocha -R spec ./test/test-jsgraph.js"
    },
    "version": "0.7.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
