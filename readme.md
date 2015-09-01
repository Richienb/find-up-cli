# find-up-cli [![Build Status](https://travis-ci.org/sindresorhus/find-up-cli.svg?branch=master)](https://travis-ci.org/sindresorhus/find-up-cli)

> Find a file by walking up parent directories


## Install

```
$ npm install --global find-up-cli
```


## Usage

```
$ find-up --help

  Usage
    $ find-up <filename>

  Options
    --cwd=<dir>  Working directory
```


## Example

```
/
└── Users
    └── sindresorhus
        ├── unicorn.png
        └── foo
            └── bar
                ├── baz
                └── faz
```

```
$ echo $PWD
/Users/sindresorhus/foo/bar/faz
$ find-up unicorn.png
/Users/sindresorhus/unicorn.png
```


## Related

- [find-up](https://github.com/sindresorhus/find-up) - API for this module


## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
