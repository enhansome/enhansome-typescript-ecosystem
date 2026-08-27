# Awesome TypeScript Ecosystem with stars

> 😎 A list of awesome TypeScript transformers, plugins, handbooks, etc

> As always,
> use caution when trying out TypeScript transformers & plugins,
> especially those marked as 🔧 *experimental* or 🔧🚧 *under construction*.

## Handbooks

* [TypeScript wiki](https://github.com/Microsoft/TypeScript/wiki) ⭐ 110,735 | 🐛 5,190 | 🌐 Go | 📅 2026-08-27 - The official wiki for TypeScript lang
* [typescript-book](https://github.com/basarat/typescript-book/) ⭐ 21,552 | 🐛 150 | 🌐 TypeScript | 📅 2024-06-29 - 📚 The definitive guide to TypeScript and possibly the best TypeScript book 📖
* [TypeScript-Handbook](https://github.com/microsoft/TypeScript-Handbook) ⚠️ Archived - The TypeScript Handbook is a comprehensive guide to the TypeScript language
* [ts-transformer-handbook](https://github.com/madou/ts-transformer-handbook) ⭐ 1,019 | 🐛 16 | 🌐 TypeScript | 📅 2025-02-14 - 📘 A handbook on how to create transformers for Typescript with real code examples

## Transformers

Transformers are synonymous with Babel Plugins.
They enable transforming code from one to to another,
generally used for improving the developer experience,
doing performance optimizations,
and more.

### General transformers

* [typescript-is](https://github.com/woutervh-/typescript-is#readme) ⭐ 959 | 🐛 48 | 🌐 TypeScript | 📅 2023-07-17 - generate run-time type-checks
* [ts-nameof](https://github.com/dsherret/ts-nameof) ⭐ 504 | 🐛 33 | 🌐 TypeScript | 📅 2023-03-23 - nameof in TypeScript
* [@ts-tools/robotrix](https://github.com/AviVahl/ts-tools/tree/master/packages/robotrix) ⭐ 170 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-27 - Useful TypeScript transpilation transformers.
* [ts-transform-graphql-tag](https://github.com/firede/ts-transform-graphql-tag) ⭐ 155 | 🐛 17 | 🌐 TypeScript | 📅 2023-01-03 - Compiles GraphQL tagged template strings using graphql-tag in TypeScript files
* [ts-transform-import-path-rewrite](https://github.com/dropbox/ts-transform-import-path-rewrite) ⭐ 130 | 🐛 12 | 🌐 TypeScript | 📅 2023-08-07 - TS AST transformer to rewrite import path
* [ts-transform-css-modules](https://github.com/longlho/ts-transform-css-modules) ⭐ 86 | 🐛 25 | 🌐 TypeScript | 📅 2023-01-16 - Extract css class names from required css module files for TypeScript
* [ts-transform-json-schema](https://github.com/marionebl/ts-transform-json-schema) ⭐ 29 | 🐛 13 | 🌐 TypeScript | 📅 2023-01-04 - Generate inline JSON schema from TypeScript types
* [ts-transform-img](https://github.com/longlho/ts-transform-img) ⭐ 24 | 🐛 30 | 🌐 TypeScript | 📅 2023-01-16 - Allow `import * as img from 'foo.png'` in TS
* [ts-transform-json](https://github.com/longlho/ts-transform-json) ⭐ 15 | 🐛 21 | 🌐 TypeScript | 📅 2023-03-06 - Inline specific values from a JSON file or the whole JSON blob
* [ts-transform-define](https://github.com/compiled/ts-transform-define) ⭐ 8 | 🐛 11 | 🌐 TypeScript | 📅 2023-01-06 - Allows you to create global constants which can be configured at compile time.
* [ts-trim-declarations](https://github.com/cprecioso/ts-trim-declarations) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2020-11-05 - Remove declarations marked with `/** @internal */` from your exported files.

### Module resolution

* [ts-import-plugin](https://github.com/Brooooooklyn/ts-import-plugin) ⭐ 603 | 🐛 25 | 🌐 TypeScript | 📅 2026-08-26 - Modular import plugin for TypeScript
* [ts-transformer-imports](https://www.npmjs.com/package/ts-transformer-imports) - A TypeScript transformer which enables compilation of absolute imports (using baseUrl or paths) so they can be required as modules from Javascript or TypeScript, without additional configuration or path mapping

### React

* [typescript-plugin-styled-components](https://github.com/Igorbek/typescript-plugin-styled-components) ⭐ 418 | 🐛 33 | 🌐 TypeScript | 📅 2023-06-06 - TypeScript transformer for improving the debugging experience of styled-components
* [emotion-ts-plugin](https://github.com/LeetCode-OpenSource/emotion-ts-plugin) ⭐ 57 | 🐛 22 | 🌐 TypeScript | 📅 2023-04-07 - TypeScript transformer for improving the debugging experience and abilities of emotion
* [ts-transform-react-constant-elements](https://github.com/dropbox/ts-transform-react-constant-elements) ⭐ 44 | 🐛 11 | 🌐 TypeScript | 📅 2023-08-29 - A TypeScript AST Transformer that can speed up reconciliation and reduce garbage collection pressure by hoisting React elements to the highest possible scope
* [react-hot-ts](https://github.com/elsassph/react-hot-ts) ⭐ 27 | 🐛 18 | 🌐 TypeScript | 📅 2023-01-07 - A lightweight, TypeScript-native, Babel-free, plugin-free, implementation of react-hot-loader
* [ts-transform-react-jsx-source](https://github.com/dropbox/ts-transform-react-jsx-source) ⭐ 11 | 🐛 18 | 🌐 TypeScript | 📅 2023-07-25 - TypeScript AST Transformer that adds source file and line number to JSX elements
* [ts-transform-hoist-objects-in-props](https://github.com/avensia-oss/ts-transform-hoist-objects-in-props) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2025-12-09 - A TypeScript custom transformer that hoists object literals and functions that are passed to JSX props.
* [ts-transform-import-to-lazy-async-import](https://github.com/avensia-oss/ts-transform-import-to-lazy-async-import) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2019-04-17 - A TypeScript custom transformer that turns your synchronously imported components into lazy loaded through React.lazy() (or a factory of your choosing) 🔧
* [ts-transform-instrument-react-components](https://github.com/avensia-oss/ts-transform-instrument-react-components) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2019-04-17 - A TypeScript custom transformer that instruments React components to report which components exists in your bundle and which gets rendered 🔧

### i18n

* [@formatjs/ts-transformer](https://www.npmjs.com/package/@formatjs/ts-transformer) - Extracts string messages for translation from modules that use React Intl (similar to babel-plugin-react-intl)

### Types

* [ts-transformer-keys](https://www.npmjs.com/package/ts-transformer-keys) - A TypeScript custom transformer which enables to obtain keys of given type

### Testing

* [jest-ts-auto-mock](https://github.com/Typescript-TDD/jest-ts-auto-mock) ⭐ 169 | 🐛 13 | 🌐 TypeScript | 📅 2024-09-09 - Jest test utility with automatic mock creation for interfaces and classes
* [ts-transformer-testing-library](https://github.com/marionebl/ts-transformer-testing-library) ⭐ 17 | 🐛 14 | 🌐 TypeScript | 📅 2023-01-05 - Make testing custom TypeScript transformers a breeze
* [ts-auto-mock](https://www.npmjs.com/package/ts-auto-mock) - A TypeScript transformer that will allow you to create mock for any types (Interfaces, Classes, ...) without need to create manual fakes/mocks.

### Optimization

* [ts-transform-inferno](https://github.com/deamme/ts-transform-inferno) ⭐ 53 | 🐛 7 | 🌐 TypeScript | 📅 2022-03-04 - TypeScript transformer for InfernoJS
* [ts-transform-async-import](https://github.com/avensia-oss/ts-transform-async-import) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2018-12-30 - A TypeScript custom transformer that turns synchronous imports of async functions into asynchronous imports 🔧
* [ts-transform-export-const-folding](https://github.com/avensia-oss/ts-transform-export-const-folding) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2018-12-30 - This is a TypeScript custom transform that removes imported constants by inlining them.

## Language service plugins

Language service plugins enable rich developer experience warnings, errors, and even intellisense in your IDE.
Read [how to write your own langauge service plugin here](https://github.com/Microsoft/TypeScript/wiki/Writing-a-Language-Service-Plugin) ⭐ 110,735 | 🐛 5,190 | 🌐 Go | 📅 2026-08-27.

* [typescript-styled-plugin](https://github.com/Microsoft/typescript-styled-plugin) ⚠️ Archived - TypeScript server plugin that adds intellisense to styled component css strings
* [ts-graphql-plugin](https://github.com/Quramy/ts-graphql-plugin) ⭐ 757 | 🐛 30 | 🌐 TypeScript | 📅 2026-08-25 - TypeScript Language Service Plugin for GraphQL developers
* [ts-mysql-plugin](https://github.com/segmentio/ts-mysql-plugin) ⭐ 319 | 🐛 18 | 🌐 TypeScript | 📅 2026-06-25 - A TypeScript Language Service Plugin that gives superpowers to SQL tagged template literals.
* [ts-sql-plugin](https://github.com/xialvjun/ts-sql-plugin) ⭐ 192 | 🐛 7 | 🌐 TypeScript | 📅 2026-07-06 -  TypeScript Language Service Plugin for SQL with a tagged template strings SQL builder
* [tslint-language-service](https://github.com/angelozerr/tslint-language-service/) ⭐ 190 | 🐛 25 | 🌐 TypeScript | 📅 2019-11-06 - TypeScript 2.2.1 plugin for tslint
* [ts-migrating](https://github.com/ycmjason/ts-migrating/) ⭐ 69 | 🐛 1 | 🌐 TypeScript | 📅 2026-06-24 - an TypeScript LSP plugin that lets you migrate TSconfig

## Tools

* [ts-morph](https://github.com/dsherret/ts-morph) ⭐ 6,165 | 🐛 292 | 🌐 TypeScript | 📅 2026-08-26 -  TypeScript Compiler API wrapper for static analysis and programmatic code changes
* [fallow](https://github.com/fallow-rs/fallow) ⭐ 4,416 | 🐛 14 | 🌐 Rust | 📅 2026-08-27 - Finds dead code, duplication, circular dependencies, and complexity hotspots in TypeScript codebases
* [typescript-json-schema](https://github.com/YousefED/typescript-json-schema) ⭐ 3,267 | 🐛 189 | 🌐 TypeScript | 📅 2026-07-14 - Generate json-schema from your TypeScript sources
* [ts-json-schema-generator](https://github.com/vega/ts-json-schema-generator) ⭐ 1,714 | 🐛 130 | 🌐 TypeScript | 📅 2026-08-09 - Generate JSON schema from your TypeScript sources
* [ttypescript](https://github.com/cevek/ttypescript) ⭐ 1,534 | 🐛 23 | 🌐 TypeScript | 📅 2023-06-23 - Over TypeScript tool to use custom transformers in the tsconfig.json
* [ts-query](https://github.com/phenomnomnominal/tsquery) ⭐ 1,053 | 🐛 12 | 🌐 TypeScript | 📅 2026-04-06 - TypeScript AST query library
* [ts-creator](https://github.com/HearTao/ts-creator) ⭐ 391 | 🐛 22 | 🌐 TypeScript | 📅 2023-03-06 - A code generator to generate TypeScript code generator from TypeScript code
* [jsontosdk](https://github.com/SolvoHQ/jsontosdk) ⭐ 0 | 🐛 0 | 🌐 Astro | 📅 2026-05-14 - Paste a JSON sample and generate typed TypeScript interfaces, a Zod schema, and a fetch helper

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-27._
