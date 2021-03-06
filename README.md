# graphql-cli-bundle [![npm](https://img.shields.io/npm/v/graphql-cli-bundle.svg?style=for-the-badge)]() 
[![CircleCI](https://img.shields.io/circleci/project/github/supergraphql/graphql-cli-bundle.svg?style=for-the-badge)]()[![David](https://img.shields.io/david/supergraphql/graphql-cli-bundle.svg?style=for-the-badge)]()[![Greenkeeper badge](https://img.shields.io/badge/Greenkeeper-enabled-brightgreen.svg?style=for-the-badge)](https://greenkeeper.io/)  
Plugin for [`graphql-cli`](https://github.com/graphql-cli/graphql-cli). Processes import statements in a GraphQL schema using [`graphql-import`](https://github.com/graphcool/graphql-import) and outputs a single schema file.

## Installation

Install `graphql-cli-bundle` either globally (recommended) or locally using your favorite package manager:
```shell
$ yarn [global] add graphql-cli-bundle
$ npm install graphql-cli-bundle [--global]
```

## Usage
```
graphql bundle [schema]

Process import statements in a schema and output a single schema file

Options:
  --dotenv       Path to .env file                                      [string]
  -p, --project  Project name                                           [string]
  --schema       Schema file to process                                 [string]
  --output, -o   Filename of output schema                   [string] [required]
  --force, -f    Force overwriting exissting output file               [boolean]
  -h, --help     Show help                                             [boolean]
  -v, --version  Show version number                                   [boolean]
```
<hr>
<p align="center">
  <img src="https://img.shields.io/badge/built-with_love-blue.svg?style=for-the-badge"/><a href="https://github.com/kbrandwijk" target="-_blank"><img src="https://img.shields.io/badge/by-kim_brandwijk-blue.svg?style=for-the-badge"/></a>
</p>
