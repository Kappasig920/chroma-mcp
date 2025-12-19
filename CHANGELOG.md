# Changelog

## 1.0.1 (2025-12-19)

Full Changelog: [v1.0.0...v1.0.1](https://github.com/Kappasig920/chroma-mcp/compare/v1.0.0...v1.0.1)

### Bug Fixes

* **client:** close streams without requiring full consumption ([62f44ad](https://github.com/Kappasig920/chroma-mcp/commit/62f44ad0e810ee5d53a753117fd166e999d5e84c))
* compat with Python 3.14 ([80771bc](https://github.com/Kappasig920/chroma-mcp/commit/80771bc96e81227e6d2b0d144094ca02758daa5e))
* **compat:** update signatures of `model_dump` and `model_dump_json` for Pydantic v1 ([e74337b](https://github.com/Kappasig920/chroma-mcp/commit/e74337b857bf1f5c4a1097a9a22b7eabc2274a7f))
* ensure streams are always closed ([cd46dc7](https://github.com/Kappasig920/chroma-mcp/commit/cd46dc7254bfd28dc977a020843d9f87ccfa8d2c))
* **types:** allow pyright to infer TypedDict types within SequenceNotStr ([10c0057](https://github.com/Kappasig920/chroma-mcp/commit/10c0057dbd036b3e6c46d0ad1b2ab53469ebc52b))
* use async_to_httpx_files in patch method ([39de38d](https://github.com/Kappasig920/chroma-mcp/commit/39de38d14ceca75824a215ae472194e0fef780cb))


### Chores

* add Python 3.14 classifier and testing ([0e85883](https://github.com/Kappasig920/chroma-mcp/commit/0e8588368a7d7dde1e88cd917503918351fc050f))
* **deps:** mypy 1.18.1 has a regression, pin to 1.17 ([7bf832b](https://github.com/Kappasig920/chroma-mcp/commit/7bf832bdb92db14d20a88c6c86b779898e46ed24))
* **docs:** use environment variables for authentication in code snippets ([a41b4bf](https://github.com/Kappasig920/chroma-mcp/commit/a41b4bfee475a0c99b9e90fee02b3e6c6b7c1a1e))
* **internal/tests:** avoid race condition with implicit client cleanup ([39be94d](https://github.com/Kappasig920/chroma-mcp/commit/39be94de291f32eb6a8bf31f2cfa0f7ef1c68f4c))
* **internal:** add `--fix` argument to lint script ([fe64dc8](https://github.com/Kappasig920/chroma-mcp/commit/fe64dc8ecdf84e21054365310fe4224cfcf3e994))
* **internal:** add missing files argument to base client ([fd216f3](https://github.com/Kappasig920/chroma-mcp/commit/fd216f389d7b137e8dcb0f67f63a1a58ea957185))
* **internal:** grammar fix (it's -&gt; its) ([3977ce6](https://github.com/Kappasig920/chroma-mcp/commit/3977ce65cbbb92c1596230e71a7293b8047e3c64))
* **package:** drop Python 3.8 support ([83fbd65](https://github.com/Kappasig920/chroma-mcp/commit/83fbd65e3dfbc2b54781a8dc630163622ee49ff7))
* speedup initial import ([315036a](https://github.com/Kappasig920/chroma-mcp/commit/315036a07cb3d1656c5eb1cd18edbac8529fec0a))
* update lockfile ([1e86251](https://github.com/Kappasig920/chroma-mcp/commit/1e862511b288c890669880f5f6aaa125c9ed0337))

## 1.0.0 (2025-10-22)

Full Changelog: [v0.0.1...v1.0.0](https://github.com/Kappasig920/chroma-mcp/compare/v0.0.1...v1.0.0)

### Features

* add chroma_update_documents tool ([#17](https://github.com/Kappasig920/chroma-mcp/issues/17)) ([8863b47](https://github.com/Kappasig920/chroma-mcp/commit/8863b4757039478986fafbb5d4ff9397134a35cb))


### Chores

* **GitHub Action:** adding container workflow ([#50](https://github.com/Kappasig920/chroma-mcp/issues/50)) ([98ff675](https://github.com/Kappasig920/chroma-mcp/commit/98ff67589bdcc31b730a5415ff9529433f949077))
* sync repo ([cc7a1e2](https://github.com/Kappasig920/chroma-mcp/commit/cc7a1e24c7e20559b967b40f4fdc4fa92a1213a3))
* update SDK settings ([e8a13f2](https://github.com/Kappasig920/chroma-mcp/commit/e8a13f2e2dc9de19815e74644ab9ca8acc936b42))
