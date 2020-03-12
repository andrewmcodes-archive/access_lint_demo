# README

## Install

### Clone the repository

```shell
git clone git@github.com:andrewmcodes/access_lint_demo.git
cd access_lint_demo
```

### Dependencies

- Ruby 2.7
- Node 13.7.0
- Rails 6.0.2.1
- Webpacker 4.2.2
- SQLite

### Install dependencies

Using [Bundler](https://github.com/bundler/bundler) and [Yarn](https://github.com/yarnpkg/yarn):

```shell
bundle && yarn
```

### Initialize the database

```shell
bin/rails db:setup
```

## Serve

```shell
rails s
```

If you want to run the `webpack-dev-server`, run this in another tab:

```shell
bin/webpack-dev-server
```
