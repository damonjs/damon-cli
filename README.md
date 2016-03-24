![logo](./media/logo.png)

> A CLI for the damon tool.

![logo](./media/demo.gif)

`damon` is a CLI that runs on [CasperJS](http://casperjs.org/) which runs on [PhantomJS](http://phantomjs.org/).

He feeds on JSON files that describe what tasks he needs to achieve on specified starting URL.

```bash
Usage:
  damon [OPTIONS] [COMMAND]

Commands:
  run <files...>  Run the list of JSON tasks files. Accept glob.

Options:
   -R, --reporter the reporter's path to use
   -h, --help     output usage information
   -V, --version  output the version number
```

## Installation

via NPM :

```bash
npm install -g damon-cli
```

## Usage

```bash
> damon run tasks.json
or
> damon run tasks1.json tasks2.json
or 
> damon run *.json
```
