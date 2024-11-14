# `jsonnet-lib-consumer-test`

This repository's only purpose is to test `jsonnet` by importing a 
package that I've made ([the package's repository](https://github.com/botflux/jsonnet-lib-test)).

I just wanted to learn how packaging work with jsonnet and jb.

## Generate the JSON

```bash
# install dependencies via `jb`, a `jsonnet` package manager.
jb install

# run jsonnet with -J to include the package installed by `jb`.
jsonnet -J vendor main.jsonnet
```