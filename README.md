# eslint-config

[Shareable config](https://eslint.org/docs/developer-guide/shareable-configs)
for [ESLint](https://eslint.org). Extends the [form8ion config](https://github.com/form8ion/eslint-config).

<!--status-badges start -->

[![Node CI Workflow Status][github-actions-ci-badge]][github-actions-ci-link]
![SLSA Level 2][slsa-badge]

<!--status-badges end -->

## Usage

<!--consumer-badges start -->

[![npm][npm-badge]][npm-link]
[![MIT license][license-badge]][license-link]
![node][node-badge]

<!--consumer-badges end -->

### Installation

```sh
$ npm install @travi/eslint-config --save-dev
```

### Add to the project config

Such as in an `.eslintrc.yml`

```yml
extends: '@travi'
```

## Contributing

<!--contribution-badges start -->

[![Conventional Commits][commit-convention-badge]][commit-convention-link]
[![Commitizen friendly][commitizen-badge]][commitizen-link]
[![semantic-release][semantic-release-badge]][semantic-release-link]
[![PRs Welcome][PRs-badge]][PRs-link]
[![Renovate][renovate-badge]][renovate-link]

<!--contribution-badges end -->

### Dependencies

```sh
$ nvm install
$ npm install
```

### Verification

```sh
$ npm test
```

[npm-link]: https://www.npmjs.com/package/@travi/eslint-config

[npm-badge]: https://img.shields.io/npm/v/@travi/eslint-config?logo=npm

[license-link]: LICENSE

[license-badge]: https://img.shields.io/github/license/travi/eslint-config.svg

[commit-convention-link]: https://conventionalcommits.org

[commit-convention-badge]: https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg

[commitizen-link]: http://commitizen.github.io/cz-cli/

[commitizen-badge]: https://img.shields.io/badge/commitizen-friendly-brightgreen.svg

[semantic-release-link]: https://github.com/semantic-release/semantic-release

[semantic-release-badge]: https://img.shields.io/badge/semantic--release-angular-e10079?logo=semantic-release

[PRs-link]: http://makeapullrequest.com

[PRs-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg

[renovate-link]: https://renovatebot.com

[renovate-badge]: https://img.shields.io/badge/renovate-enabled-brightgreen.svg?logo=renovatebot

[github-actions-ci-link]: https://github.com/travi/eslint-config/actions?query=workflow%3A%22Node.js+CI%22+branch%3Amaster

[github-actions-ci-badge]: https://github.com/travi/eslint-config/workflows/Node.js%20CI/badge.svg

[node-badge]: https://img.shields.io/node/v/@travi/eslint-config?logo=node.js

[slsa-badge]: https://slsa.dev/images/gh-badge-level2.svg
