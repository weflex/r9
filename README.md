# r9(1) -- npm registry manager

`r9` can help you easy and fast switch between different npm registries.

## Install

```sh
$ npm install -g r9
```

## Example

### List all registries

```sh
$ r9 ls

* npm ---- https://registry.npmjs.org/
  cnpm --- http://r.cnpmjs.org/
  taobao - http://registry.npm.taobao.org/
  eu ----- http://registry.npmjs.eu/
  au ----- http://registry.npmjs.org.au/
  sl ----- http://npm.strongloop.com/
  nj ----- https://registry.nodejitsu.com/
  pt ----- http://registry.npmjs.pt/

```

### Select a registry

```sh
$ r9 use weflex  //switch registry to weflex

    Registry has been set to: http://npm.weflex.org:2970/

```

## CLI Usage

```
Usage: r9 [options] [command]

  Commands:

    ls                           list all the registries
    use <registry>               change registry to registry
    add <registry> <url> [home]  add one custom registry
    del <registry>               delete one custom registry
    home <registry> [browser]    open the homepage of registry with optional browser
    test [registry]              show the response time for one or all registries
    help                         print this help

  Options:

    -h, --help     output usage information
    -V, --version  output the version number
```

## Registries

* [npm](https://www.npmjs.org)
* [wpm](http://npm.weflex.org)

## Thanks

This package is fork of [Pana/nrm](https://github.com/Pana/nrm), thanks for @Pana to create
the original repostory in the world.

## LICENSE

MIT
