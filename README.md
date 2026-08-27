# Awesome Jest with stars

> An awesome list of [Jest](https://jestjs.io) packages and resources

## Contents

* [Packages](#packages)
  * [Matchers](#matchers)
  * [IDE](#ide)
  * [Linting](#linting)
  * [Runners](#runners)
  * [Reporters](#reporters)
  * [Results Processors](#results-processors)
  * [Environments](#environments)
  * [Coverage](#coverage)
  * [Snapshot](#snapshot)
  * [Migration](#migration)
  * [Library extensions](#library-extensions)
  * [Mocks](#mocks)
  * [Watch Plugins](#watch-plugins)
  * [Processor](#processor)
  * [Presets](#presets)
  * [Generators](#generators)
  * [Debug](#debug)
* [Resources](#resources)

## Packages

### Matchers

* [@emotion/jest](https://github.com/emotion-js/emotion/tree/main/packages/jest) ⭐ 18,019 | 🐛 392 | 🌐 JavaScript | 📅 2026-08-26 Jest matcher for testing Emotion components.
* [@testing-library/jest-dom](https://github.com/testing-library/jest-dom) ⭐ 4,597 | 🐛 143 | 🌐 JavaScript | 📅 2026-08-09 Jest matchers to test the state of the DOM.
* [expect-puppeteer](https://github.com/smooth-code/jest-puppeteer/tree/master/packages/expect-puppeteer) ⭐ 3,544 | 🐛 22 | 🌐 TypeScript | 📅 2026-03-26 Collection of matchers for Jest & Puppeteer.
* [jest-extended](https://github.com/jest-community/jest-extended) ⭐ 2,350 | 🐛 122 | 🌐 TypeScript | 📅 2026-08-27 Adds additional matchers to core API making it easy to test everything.
* [jest-axe](https://github.com/nickcolley/jest-axe) ⭐ 1,111 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-10 Jest matcher for [axe](https://github.com/dequelabs/axe-core) ⭐ 7,449 | 🐛 432 | 🌐 JavaScript | 📅 2026-08-27 for testing accessibility.
* [jest-enzyme](https://github.com/FormidableLabs/enzyme-matchers/tree/master/packages/jest-enzyme) ⭐ 886 | 🐛 50 | 🌐 JavaScript | 📅 2024-03-07 An assertion library for enzyme.
* [@testing-library/jest-native](https://github.com/testing-library/jest-native) ⭐ 439 | 🐛 7 | 🌐 TypeScript | 📅 2025-03-05 Jest matchers to test the state of React Native.
* [@traceloop/jest-opentelemetry](https://github.com/traceloop/jest-opentelemetry) ⭐ 255 | 🐛 11 | 🌐 JavaScript | 📅 2023-11-16 Collection of matchers and runner for end to end tests with Jest & OpenTelemetry.
* [jest-openapi](https://github.com/openapi-library/OpenAPIValidators/tree/master/packages/jest-openapi) ⭐ 195 | 🐛 53 | 🌐 TypeScript | 📅 2023-03-04 Jest matchers for asserting that HTTP responses satisfy an [OpenAPI](https://swagger.io/docs/specification/about) spec.
* [expect-more](https://github.com/JamieMason/expect-more/tree/master/packages/expect-more-jest) ⭐ 172 | 🐛 8 | 🌐 TypeScript | 📅 2023-02-16 A huge library of test matchers for a range of common use-cases.
* [jest-json-schema](https://github.com/americanexpress/jest-json-schema) ⭐ 172 | 🐛 10 | 🌐 JavaScript | 📅 2026-07-13 JSON schema matcher.
* [jest-generator](https://github.com/doniyor2109/jest-generator) ⭐ 31 | 🐛 1 | 🌐 JavaScript | 📅 2021-04-08 Jest matcher for testing generator function.
* [jest-json](https://github.com/duailibe/jest-json) ⭐ 16 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-09 Jest matchers to assert on JSON strings.
* [jest-shell-matchers](https://github.com/raingerber/jest-shell-matchers) ⭐ 8 | 🐛 1 | 🌐 JavaScript | 📅 2019-01-12 Test shell scripts while mocking specific commands.

### IDE

* [vscode-jest](https://github.com/jest-community/vscode-jest) ⭐ 2,890 | 🐛 214 | 🌐 TypeScript | 📅 2026-03-20 Works out of the box Jest based testing in VS Code.
* [wallaby](https://github.com/wallabyjs/public) ⭐ 774 | 🐛 151 | 📅 2026-07-01 The pinnacle of the idea of a test runner integrated into an editor.
* [vscode-jest-runner](https://github.com/firsttris/vscode-jest-runner) ⭐ 301 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-10 Simple way to run or debug one or more tests from context menu, codelens or command plalette.
* [jester](https://github.com/David-Kunz/jester) ⭐ 213 | 🐛 4 | 🌐 Lua | 📅 2025-01-15 A Neovim plugin to easily run and debug Jest tests.
* [coc-jest](https://github.com/neoclide/coc-jest) ⭐ 51 | 🐛 4 | 🌐 TypeScript | 📅 2025-04-19 Jest plugin for [coc.nvim](https://github.com/neoclide/coc.nvim) ⭐ 25,168 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-27.

### Linting

* [eslint-plugin-jest](https://github.com/jest-community/eslint-plugin-jest) ⭐ 1,170 | 🐛 23 | 🌐 TypeScript | 📅 2026-08-27 ESLint plugin for Jest.
* [eslint-plugin-jest-dom](https://github.com/testing-library/eslint-plugin-jest-dom) ⭐ 369 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-03 ESLint plugin to follow best practices and anticipate common mistakes when writing tests with [@testing-library/jest-dom](https://github.com/testing-library/jest-dom) ⭐ 4,597 | 🐛 143 | 🌐 JavaScript | 📅 2026-08-09.
* [eslint-plugin-jest-formatting](https://github.com/dangreenisrael/eslint-plugin-jest-formatting) ⭐ 159 | 🐛 5 | 🌐 JavaScript | 📅 2023-05-21 ESLint plugin that aims to provide formatting rules (auto-fixable where possible) to ensure consistency and readability in jest test suites.
* [eslint-plugin-jest-extended](https://github.com/jest-community/eslint-plugin-jest-extended) ⭐ 22 | 🐛 16 | 🌐 TypeScript | 📅 2026-08-26 ESLint plugin for [jest-extended](https://github.com/jest-community/jest-extended) ⭐ 2,350 | 🐛 122 | 🌐 TypeScript | 📅 2026-08-27.

### Runners

* [jest-runner-eslint](https://github.com/jest-community/jest-runner-eslint) ⭐ 480 | 🐛 38 | 🌐 JavaScript | 📅 2026-08-26 ESLint runner for Jest.
* [jest-light-runner](https://github.com/nicolo-ribaudo/jest-light-runner) ⭐ 242 | 🐛 20 | 🌐 JavaScript | 📅 2026-07-31 Runner that runs tests directly in bare Node.js, without virtualizing the environment.
* [jest-runner-tsc](https://github.com/azz/jest-runner-tsc) ⭐ 178 | 🐛 8 | 🌐 JavaScript | 📅 2020-11-18 A Jest runner for the TypeScript compiler.
* [jest-runner-groups](https://github.com/eugene-manuilov/jest-runner-groups) ⚠️ Archived A runner that lets to group tests and to run groups separately.
* [jest-runner-prettier](https://github.com/keplersj/jest-runner-prettier) ⭐ 91 | 🐛 20 | 🌐 TypeScript | 📅 2026-08-26 Prettier runner for Jest.
* [jest-runner-tsd](https://github.com/jest-community/jest-runner-tsd) ⭐ 77 | 🐛 15 | 🌐 TypeScript | 📅 2026-08-26 Runner for running TypeScript type tests.
* [jest-runner-mocha](https://github.com/rogeliog/jest-runner-mocha) ⭐ 71 | 🐛 16 | 🌐 JavaScript | 📅 2020-02-04 Mocha runner for Jest.
* [jest-electron-runner](https://github.com/d4rkr00t/jest-electron-runner) ⭐ 49 | 🐛 4 | 🌐 JavaScript | 📅 2017-09-18 Electron runner for Jest.
* [jest-runner-stylelint](https://github.com/keplersj/jest-runner-stylelint) ⭐ 19 | 🐛 13 | 🌐 JavaScript | 📅 2024-06-18 Stylelint runner for Jest.

### Reporters

* [jest-html-reporters](https://github.com/Hazyzh/jest-html-reporters) ⭐ 540 | 🐛 19 | 🌐 JavaScript | 📅 2026-08-07 A Jest test results processor for generating a summary in HTML.
* [jest-junit](https://github.com/jest-community/jest-junit) ⭐ 502 | 🐛 14 | 🌐 JavaScript | 📅 2026-08-20 A JUnit format reporter for Jest which can integrate with CI systems.
* [jest-html-reporter](https://github.com/Hargne/jest-html-reporter) ⭐ 287 | 🐛 2 | 🌐 TypeScript | 📅 2026-06-28 A Jest test results processor for generating a summary in HTML.
* [jest-stare](https://github.com/dkelosky/jest-stare) ⭐ 269 | 🐛 11 | 🌐 TypeScript | 📅 2026-08-14 Configurable HTML reporter for filtering, side-by-side snapshot diffs, API, and simple CLI.
* [jest-silent-reporter](https://github.com/rickhanlonii/jest-silent-reporter) ⭐ 158 | 🐛 4 | 🌐 JavaScript | 📅 2024-05-22 A silent reporter for Jest.
* [testomatio-jest-reporter](https://github.com/testomatio/reporter/blob/master/docs/frameworks.md#Jest) ⭐ 151 | 🐛 13 | 🌐 JavaScript | 📅 2026-08-23 Allows to analyze Jest autotests, collect test metadata and report them to the testomat.io TCM system.
* [jest-allure](https://github.com/zaqqaz/jest-allure) ⭐ 117 | 🐛 35 | 🌐 TypeScript | 📅 2022-12-07 Add more power to your tests using Jest-Allure with very concise representation of what has been tested in a neat web report form.
* [jest-github-reporter](https://github.com/hipstersmoothie/jest-github-reporter) ⭐ 106 | 🐛 23 | 🌐 TypeScript | 📅 2026-08-26 Report jest test errors directly in pull requests.
* [jest-dashboard](https://github.com/theoutlander/jest-dashboard) ⭐ 77 | 🐛 11 | 🌐 JavaScript | 📅 2023-03-01 Command line dashboard.
* [jest-slow-test-reporter](https://github.com/jodonnell/jest-slow-test-reporter) ⭐ 54 | 🐛 2 | 🌐 JavaScript | 📅 2020-05-30 Prints the slowest tests in your codebase.
* [echoed](https://github.com/mrasu/echoed) ⭐ 37 | 🐛 1 | 🌐 TypeScript | 📅 2025-03-09 Makes tests observable by reporting OpenTelemetry data.
* [jest-standard-reporter](https://github.com/chrisgalvan/jest-standard-reporter) ⭐ 22 | 🐛 19 | 🌐 JavaScript | 📅 2026-08-26 Reporter that uses stdout for messages and stderr for errors.
* [jest-performance-reporter](https://github.com/sholzmayer/jest-performance-reporter) ⭐ 16 | 🐛 1 | 🌐 TypeScript | 📅 2023-02-28 Identify slow tests and create a report including execution times.
* [github-actions-jest-reporter](https://github.com/MatteoH2O1999/github-actions-jest-reporter) ⭐ 15 | 🐛 4 | 🌐 TypeScript | 📅 2026-05-11 Reports jest test results using Github Actions groups, allowing for an easy navigation of the test logs.
* [jest-progress-bar-reporter](https://github.com/pierreroth64/jest-progress-bar-reporter) ⭐ 13 | 🐛 1 | 🌐 JavaScript | 📅 2023-01-07 Simple reporter with a little progressbar.
* [jest-skipped-reporter](https://github.com/rickhanlonii/jest-skipped-reporter) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2020-06-23 Report skipped tests in Jest.
* [jest-simple-dot-reporter](https://github.com/jodonnell/jest-simple-dot-reporter) ⭐ 10 | 🐛 1 | 🌐 JavaScript | 📅 2023-01-06 A simple dot reporter - one dot per each test.
* [testrail-jest-reporter](https://github.com/AntonChaukin/testrail-jest-reporter) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2024-04-09 Report jest test results to TestRail.
* [jest-console-group-reporter](https://github.com/Ashvin-Pal/jest-console-group-reporter) ⭐ 7 | 🐛 1 | 🌐 TypeScript | 📅 2024-02-25 Automatically groups console messages, allows filtering, and provides flexible display configuration options.
* [jest-ado-reporter](https://github.com/bashaus/jest-ado-reporter) ⭐ 3 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-16 Reports jest test suite progress information to the pipeline step in Azure DevOps.
* [jest-slow-test-highlighter](https://github.com/Neizan93/jest-slow-test-highlighter) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-10 Highlights and reports the slowest tests in your suite, helping you identify areas for performance optimization.
* [jest-xunit](https://github.com/sscaff1/jest-xunit) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2018-11-29 An xUnit format reporter for Jest.
* [jest-email-reporter](https://github.com/tglink/jest-email-reporter) ⭐ 2 | 🐛 1 | 🌐 JavaScript | 📅 2019-10-23 Reporter for jest test errors by e-mail.
* [jest-angular-test-verifier](https://github.com/Neizan93/jest-angular-test-verifier) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-09 Ensures that essential Angular files have corresponding test files, reporting any missed opportunities and celebrating when all is well.
* [@tsdoc-test-reporter/jest](https://github.com/tsdoc-test-reporter/reporter) ⭐ 2 | 🐛 4 | 🌐 TypeScript | 📅 2024-09-01 A reporter that attaches JS/TSDoc comments to your test results and generates a summary in HTML or JSON.
* [jest-ci-spec-reporter](https://github.com/robertbradleyux/jest-ci-spec-reporter) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-16 Zero dependency spec reporter with CI-friendly output.
* [jest-wip-reporter](https://github.com/kevinrutherford/jest-wip-reporter) ⭐ 1 | 🐛 5 | 🌐 TypeScript | 📅 2026-06-27 Classifies all tests as either passing, failing, or work-in-progress; also quiet progress reporting with dots by default.
* [jest-tesults-reporter](https://github.com/tesults/jest-tesults-reporter) ⭐ 0 | 🐛 1 | 🌐 JavaScript | 📅 2026-05-03 Submits test results data to Tesults for analysis and reporting.

### Results Processors

* [majestic](https://github.com/Raathigesh/majestic) ⭐ 7,452 | 🐛 50 | 🌐 TypeScript | 📅 2022-05-03 Zero config UI for Jest.

### Environments

* [jest-environment-puppeteer](https://github.com/smooth-code/jest-puppeteer/tree/master/packages/jest-environment-puppeteer) ⭐ 3,544 | 🐛 22 | 🌐 TypeScript | 📅 2026-03-26 Puppeteer environment for Jest.
* [jest-environment-webdriver](https://github.com/alexeyraspopov/jest-webdriver) ⭐ 220 | 🐛 5 | 🌐 JavaScript | 📅 2019-08-13 custom environment for WebDriver integration.
* [jest-doctor](https://github.com/stephan-dum/jest-doctor/tree/main/packages/jest-doctor) ⭐ 11 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-27 Async leak detection and preventions.

### Coverage

* [jest-it-up](https://github.com/rbardini/jest-it-up) ⭐ 65 | 🐛 6 | 🌐 JavaScript | 📅 2025-11-17 Automatically bump up global thresholds whenever coverage goes above them.
* [jest-coverage-thresholds-bumper](https://github.com/Litee/jest-coverage-thresholds-bumper) ⭐ 13 | 🐛 3 | 🌐 TypeScript | 📅 2021-12-24 Similar to `jest-it-up`, but allows to specify where coverage summary is located, supports Jest config in JSON files and `package.json`.
* [jest-a-coverage-slip-detector](https://github.com/GetJobber/jest-a-coverage-slip-detector) ⭐ 9 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-03 Designed for parallelized CI, prevents test coverage from slipping. Features include per-file ratcheting, automatic coverage merging, and custom messages.

### Snapshot

* [StoryShots](https://github.com/storybooks/storybook/tree/master/addons/storyshots/storyshots-core) ⭐ 90,950 | 🐛 1,774 | 🌐 TypeScript | 📅 2026-08-27 StoryShots adds automatic Jest Snapshot Testing for Storybook.
* [@emotion/jest](https://github.com/emotion-js/emotion/tree/main/packages/jest) ⭐ 18,019 | 🐛 392 | 🌐 JavaScript | 📅 2026-08-26 Include Emotion styles in component snapshots.
* [jest-image-snapshot](https://github.com/americanexpress/jest-image-snapshot) ⭐ 3,914 | 🐛 42 | 🌐 JavaScript | 📅 2026-08-05 Take a snapshot test of an image buffer, and catch when the image changes over a threshold. Commonly used for visual regression testing.
* [jest-styled-components](https://github.com/styled-components/jest-styled-components) ⭐ 1,580 | 🐛 5 | 🌐 JavaScript | 📅 2026-06-29 A set of utilities for testing Styled Components with Jest.
* [enzyme-to-json](https://github.com/adriantoine/enzyme-to-json) ⭐ 940 | 🐛 22 | 🌐 JavaScript | 📅 2026-01-27 Convert Enzyme wrappers to a format compatible with Jest snapshot testing.
* [Differencify](https://github.com/NimaSoroush/differencify) ⭐ 638 | 🐛 27 | 🌐 JavaScript | 📅 2020-06-02 Visual regression testing tool using Jest and Puppeteer to do Image snapshot comparison.
* [snapshot-diff](https://github.com/jest-community/snapshot-diff) ⭐ 604 | 🐛 20 | 🌐 JavaScript | 📅 2026-08-26 Takes two values, and return their difference as a string, ready to be snapshotted with `toMatchSnapshot()`. Especially helpful when testing the difference between different React component states.
* [jest-snapshots-svg](https://github.com/jest-community/jest-snapshots-svg) ⭐ 221 | 🐛 18 | 🌐 TypeScript | 📅 2023-11-28 Take a React component tree, and render it into an SVG.
* [1log](https://github.com/ivan7237d/1log) ⚠️ Archived Extensible logger that allows capturing log messages as snapshots.
* [jest-file-snapshot](https://github.com/satya164/jest-file-snapshot) ⭐ 45 | 🐛 3 | 🌐 JavaScript | 📅 2024-07-10 Write snapshots to a separate file instead of the default snapshot file used by Jest.
* [jest-serializer-ansi-escapes](https://github.com/mrazauskas/jest-serializer-ansi-escapes) ⭐ 6 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-24 Snapshot serializer for ANSI escape sequences.
* [jest-large-snapshot-warning](https://github.com/jomaxx/jest-large-snapshot-warning) ⭐ 2 | 🐛 13 | 🌐 JavaScript | 📅 2023-01-04 Add warnings to large snapshots.
* [jest-serializer-xml](https://github.com/keplersj/jest-serializer-xml) ⭐ 2 | 🐛 7 | 🌐 JavaScript | 📅 2024-06-18 Format XML documents to better visualize in Snapshots.
* [jest-img-snapshot](https://github.com/donysukardi/jest-img-snapshot) ⭐ 1 | 🐛 3 | 🌐 JavaScript | 📅 2018-05-07 Image snapshot comparison using pixelmatch with all Jest's snapshot goodies out of the box.
* [jest-serializer-react-helmet](https://github.com/keplersj/jest-serializer-react-helmet) ⭐ 1 | 🐛 11 | 🌐 TypeScript | 📅 2024-06-18 Include React Helmet data in component snapshots.
* [jest-serializer-json-ld-script](https://github.com/keplersj/jest-serializer-json-ld-script) ⭐ 0 | 🐛 12 | 🌐 TypeScript | 📅 2024-06-18 Serializes JSON+LD elements as JavaScript objects.

### Migration

* [jest-codemods](https://github.com/skovhus/jest-codemods) ⭐ 888 | 🐛 35 | 🌐 TypeScript | 📅 2026-08-27 Makes it easy to migrate from other test runner and frameworks to Jest.
* [@putout/plugin-jest](https://github.com/coderaiser/putout/blob/master/packages/plugin-jest/README.md#putoutplugin-jest-) ⭐ 796 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-27 🐊Putout plugin helps to migrate to latest Jest API.

### Library extensions

* [@fast-check/jest](https://github.com/dubzzz/fast-check/tree/main/packages/jest) ⭐ 5,120 | 🐛 76 | 🌐 TypeScript | 📅 2026-08-27 Bring property based testing (aka fuzzing) into Jest.
* [jest-expect-message](https://github.com/mattphillips/jest-expect-message) ⭐ 370 | 🐛 12 | 🌐 JavaScript | 📅 2024-07-17 Add custom message to Jest expects.
* [wait-for-expect](https://github.com/TheBrainFamily/wait-for-expect) ⭐ 299 | 🐛 10 | 🌐 TypeScript | 📅 2025-08-01 A await/async function to wait a expect. Useful on e2e test.
* [jest-chain](https://github.com/mattphillips/jest-chain) ⭐ 273 | 🐛 3 | 🌐 JavaScript | 📅 2023-01-09 Chain Jest matchers together to create one powerful assertion.
* [@testdeck/jest](https://github.com/testdeck/testdeck) ⭐ 235 | 🐛 7 | 🌐 TypeScript | 📅 2025-01-22 Decorator based wrapper around Jest for object oriented testing. Checkout the [documentation](https://testdeck.org) and a working [seed](https://github.com/testdeck/testdeck-jest-seed) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2020-11-19 for you to start with.
* [jest-fail-on-console](https://github.com/ValentinH/jest-fail-on-console) ⭐ 157 | 🐛 2 | 🌐 JavaScript | 📅 2025-12-16 Utility to fail a test when `console.error()` (or any other method of the console) gets called.
* [typescript-snapshots-plugin](https://github.com/asvetliakov/typescript-snapshots-plugin) ⭐ 129 | 🐛 21 | 🌐 TypeScript | 📅 2024-05-30 Extends the TypeScript dev server to support hovering and jumping to a snapshot.
* [babel-jest-assertions](https://github.com/mattphillips/babel-jest-assertions) ⭐ 94 | 🐛 21 | 🌐 JavaScript | 📅 2023-01-11 Babel plugin that automatically adds the number of assertions found in each test with `expect.assertions(n)` and `expect.hasAssertions()`.
* [jest-puppe-shots](https://github.com/macku/jest-puppe-shots) ⭐ 84 | 🐛 2 | 🌐 JavaScript | 📅 2020-01-05 A Jest plugin for creating screenshots of [React](https://reactjs.org) components with a little help of [Puppeteer](https://github.com/puppeteer/puppeteer) ⭐ 95,512 | 🐛 264 | 🌐 TypeScript | 📅 2026-08-26.
* [testdouble-jest](https://github.com/testdouble/testdouble-jest) ⭐ 37 | 🐛 3 | 🌐 JavaScript | 📅 2021-06-02 Support for [testdouble.js](https://github.com/testdouble/testdouble.js) ⭐ 1,428 | 🐛 35 | 🌐 JavaScript | 📅 2024-03-21 for users of Jest.
* [jest-plugin-must-assert](https://github.com/ballercat/jest-plugin-must-assert) ⭐ 26 | 🐛 4 | 🌐 JavaScript | 📅 2023-03-04 A Jest plugin for strict runtime checks. Fails any tests without assertions and prevents async tasks (Promises & timeouts) from leaking across tests.
* [jest-os-detection](https://github.com/doctolib/jest-os-detection) ⭐ 14 | 🐛 30 | 🌐 TypeScript | 📅 2025-02-10 Dynamically enable or skip tests based on the OS they run on so you can share the same test suite across various platforms.
* [@bigtest/interactor](https://frontside.com/bigtest/interactors) A testing and assertion library that makes it easy to test UIs at scale while keeping accessibility at the core.

### Mocks

* [jest-mock-extended](https://github.com/marchaos/jest-mock-extended) ⭐ 906 | 🐛 35 | 🌐 TypeScript | 📅 2026-04-20 Create Typesafe mocks for TS interfaces and objects as well as returning argument specific return values.
* [jest-fetch-mock](https://github.com/jefflau/jest-fetch-mock) ⭐ 893 | 🐛 5 | 🌐 JavaScript | 📅 2026-08-11 Easily mock out `fetch` and set up responses, powered by [Jest mock functions](https://facebook.github.io/jest/docs/en/mock-functions.html).
* [Suites](https://github.com/suites-dev/suites) ⭐ 546 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-26 Unit-testing framework for TypeScript backends with inversion of control and dependency injection that automatically generates type-safe mocks.
* [jest-localstorage-mock](https://github.com/clarkbw/jest-localstorage-mock) ⭐ 319 | 🐛 8 | 🌐 JavaScript | 📅 2024-09-27 A module to mock window\.localStorage and window\.sessionStorage in Jest.
* [jest-canvas-mock](https://github.com/hustcc/jest-canvas-mock) ⭐ 312 | 🐛 20 | 🌐 JavaScript | 📅 2026-07-09 Mock canvas when run unit test cases with jest.
* [jest-date-mock](https://github.com/hustcc/jest-date-mock) ⭐ 267 | 🐛 1 | 🌐 JavaScript | 📅 2024-04-21 Mock `window.Date` when run unit test cases with jest. Make tests of Date easier.
* [jest-location-mock](https://github.com/evelynhathaway/jest-location-mock) ⭐ 63 | 🐛 4 | 🌐 TypeScript | 📅 2026-06-17 Mock `window.location` easily.
* [@jest-mock/express](https://github.com/bikk-uk/jest-mock-express) ⭐ 52 | 🐛 10 | 🌐 TypeScript | 📅 2026-02-17 Mock Express.js request and response objects.
* [jest-wake-lock-mock](https://github.com/jorisre/jest-wake-lock-mock) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2020-12-01 Mock Screen Wake Lock API `navigator.wakeLock` with ease and run your tests using Jest.

### Watch plugins

* [jest-watch-typeahead](https://github.com/jest-community/jest-watch-typeahead) ⭐ 412 | 🐛 22 | 🌐 TypeScript | 📅 2026-08-26 Filter your tests by file name or test name.
* [node-recorder](https://github.com/ericclemmons/node-recorder/#using-jest) ⭐ 97 | 🐛 34 | 🌐 TypeScript | 📅 2023-01-07 Toggle recording modes for `node-recorder`.
* [jest-watch-select-projects](https://github.com/rogeliog/jest-watch-select-projects) ⭐ 67 | 🐛 1 | 🌐 JavaScript | 📅 2024-11-20 Select which Jest projects to run.
* [jest-watch-master](https://github.com/rickhanlonii/jest-watch-master) ⭐ 45 | 🐛 3 | 🌐 JavaScript | 📅 2021-10-16 Check changes since master.
* [jest-watch-directories](https://github.com/cameronhunter/jest-watch-directories/tree/master/packages/jest-watch-directories) ⭐ 26 | 🐛 0 | 🌐 JavaScript | 📅 2018-10-21 Select directories to test.
* [jest-watch-lerna-packages](https://github.com/cameronhunter/jest-watch-directories/blob/master/packages/jest-watch-lerna-packages) ⭐ 26 | 🐛 0 | 🌐 JavaScript | 📅 2018-10-21 Select Lerna packages to test.
* [jest-watch-yarn-workspaces](https://github.com/cameronhunter/jest-watch-directories/tree/master/packages/jest-watch-yarn-workspaces) ⭐ 26 | 🐛 0 | 🌐 JavaScript | 📅 2018-10-21 Select Yarn workspaces to test.
* [jest-watch-suspend](https://github.com/unional/jest-watch-suspend) ⭐ 16 | 🐛 10 | 🌐 TypeScript | 📅 2026-05-19 Suspend watch mode so that your changes would not trigger test runs.
* [jest-watch-toggle-config](https://github.com/jest-community/jest-watch-toggle-config) ⭐ 12 | 🐛 2 | 🌐 JavaScript | 📅 2024-06-16 Toggle boolean settings (e.g. verbosity, test coverage).
* [jest-watch-exec](https://github.com/unional/jest-watch-exec) ⭐ 7 | 🐛 14 | 🌐 TypeScript | 📅 2023-12-15 Execute scripts during the watch cycle.
* [jest-watch-repeat](https://github.com/unional/jest-watch-repeat) ⭐ 5 | 🐛 24 | 🌐 TypeScript | 📅 2026-08-26 Repeat test runs multiple times.
* [jest-watch-random](https://github.com/unional/jest-watch-random) ⭐ 4 | 🐛 28 | 🌐 TypeScript | 📅 2026-05-19 Randomly run some of the test suites.
* [jest-watch-continue](https://github.com/unional/jest-watch-continue) ⭐ 2 | 🐛 20 | 🌐 TypeScript | 📅 2026-05-19 Run test in continue mode.

### Processor

* [ts-jest](https://github.com/kulshekhar/ts-jest) ⭐ 7,075 | 🐛 85 | 🌐 TypeScript | 📅 2026-08-27 TypeScript preprocessor with sourcemap support.
* [vue-jest](https://github.com/vuejs/vue-jest) ⭐ 752 | 🐛 138 | 🌐 JavaScript | 📅 2024-01-29 Vue transformer with source map support.
* [jest-raw-loader](https://github.com/keplersj/jest-raw-loader) ⭐ 34 | 🐛 11 | 🌐 JavaScript | 📅 2026-08-27 Processor mimicking `webpack`'s `raw-loader`.
* [jest-less-loader](https://github.com/hustcc/jest-less-loader) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2023-01-09 Jest transformer for `.less` file.
* [jest-nunjucks](https://github.com/denar90/jest-nunjucks) ⭐ 3 | 🐛 1 | 🌐 JavaScript | 📅 2018-11-15 Processor that compiles nunjucks templates.
* [marko-jest](https://github.com/abiyasa/marko-jest) ⭐ 3 | 🐛 8 | 🌐 JavaScript | 📅 2020-05-15 Processor for [Marko component](https://markojs.com).
* [jest-url-loader](https://github.com/hustcc/jest-url-loader) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2021-09-06 Similar with webpack's `url-loader` for Jest transformer.
* [awesome-pug-jest](https://github.com/iketari/awesome-pug-jest) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2019-01-03 Processor for [Pug/Jade](https://pugjs.org).

### Presets

* [jest-puppeteer](https://github.com/smooth-code/jest-puppeteer) ⭐ 3,544 | 🐛 22 | 🌐 TypeScript | 📅 2026-03-26 A Jest preset that enables a ready-to-use environment to write integration tests using Puppeteer.
* [jest-preset-angular](https://github.com/thymikee/jest-preset-angular) ⭐ 920 | 🐛 30 | 🌐 TypeScript | 📅 2026-08-27 Jest preset for [Angular](https://angular.io) projects.
* [jest-mongodb](https://github.com/shelfio/jest-mongodb) ⭐ 602 | 🐛 36 | 🌐 TypeScript | 📅 2026-08-22 Jest preset for working with MongoDB.
* [jest-dynamodb](https://github.com/shelfio/jest-dynamodb) ⭐ 198 | 🐛 37 | 🌐 TypeScript | 📅 2026-08-24 Jest preset for working with DynamoDB.
* [jest-search](https://github.com/geek-fun/jest-search) ⭐ 17 | 🐛 4 | 🌐 TypeScript | 📅 2026-02-27 Jest preset for working with customisable version of OpenSearch, ElasticSearch and ZincSearch.
* [jest-elasticsearch](https://github.com/shelfio/jest-elasticsearch) ⭐ 9 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-22 Jest preset for working with ElasticSearch.
* [jest-preset-gatsby](https://github.com/keplersj/jest-preset-gatsby) ⭐ 9 | 🐛 12 | 🌐 JavaScript | 📅 2024-08-21 Jest preset to streamline unit testing a Gatsby project.

### Generators

* [jest-test-gen](https://github.com/egm0121/jest-test-gen) ⭐ 187 | 🐛 7 | 🌐 TypeScript | 📅 2023-02-05 CLI tool to generate a test file with test scaffold for every class method or function exported.
* [text2jest](https://www.text2jest.com/) A web-based tool to instantly convert a nested list of plain text test names into a Jest file.

### Debug

* [jest-preview](https://github.com/nvh95/jest-preview) ⭐ 2,393 | 🐛 50 | 🌐 TypeScript | 📅 2026-04-25 Preview Jest tests in a browser.

## Resources

* [Jest cheat sheet](https://github.com/sapegin/jest-cheat-sheet) ⭐ 5,421 | 🐛 0 | 📅 2024-10-30.
* [React Jest workshop](https://github.com/kentcdodds/react-jest-workshop) ⭐ 198 | 🐛 3 | 🌐 JavaScript | 📅 2021-01-25.
* [Jest: How Do I Mock X](https://github.com/magicmark/jest-how-do-i-mock-x) ⭐ 104 | 🐛 1 | 🌐 JavaScript | 📅 2025-08-22.

## Contribute

Contributions welcome! Read the [contribution guidelines](/CONTRIBUTING.md).

## License

[MIT](/LICENSE)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-27._
