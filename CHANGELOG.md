# neverthrow

## 7.1.0

### Minor Changes

- [#467](https://github.com/supermacro/neverthrow/pull/467) [`4b9d2fd`](https://github.com/supermacro/neverthrow/commit/4b9d2fdaf03223945068509f948b57194732aa03) Thanks [@untidy-hair
](https://github.com/untidy-hair)! - feat: add `andTee` and `andThrough` to handle side-effect

### Patch Changes

- [#483](https://github.com/supermacro/neverthrow/pull/483) [`96f7f66`](https://github.com/supermacro/neverthrow/commit/96f7f669ac83be705a389d47ed804e9d44a13932) Thanks [@braxtonhall](https://github.com/braxtonhall)! - Fix `combineWithAllErrors` types

- [#563](https://github.com/supermacro/neverthrow/pull/563) [`eadf50c`](https://github.com/supermacro/neverthrow/commit/eadf50c695db896b8841c0ee301ae5eeba994b90) Thanks [@mattpocock](https://github.com/mattpocock)! - Made err() infer strings narrowly for easier error tagging.

## 7.0.1

### Patch Changes

- [#527](https://github.com/supermacro/neverthrow/pull/527) [`2e1f198`](https://github.com/supermacro/neverthrow/commit/2e1f19899800ce5e1164412c6a693cf2f1c40b20) Thanks [@3846masa](https://github.com/3846masa)! - fix: change type definitions to make inferring types of safeTry more strict

- [#497](https://github.com/supermacro/neverthrow/pull/497) [`e06203e`](https://github.com/supermacro/neverthrow/commit/e06203e90b2b64edaa42707cbca8383c9f4765e8) Thanks [@braxtonhall](https://github.com/braxtonhall)! - enhance type inferrence of `match`

## 7.0.0

### Major Changes

- [#553](https://github.com/supermacro/neverthrow/pull/553) [`5a3af0a`](https://github.com/supermacro/neverthrow/commit/5a3af0a55d0c440dfd50bfbbe021c6e4b973184b) Thanks [@m-shaka](https://github.com/m-shaka)! - Declare the minimum supported Node.js version

  `Neverthrow` does not depend on any Node.js version-specific features, so it should work with any version of Node.js that supports ES6 and other runtimes like Browser, Deno, etc.

  However, for the sake of maintaining a consistent development environment, we should declare the minimum supported version of Node.js in the `engines` field of the `package.json` file.