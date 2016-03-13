# sql2graphql
[![Build Status](https://travis-ci.org/kmulvey/sql2graphql.svg?branch=master)](https://travis-ci.org/kmulvey/sql2graphql)
[![Coverage Status](https://coveralls.io/repos/github/kmulvey/sql2graphql/badge.svg?branch=master)](https://coveralls.io/github/kmulvey/sql2graphql?branch=master)

Generate a graphql schema in Go from an existing sql database.

This is currently alpha software that "works" for mysql but thats about it, [help is welcome](https://github.com/kmulvey/gographql/issues).


## Usage

  `go install github.com/kmulvey/sql2graphql`
  
  `sql2graphql [options]`

### Options:
  
  
  - `--output`    - Directory to use when generating code *`(string [required])`*
  - `--schema`    - Schema name *`(string [required])`*
  - `--hostname`  - Hostname of database server *`(string [default: "localhost"])`*
  - `--port`      - Port number of database server *`(number)`*
  - `--username`  - Username to use when connecting *`(string [default: "root"])`*
  - `--password`  - Password to use when connecting *`(string [default: ""])`*


## License

Apache2 licensed. See LICENSE.
