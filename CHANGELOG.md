# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](Https://conventionalcommits.org) for commit guidelines.

<!-- changelog -->

## [v0.2.17](https://github.com/ash-project/spark/compare/v0.2.16...v0.2.17) (2022-12-02)




### Improvements:

* more anonymous function type support

## [v0.2.16](https://github.com/ash-project/spark/compare/v0.2.15...v0.2.16) (2022-12-02)




### Improvements:

* support partial captures in functions

* leave unordered code where it is when sorting DSL sections

## [v0.2.15](https://github.com/ash-project/spark/compare/v0.2.14...v0.2.15) (2022-12-01)




### Bug Fixes:

* properly avoid unquoting functions out of context

## [v0.2.14](https://github.com/ash-project/spark/compare/v0.2.13...v0.2.14) (2022-12-01)




### Improvements:

* various DSL utilities, like `fetch_opt` and `sparks/2`

## [v0.2.13](https://github.com/ash-project/spark/compare/v0.2.12...v0.2.13) (2022-11-30)




### Improvements:

* support `remove_parens?` option for `Spark.Formatter`

* Typespecs: add a `t` type for `Spark.Dsl.Extension`. (#12)

## [v0.2.12](https://github.com/ash-project/spark/compare/v0.2.11...v0.2.12) (2022-11-21)




### Bug Fixes:

* Incorrect typespecs. (#11)

## [v0.2.11](https://github.com/ash-project/spark/compare/v0.2.10...v0.2.11) (2022-11-19)




### Bug Fixes:

* properly handle `{:or, [{:spark_function_behaviour, ...}]}` types

* support anonymous functions in an `or` type

* don't cause unnecessary export dependency recompilation

### Improvements:

* Add typespecs for `Spark.Dsl.Entity` and `Spark.Dsl.Section`. (#10)

## [v0.2.10](https://github.com/ash-project/spark/compare/v0.2.9...v0.2.10) (2022-11-15)




### Bug Fixes:

* add basename to guide typespec

## [v0.2.9](https://github.com/ash-project/spark/compare/v0.2.8...v0.2.9) (2022-11-15)




### Improvements:

* support explicitly ordering guides

## [v0.2.8](https://github.com/ash-project/spark/compare/v0.2.7...v0.2.8) (2022-11-03)




### Bug Fixes:

* properly link to libraries, and support `default_guide`

## [v0.2.7](https://github.com/ash-project/spark/compare/v0.2.6...v0.2.7) (2022-11-03)




### Improvements:

* support generic docs replacements renderer

## [v0.2.6](https://github.com/ash-project/spark/compare/v0.2.5...v0.2.6) (2022-10-31)




### Bug Fixes:

* add new `spark_function_behaviour` to elixir_sense plugin

### Improvements:

* support `{:or, ...}` option types

## [v0.2.5](https://github.com/ash-project/spark/compare/v0.2.4...v0.2.5) (2022-10-30)




### Bug Fixes:

* un-break recursive DSL entities

## [v0.2.4](https://github.com/ash-project/spark/compare/v0.2.3...v0.2.4) (2022-10-29)




### Improvements:

* support anonymous functions in the DSL

* remove necessity for `{:elixir_sense, ...}` to make the plugin work

## [v0.2.3](https://github.com/ash-project/spark/compare/v0.2.2...v0.2.3) (2022-10-28)




### Improvements:

* add `Builder.input()` type

## [v0.2.2](https://github.com/ash-project/spark/compare/v0.2.1...v0.2.2) (2022-10-28)




### Improvements:

* add `handle_nested_builders/2`

## [v0.2.1](https://github.com/ash-project/spark/compare/v0.2.0...v0.2.1) (2022-10-27)




### Bug Fixes:

* handle non tuple return in builder

## [v0.2.0](https://github.com/ash-project/spark/compare/v0.1.29...v0.2.0) (2022-10-24)




### Features:

* add `Spark.Dsl.Builder`

## [v0.1.29](https://github.com/ash-project/spark/compare/v0.1.28...v0.1.29) (2022-10-21)




### Improvements:

* add `{:struct, Struct}` option type

* DslError: Add type for `DslError` struct. (#4)

## [v0.1.28](https://github.com/ash-project/spark/compare/v0.1.27...v0.1.28) (2022-10-08)




### Bug Fixes:

* resolve issue w/ Code.eval_quoted

### Improvements:

* OptionsHelpers: Add typespecs for options helpers. (#3)

## [v0.1.27](https://github.com/ash-project/spark/compare/v0.1.26...v0.1.27) (2022-10-04)




### Bug Fixes:

* go back to fully hiding `no_require` modules

## [v0.1.26](https://github.com/ash-project/spark/compare/v0.1.25...v0.1.26) (2022-09-29)




### Improvements:

* add `mix_tasks/0` to `DocIndex`

## [v0.1.25](https://github.com/ash-project/spark/compare/v0.1.24...v0.1.25) (2022-09-20)




### Improvements:

* add `t()` type for DSL

## [v0.1.24](https://github.com/ash-project/spark/compare/v0.1.23...v0.1.24) (2022-09-20)




### Improvements:

* properly induce export dependency and still use aliases

## [v0.1.23](https://github.com/ash-project/spark/compare/v0.1.22...v0.1.23) (2022-09-20)




### Improvements:

* no dependencies hacked into export dependencies

## [v0.1.22](https://github.com/ash-project/spark/compare/v0.1.21...v0.1.22) (2022-09-20)




## [v0.1.21](https://github.com/ash-project/spark/compare/v0.1.20...v0.1.21) (2022-09-15)




### Bug Fixes:

* put back in fetching from module attribute if possible

## [v0.1.20](https://github.com/ash-project/spark/compare/v0.1.19...v0.1.20) (2022-09-15)




### Improvements:

* preliminary support for passing maps to introspection

* allow extensions to modify the module docs of an extension

## [v0.1.19](https://github.com/ash-project/spark/compare/v0.1.18...v0.1.19) (2022-08-31)




### Bug Fixes:

* revert ordering changes that appear to be causing errors

## [v0.1.18](https://github.com/ash-project/spark/compare/v0.1.17...v0.1.18) (2022-08-25)




### Bug Fixes:

* fix base resource pattern

* using type config in more places

* use configured type

### Improvements:

* add otp_app getter

## [v0.1.17](https://github.com/ash-project/spark/compare/v0.1.16...v0.1.17) (2022-08-23)




### Bug Fixes:

* don't create module docs for generated modules

## [v0.1.16](https://github.com/ash-project/spark/compare/v0.1.15...v0.1.16) (2022-08-23)




### Improvements:

* remove `default_guide/1`

## [v0.1.15](https://github.com/ash-project/spark/compare/v0.1.14...v0.1.15) (2022-08-19)




### Improvements:

* work on doc index

## [v0.1.14](https://github.com/ash-project/spark/compare/v0.1.13...v0.1.14) (2022-08-19)




### Improvements:

* add docs to hex package

## [v0.1.13](https://github.com/ash-project/spark/compare/v0.1.12...v0.1.13) (2022-08-19)




### Improvements:

* try out adding extra package metadata

## [v0.1.12](https://github.com/ash-project/spark/compare/v0.1.11...v0.1.12) (2022-08-18)




### Improvements:

* add default to get_option

* fix package files

## [v0.1.11](https://github.com/ash-project/spark/compare/v0.1.10...v0.1.11) (2022-08-18)




### Improvements:

* more documentation, tools for hex docs

## [v0.1.10](https://github.com/ash-project/spark/compare/v0.1.9...v0.1.10) (2022-08-18)




### Improvements:

* WIP on fixing the way we distribute doc files

## [v0.1.9](https://github.com/ash-project/spark/compare/v0.1.8...v0.1.9) (2022-08-17)




### Bug Fixes:

* properly ignore built in alias types

### Improvements:

* use libgraph to sort transformers

## [v0.1.8](https://github.com/ash-project/spark/compare/v0.1.7...v0.1.8) (2022-08-16)




### Improvements:

* don't provide the module to transformers

* update sourceror depednency

## [v0.1.7](https://github.com/ash-project/spark/compare/v0.1.6...v0.1.7) (2022-08-15)




### Improvements:

* add `spark.formatter.exs` (from ash)

## [v0.1.6](https://github.com/ash-project/spark/compare/v0.1.5...v0.1.6) (2022-08-14)




### Improvements:

* add formatter

## [v0.1.5](https://github.com/ash-project/spark/compare/v0.1.4...v0.1.5) (2022-08-14)




### Bug Fixes:

* properly use spark dsl error

## [v0.1.4](https://github.com/ash-project/spark/compare/v0.1.3...v0.1.4) (2022-08-14)




### Bug Fixes:

* add `Spark.Error.DslError`

## [v0.1.3](https://github.com/ash-project/spark/compare/v0.1.2...v0.1.3) (2022-08-14)




### Bug Fixes:

* properly handle `spark` types

## [v0.1.2](https://github.com/ash-project/spark/compare/v0.1.1...v0.1.2) (2022-08-14)




### Bug Fixes:

* validate spark types properly

## [v0.1.1](https://github.com/ash-project/spark/compare/v0.1.1...v0.1.1) (2022-08-14)



