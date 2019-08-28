# nr1-infra-geoops-nerdpack

![GitHub release (latest SemVer including pre-releases)](https://img.shields.io/github/v/release/newrelic/nr1-infra-geoops-nerdpack?include_prereleases&sort=semver) ![AppVeyor](https://img.shields.io/appveyor/ci/newrelic/nr1-infra-geoops-nerdpack) [![Snyk](https://snyk.io/test/github/newrelic/nr1-infra-geoops-nerdpack/badge.svg)](https://snyk.io/test/github/hospitalrun/hospitalrun-frontend)

## Usage

nr1-infra-geoops-nerdpack provides a geographic exploration of Infrastructure and APM data tied to a point of sale solution.

![Screenshot #1](screenshots/screenshot_01.png)

## Open Source License

This project is distributed under the [Apache 2 license](blob/master/LICENSE).

## What do you need to make this work?

1. [New Relic Infrastructure Agent(s) installed](https://newrelic.com/products/infrastructure) and the related access to [New Relic One](https://newrelic.com/platform).
2. (Recommended) Add the customer-defined `locationId` to the `newrelic_infra.yml`. See an example [here](blob/master/examples/example_newrelic_infra.yml).
3. (Currently) Updating (or replacing) the [geoopsConfig.js](blob/master/geoopsConfig.js) file.

## Getting started

Clone this repository and run the following scripts:

```bash
git clone https://github.com/newrelic/nr1-infra-geoops-nerdpack.git
cd nr1-infra-geoops-nerdpack
npm install
npm start
```

Visit https://one.newrelic.com/?nerdpacks=local, navigate to the Nerdpack, and :sparkles:

# Support

New Relic has open-sourced this project. This project is provided AS-IS WITHOUT WARRANTY OR SUPPORT, although you can report issues and contribute to the project here on GitHub.

_Please do not report issues with this software to New Relic Global Technical Support._

## Community

New Relic hosts and moderates an online forum where customers can interact with New Relic employees as well as other customers to get help and share best practices. Like all official New Relic open source projects, there's a related Community topic in the New Relic Explorer's Hub. You can find this project's topic/threads here:

https://discuss.newrelic.com/c/build-on-new-relic/nr1-infra-geoops-nerdpack
*(Note: URL subject to change before GA)*

## Issues / Enhancement Requests

Issues and enhancement requests can be submitted in the [Issues tab of this repository](issues). Please search for and review the existing open issues before submitting a new issue.

# Contributing

Contributions are welcome (and if you submit a Enhancement Request, expect to be invited to contribute it yourself :grin:). Please review our [Contributors Guide](blob/master/CONTRIBUTING.md).

Keep in mind that when you submit your pull request, you'll need to sign the CLA via the click-through using CLA-Assistant. If you'd like to execute our corporate CLA, or if you have any questions, please drop us an email at opensource@newrelic.com.