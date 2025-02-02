[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.paypal.butterfly/butterfly-core/badge.svg?style=flat)](http://search.maven.org/#search|ga|1|g:com.paypal.butterfly)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![javadoc](https://javadoc.io/badge2/com.paypal.butterfly/butterfly-utilities/javadoc.svg?label=butterfly-utilities-javadoc)](https://javadoc.io/doc/com.paypal.butterfly/butterfly-utilities)
[![javadoc](https://javadoc.io/badge2/com.paypal.butterfly/butterfly-extensions-api/javadoc.svg?label=butterfly-extensions-api-javadoc)](https://javadoc.io/doc/com.paypal.butterfly/butterfly-extensions-api)

<br><br>
<div style="text-align:center"><img src ="docs/img/logo/butterfly.png" /></div>
<br>

Butterfly is an application code transformation tool, and commonly it is used to perform **automated application migrations**, **upgrades** and **source code and configuration changes**.

Visit <a href="https://paypal.github.io/butterfly/" target="_blank">Butterfly website</a> for further information.

## Features

* Automated application source code transformations
    * Application upgrades
    * Application migrations
    * Source code and configuration changes
* Plugable mechanism for Butterfly extensions, containing transformation and/or upgrade templates
* Multiple types of ready-to-use transformation utilities, including for example manipulating text, properties, XML, POM and Java files
* Resilient transformation pipeline
    * Shared context among transformation utilities
    * Error handling
    * Dependency management among transformation utilities
    * Conditional transformation utilities
* Transformation utilities execution in different modes and fashions
    * Configurable utilities
    * Anonymous utilities
    * Multiple execution
    * Group execution
    * In-loop execution
* Post-transformation features
    * Manual steps Reporting
    * Metrics
* APIs
    * Extensions API
    * API for custom transformation utilities and operations
    * Facade for Java application integration
* Command-Line-Interface tool
* Logging in silent or verbose mode, in info or debug level, and on console or file

## Quick start
Read the <a href="https://paypal.github.io/butterfly/QUICK_START" target="_blank">Quick Start</a> page to learn how to use Butterfly by transforming a sample application.
Visit <a href="https://paypal.github.io/butterfly/" target="_blank">Butterfly website</a> for further information.

## Release notes
See [Butterfly release notes](docs/RELEASE_NOTES.md).

## Reporting an issue
Please open an issue using our [GitHub issues](https://github.com/paypal/butterfly/issues) page.

## Contributing
You are very welcome to contribute to Butterfly! Read our [Contribution guidelines](docs/CONTRIBUTING.md).

## License
This project is licensed under the [MIT License](LICENSE.txt).
