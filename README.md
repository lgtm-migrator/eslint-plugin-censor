# eslint-plugin-censor
The plugin will prevent you from using swear pejoratives and abuse words.

[![Version][badge-vers]][npm]
[![Bundle size][npm-size-badge]][npm-size-url]
[![Downloads][npm-downloads-badge]][npm]

[![CodeFactor][codefactor-badge]][codefactor-url]
[![SonarCloud][sonarcloud-badge]][sonarcloud-url]
[![Codacy][codacy-badge]][codacy-url]
[![Total alerts][lgtm-alerts-badge]][lgtm-alerts-url]
[![Language grade][lgtm-lg-badge]][lgtm-lg-url]
[![Scrutinizer][scrutinizer-badge]][scrutinizer-url]

[![Dependencies][badge-deps]][npm]
[![Vulnerabilities][badge-vuln]](https://snyk.io/)
[![Build Status][tests-badge]][tests-url]
[![Coverage Status][badge-coverage]][url-coverage]

[![Commit activity][commit-activity-badge]][github]
[![License][badge-lic]][github]

## Table of Contents
  - [Requirements](#requirements)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Sources](#sources)
  - [Contribute](#contribute)

## Requirements
To use library you need to have [node](https://nodejs.org) and [npm](https://www.npmjs.com) installed in your machine:

* node `6.0+`
* npm `3.0+`

## Installation

To install the library run the following command

```bash
  npm i --save-dev eslint-plugin-censor
```

## Usage

After installation, add plugin to [eslint](https://eslint.org/docs/user-guide/configuring/configuration-files#using-configuration-files) config:

```json
{
    "extends": [...],
    "env": {...},
    "plugins": [ "censor" ],
    "rules": {...}
}
```

And enable rule:
```json
{
    "extends": [...],
    "env": {...},
    "plugins": [ "censor" ],
    "rules": {
      ...
      "censor/no-swear": 2
    }
}
```

Now you can check your courtesy by running eslint.


## Sources

* [wiktionary](https://en.wiktionary.org/wiki/Category:English_swear_words)
* https://github.com/MauriceButler/badwords
* https://github.com/LDNOOBW/List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words
* https://github.com/first20hours/google-10000-english

## Contribute

Make the changes to the code and tests. Then commit to your branch. Be sure to follow the commit message conventions.

Commit message summaries must follow this basic format:
```
  Tag: Message (fixes #1234)
```

The Tag is one of the following:
* **Fix** - for a bug fix.
* **Update** - for a backwards-compatible enhancement.
* **Breaking** - for a backwards-incompatible enhancement.
* **Docs** - changes to documentation only.
* **Build** - changes to build process only.
* **New** - implemented a new feature.
* **Upgrade** - for a dependency upgrade.
* **Chore** - for tests, refactor, style, etc.

The message summary should be a one-sentence description of the change. The issue number should be mentioned at the end.


[npm]: https://www.npmjs.com/package/eslint-plugin-censor
[github]: https://github.com/pustovitDmytro/eslint-plugin-censor
[coveralls]: https://coveralls.io/github/pustovitDmytro/eslint-plugin-censor?branch=master
[badge-deps]: https://img.shields.io/david/pustovitDmytro/eslint-plugin-censor.svg
[badge-vuln]: https://img.shields.io/snyk/vulnerabilities/npm/eslint-plugin-censor.svg?style=popout
[badge-vers]: https://img.shields.io/npm/v/eslint-plugin-censor.svg
[badge-lic]: https://img.shields.io/github/license/pustovitDmytro/eslint-plugin-censor.svg
[badge-coverage]: https://coveralls.io/repos/github/pustovitDmytro/eslint-plugin-censor/badge.svg?branch=master
[url-coverage]: https://coveralls.io/github/pustovitDmytro/eslint-plugin-censor?branch=master

[tests-badge]: https://img.shields.io/circleci/build/github/pustovitDmytro/eslint-plugin-censor
[tests-url]: https://app.circleci.com/pipelines/github/pustovitDmytro/eslint-plugin-censor

[codefactor-badge]: https://www.codefactor.io/repository/github/pustovitdmytro/eslint-plugin-censor/badge
[codefactor-url]: https://www.codefactor.io/repository/github/pustovitdmytro/eslint-plugin-censor

[commit-activity-badge]: https://img.shields.io/github/commit-activity/m/pustovitDmytro/eslint-plugin-censor

[scrutinizer-badge]: https://scrutinizer-ci.com/g/pustovitDmytro/eslint-plugin-censor/badges/quality-score.png?b=master
[scrutinizer-url]: https://scrutinizer-ci.com/g/pustovitDmytro/eslint-plugin-censor/?branch=master

[lgtm-lg-badge]: https://img.shields.io/lgtm/grade/javascript/g/pustovitDmytro/eslint-plugin-censor.svg?logo=lgtm&logoWidth=18
[lgtm-lg-url]: https://lgtm.com/projects/g/pustovitDmytro/eslint-plugin-censor/context:javascript

[lgtm-alerts-badge]: https://img.shields.io/lgtm/alerts/g/pustovitDmytro/eslint-plugin-censor.svg?logo=lgtm&logoWidth=18
[lgtm-alerts-url]: https://lgtm.com/projects/g/pustovitDmytro/eslint-plugin-censor/alerts/

[codacy-badge]: https://app.codacy.com/project/badge/Grade/a0c20fb89e0a40259f4c8e53810a5186
[codacy-url]: https://www.codacy.com/gh/pustovitDmytro/eslint-plugin-censor/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=pustovitDmytro/eslint-plugin-censor&amp;utm_campaign=Badge_Grade

[sonarcloud-badge]: https://sonarcloud.io/api/project_badges/measure?project=pustovitDmytro_eslint-plugin-censor&metric=alert_status
[sonarcloud-url]: https://sonarcloud.io/dashboard?id=pustovitDmytro_eslint-plugin-censor

[npm-downloads-badge]: https://img.shields.io/npm/dw/eslint-plugin-censor
[npm-size-badge]: https://img.shields.io/bundlephobia/min/eslint-plugin-censor
[npm-size-url]: https://bundlephobia.com/result?p=eslint-plugin-censor
