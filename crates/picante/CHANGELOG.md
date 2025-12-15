# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0](https://github.com/bearcove/picante/compare/picante-v0.1.0...picante-v0.2.0) - 2025-12-15

### Added

- in-flight tracked-query deduplication across snapshots ([#28](https://github.com/bearcove/picante/pull/28))
- reduce DerivedIngredient compile time via type erasure ([#26](https://github.com/bearcove/picante/pull/26))

### Other

- Improve documentation for ingredient implementations
- Add database snapshot support ([#22](https://github.com/bearcove/picante/pull/22))
- :input: support singleton inputs ([#6](https://github.com/bearcove/picante/pull/6)) ([#11](https://github.com/bearcove/picante/pull/11))
- :db: generate combined Db trait ([#7](https://github.com/bearcove/picante/pull/7)) ([#10](https://github.com/bearcove/picante/pull/10))
- implement #[picante::db] ([#4](https://github.com/bearcove/picante/pull/4))
- pointer-identity fast path for Arc/Rc/Box ([#3](https://github.com/bearcove/picante/pull/3))
- Add picante proc-macros + docs site refresh ([#2](https://github.com/bearcove/picante/pull/2))
- Avoid no-op input bumps; restore dep graph on load
- Add InternedIngredient
- Fix doctests: add IngredientLookup impl and wrap bare URLs
- Add IngredientLookup impl to test and bench code
- DynIngredient etc.
- Move facet-assert to dev-dependencies
- Add custom facet-dev templates for README generation
- Add README etc.
- Fix doctest syntax in code example
- async runtime, persistence, CI, docs
