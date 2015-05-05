# package.json profiles

Emulate "profiles" in Node by selecting a profile from a group of valid package.json files and writing it to a new `./package.json` file.

## Alternative profiles

Profiles are individual valid `package.json` files located in `./packages/` and named `<profile>.package.json`.

## Example usage

Select the ___remote___ profile from the available profiles "remote" (`./packages/remote.package.json`) and "local" (`./packages/local.package.json`):

```
$ ./select-profile remote
$ npm start 
```
