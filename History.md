# 0.3.2 / 2016-06-17

* Deprecated the whole module. Since v1.0.0, Node.js embeds implementation of both `fs.access()` and `fs.accessSync()`.

# 0.3.1 / 2016-04-09

* Fixed memory leak and upgraded to latest package versions

# 0.3.0 / 2015-09-10

* Rewritten the module by using `Nan` module to eliminate incompatibilities with new V8 versions (preparation for Node.js 4.0)

# 0.2.0 / 2015-03-14

* Updated the module to be compilable under Node.js 0.12.x where API of new V8 version has changed

# 0.1.1 / 2013-11-08

* Added `mocha` and `should` versions into devDependencies in package.json to prevent future incompatibilities

# 0.1.0 / 2013-11-06

* Initial release with both sync and async versions of the UNIX access() wrapper functions
