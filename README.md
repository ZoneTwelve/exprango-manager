# Exprango-cli (aka exprango-manager)
it's a tool for [exprango](https://www.npmjs.com/package/exprango), Click the link for [More info](https://github.com/ZoneTwelve/exprango).

# Introduction

every framework, toolkit, and service has a command line interface for that own app, currently, to support the exprango easily, I will need a exprango-cli.

# How to

oclif is a tool for creating CLI apps on the node.js, we can start it by the following command:

`npx oclif generate exprango-cli`

then answer a few question:

- npm package name: **exprango-cli**
- command bin name the CLI will export: **exprango**
- description: **A CLI kit for exprango**
- Author: ZoneTwelve @ZoneTwelve
- License: ********************Apache-2.0********************
- Github owner or repo: **ZoneTwelve**
- GitHub name of repo: **exprango-cli**
- Package manager: ******npm******

After the serial question, you will got the basic CLI kit for the application

# Development

- Language: TypeScript
- Testkit: Mocha

Now, it’s your turn to design the CLI app for your own service.

## Design

- new
    - for creating a new exprango project
- makemigration
    - Check and Create the template of the SQL Structure
- migrate
    - merge into the current SQL (include empty Tables)

That’s it.
