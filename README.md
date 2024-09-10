# graphql-template

A base template for GraphQL development.

## Overview

This template is best used with [Github Codespaces](https://github.com/codespaces) or running in a local `devcontainer`. It is set up with code that will connect to the GitHub GraphQL API to show an example of operational configuration.

The devcontainer is preconfigured with settings to lint and format GraphQL files, install useful GraphQL extensions, and a few other helpful extensions such as Indent Rainbow.

## Usage

To utlize the Github GraphQL API you will need a properly scoped PAT, and an environment variable set named `GRAPHQL_TOKEN_GITHUB` which contains the value of the token. Set the value in your [GitHub Codespaces Settings](https://github.com/settings/codespaces), or set a local environment variable. The devcontainer configuration is set to read it either locally, or if set inside of GitHub so once set you can start executing queries.
