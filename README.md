# package.json profiles

Emulate "profiles" in Node by selecting a profile from a group of package.json files.

Example: Select the ___remote___ profile from the available profiles "remote" (`./packages/remote.package.json`) and "local" (`./packages/local.package.json`):

```
$ ./select-profile remote`
$ npm start 
```
