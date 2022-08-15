# <img src="https://raw.githubusercontent.com/swagger-api/swagger.io/wordpress/images/assets/SWU-logo-clr.png" width="300">

[![NPM version](https://badge.fury.io/js/swagger-ui.svg)](http://badge.fury.io/js/swagger-ui)
[![Build Status](https://jenkins.swagger.io/view/OSS%20-%20JavaScript/job/oss-swagger-ui-master/badge/icon?subject=jenkins%20build)](https://jenkins.swagger.io/view/OSS%20-%20JavaScript/job/oss-swagger-ui-master/)
[![npm audit](https://jenkins.swagger.io/buildStatus/icon?job=oss-swagger-ui-security-audit&subject=npm%20audit)](https://jenkins.swagger.io/job/oss-swagger-ui-security-audit/lastBuild/console)
![total GitHub contributors](https://img.shields.io/github/contributors-anon/swagger-api/swagger-ui.svg)

![monthly npm installs](https://img.shields.io/npm/dm/swagger-ui.svg?label=npm%20downloads)
![total docker pulls](https://img.shields.io/docker/pulls/swaggerapi/swagger-ui.svg)
![monthly packagist installs](https://img.shields.io/packagist/dm/swagger-api/swagger-ui.svg?label=packagist%20installs)
![gzip size](https://img.shields.io/bundlephobia/minzip/swagger-ui.svg?label=gzip%20size)

## Introduction
[Swagger UI](https://swagger.io/tools/swagger-ui/) allows anyone — be it your development team or your end consumers — to visualize and interact with the API’s resources without having any of the implementation logic in place. It’s automatically generated from your OpenAPI (formerly known as Swagger) Specification, with the visual documentation making it easy for back end implementation and client side consumption.

#### Usage
- hot dev     = npm run dev
- build       = npm run build
- serve built = npm run serve-static

#### Customization
- [Overview](docs/customization/overview.md)
- [Plugin API](docs/customization/plugin-api.md)
- [Custom layout](docs/customization/custom-layout.md)

#### Development
- [Setting up](docs/development/setting-up.md)
- [Scripts](docs/development/scripts.md)

#### Contributing
- [Contributing](https://github.com/swagger-api/.github/blob/master/CONTRIBUTING.md)

##### Integration Tests

You will need JDK of version 7 or higher as instructed here
https://nightwatchjs.org/guide/getting-started/installation.html#install-selenium-server

Integration tests can be run locally with `npm run e2e` - be sure you aren't running a dev server when testing!

### Browser support
Swagger UI works in the latest versions of Chrome, Safari, Firefox, and Edge.

### Known Issues

To help with the migration, here are the currently known issues with 3.X. This list will update regularly, and will not include features that were not implemented in previous versions.

- Only part of the parameters previously supported are available.
- The JSON Form Editor is not implemented.
- Support for `collectionFormat` is partial.
- l10n (translations) is not implemented.
- Relative path support for external files is not implemented.

## Security contact

Please disclose any security-related issues or vulnerabilities by emailing [security@swagger.io](mailto:security@swagger.io), instead of using the public issue tracker.

## License

SwaggerUI is licensed under [Apache 2.0 license](https://github.com/swagger-api/swagger-ui/blob/master/LICENSE).
SwaggerUI comes with an explicit [NOTICE](https://github.com/swagger-api/swagger-ui/blob/master/NOTICE) file
containing additional legal notices and information.
