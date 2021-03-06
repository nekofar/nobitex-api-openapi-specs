# Changelog
All notable changes to this project will be documented in this file.

## [1.0.3] - 2021-11-19

### Miscellaneous Tasks

- Bump actions/checkout from 2.3.5 to 2.4.0
- Bump softprops/action-gh-release from 0.1.14 to 1
- Add `openapi-to-postmanv2:2.12.0` package
- Add new script for convert openapi spec to postman collection

## [1.0.2] - 2021-10-12

### Bug Fixes

- Add missing `execution` property for `market/orders/add` on `requestBody`

### Refactor

- Update `market/orders/add` examples

## [1.0.1] - 2021-09-24

### Documentation

- Add the contributing file
- Add link to the api docs to the readme

### Miscellaneous Tasks

- Add new script for test
- Change version over main file to 1.0.1

## [1.0.0] - 2021-09-24

### Bug Fixes

- Change indentation of components on main file
- Add missing default response for trades endpoint
- Add missing trailing slash for login endpoint
- Downgrade openapi version due to editor incompatibility
- Change `auth/login` request body content type to multipart
- Replace referenced errors for `auth/login` in docs by real ones
- Add security section for `auth/login`
- Add security section for `auth/logout`
- Change bearer auth type from http to apiKey
- Change `market/stats` request body content type to multipart
- Add missing `operationId` whenever that needed
- Add the missing url for license on openapi
- Change `hours` type from float to number on `market/orders/cancel-old`
- Add base `description` whenever that needed
- Change `description` property type to string over `users/referral/links-list`
- Solve indentation issue over `users/wallets/list` responses
- Replace `examples` by `example` over `v2/orderbook` responses
- Solve some issues over `v2/wallets` responses

### Documentation

- Add the main license file
- Add funding configuration file
- Improve `auth/login` descriptions
- Add summary for `v2/orderbook` endpoint
- Add example for `v2/orderbook` parameters
- Add `externalDocs` for `v2/orderbook` endpoint
- Add `externalDocs` for `v2/trades` endpoint
- Add an example for `v2/trades` endpoint parameters
- Add `externalDocs` for `market/stats` endpoint
- Add an example for `market/stats` endpoint `requestBody`
- Add new global property for `market/stats` endpoint responses
- Add summery and description for `market/stats` endpoint
- Add `externalDocs` for `market/udf/history` endpoint
- Add the readme file
- Add badges to the readme file

### Features

- Add missing `securitySchemes` section
- Add `externalDocs` for `auth/login` endpoint

### Miscellaneous Tasks

- Add main specification file and files and folders structure
- Add `UnexpectedError` response and `Error` schema
- Update auth login structure and schema
- Update `Error` schema
- Update auth logout structure and schema
- Update orderbook structure and schema
- Update trades structure and schema
- Update market stats structure and schema
- Update market udf history structure and schema
- Add a link to external doc for login endpoint
- Add missing summery fields whenever is required
- Ignore trailing slash for `auth/login` and `auth/logout`
- Ignore package lock file
- Add package json config file
- Add `@redocly/openapi-cli:^1.0.0-beta.61` package
- Add custom scripts for lint and build project
- Remove version from package file
- Add `git-clif` config file

### Refactor

- Improve `auth/logout` responses
- Improve example response for `v2/trades` endpoint
- Cleanup endpoints and schema files
- Update the `market/global-stats` structure and schemas
- Replace `patternProperties` by `additionalProperties` on the `market/stats` structure and schemas
- Cleanup endpoints and schema files
- Update the `users/profile` structure and schemas
- Update the `users/login-attempts` structure and schemas
- Update the `users/cards-add` structure and schemas
- Update the `users/accounts-add` structure and schemas
- Update the `users/limitations` structure and schemas
- Update the `users/wallets/list` structure and schemas
- Update the `v2/wallets` structure and schemas
- Update the `users/wallets/balance` structure and schemas
- Update the `users/wallets/transactions/list` structure and schemas
- Update the `users/wallets/deposits/list` structure and schemas
- Update the `users/wallets/generate-address` structure and schemas
- Update the `market/orders/add` structure and schemas
- Update the `market/orders/status` structure and schemas
- Update the `market/orders/list` structure and schemas
- Update the `market/orders/update-status` structure and schemas
- Update the `market/orders/cancel-old` structure and schemas
- Update the `security/emergency-cancel/activate` structure and schemas
- Update the `users/referral/links-list` structure and schemas
- Update the `users/get-referral-code` structure and schemas
- Update the `users/referral/referral-status` structure and schemas
- Update the `users/referral/set-referrer` structure and schemas
- Cleanup endpoints and schema files
- Cleanup endpoints and schema files
- Extract `symbol` parameter from `market/udh/history`
- Extract `symbol` parameter from `v2/orders` and `v2/trades`
- Add `UnexpectedError` to the responses index

<!-- generated by git-cliff -->
