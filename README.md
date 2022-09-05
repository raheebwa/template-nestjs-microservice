# NestJs Baseline template

- This is a NestJs baseline template utilizing the [12 factor App](https://12factor.net/) approach.

## Features

- Using `pnpm`

- Using Commitlint and Husky hooks to automate linting [![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

## How to use

- run `pnpm install`
- copy `.env.example` to `.env`
  - Change the port number for the database
- (Assuming docker is installed) run `docker compose up -d`, alternatively update your databse details as specified above in the `.env` file
