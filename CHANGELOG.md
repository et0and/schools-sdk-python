# Changelog

## 0.4.0 (2026-05-13)

Full Changelog: [v0.3.1...v0.4.0](https://github.com/et0and/schools-sdk-python/compare/v0.3.1...v0.4.0)

### Features

* **internal/types:** support eagerly validating pydantic iterators ([46fa22e](https://github.com/et0and/schools-sdk-python/commit/46fa22e72433fd21df94f0beafae9229a493e122))
* **internal:** implement indices array format for query and form serialization ([2046eb2](https://github.com/et0and/schools-sdk-python/commit/2046eb23e27e58102aa46fc3f5db7044a1014a3b))
* support setting headers via env ([0662fcc](https://github.com/et0and/schools-sdk-python/commit/0662fcc384b691d15fa54e1ac7b454a83b4720d5))


### Bug Fixes

* **client:** add missing f-string prefix in file type error message ([f6676fe](https://github.com/et0and/schools-sdk-python/commit/f6676fe9aaa03271fca508b4714f2dc54c7c4367))
* **client:** preserve hardcoded query params when merging with user params ([d9dab79](https://github.com/et0and/schools-sdk-python/commit/d9dab7901213baed2e99a6560703192b76433da4))
* ensure file data are only sent as 1 parameter ([81117a5](https://github.com/et0and/schools-sdk-python/commit/81117a5ea7e9f0eea2ff3d6f1b549df3b3507d07))
* sanitize endpoint path params ([9347f27](https://github.com/et0and/schools-sdk-python/commit/9347f270837a6020287aeff891d33ec6c9e7b9a5))
* use correct field name format for multipart file arrays ([475e50b](https://github.com/et0and/schools-sdk-python/commit/475e50b83de40e1324a5cf10404ee13a3f594d22))


### Performance Improvements

* **client:** optimize file structure copying in multipart requests ([c48dfa9](https://github.com/et0and/schools-sdk-python/commit/c48dfa9d862d6c9264fdc2821f75e1c1457c551f))


### Chores

* **ci:** skip lint on metadata-only changes ([e552d5b](https://github.com/et0and/schools-sdk-python/commit/e552d5b4cb2a79299493d2ee48762ff0b940394e))
* **internal:** more robust bootstrap script ([6d9f384](https://github.com/et0and/schools-sdk-python/commit/6d9f384cd2aac4d84c1f137dbc3d3315923b8657))
* **internal:** reformat pyproject.toml ([2b7e212](https://github.com/et0and/schools-sdk-python/commit/2b7e2128c2aba26454b65cabf4949b7b4d17fc04))
* **internal:** update gitignore ([c5fe8ba](https://github.com/et0and/schools-sdk-python/commit/c5fe8bac5fbf9de9aece4d660b3becdb8d84f0dc))

## 0.3.1 (2026-03-17)

Full Changelog: [v0.3.0...v0.3.1](https://github.com/et0and/schools-sdk-python/compare/v0.3.0...v0.3.1)

### Bug Fixes

* **deps:** bump minimum typing-extensions version ([a5f393c](https://github.com/et0and/schools-sdk-python/commit/a5f393cb44be8b8b92eed92e665dfd2394cdaf1c))
* **pydantic:** do not pass `by_alias` unless set ([2cc6f3b](https://github.com/et0and/schools-sdk-python/commit/2cc6f3b8db044f574bb444e878d4fbc9fa9acb06))


### Chores

* **ci:** skip uploading artifacts on stainless-internal branches ([0cc645f](https://github.com/et0and/schools-sdk-python/commit/0cc645f012791cf08b822682479d5b741a31cf7f))
* **internal:** codegen related update ([16c7bdd](https://github.com/et0and/schools-sdk-python/commit/16c7bddf49d003c22b4859a963c2ac84318c8303))
* **internal:** tweak CI branches ([6c9eb70](https://github.com/et0and/schools-sdk-python/commit/6c9eb70a72a3a2d371965aedf71433ef54132cde))

## 0.3.0 (2026-02-25)

Full Changelog: [v0.2.1...v0.3.0](https://github.com/et0and/schools-sdk-python/compare/v0.2.1...v0.3.0)

### Features

* **client:** add custom JSON encoder for extended type support ([1c95c8c](https://github.com/et0and/schools-sdk-python/commit/1c95c8c48cb2bc7d33adb5e5017fc69332ac332f))


### Chores

* format all `api.md` files ([b912528](https://github.com/et0and/schools-sdk-python/commit/b912528388e13d1a111999157f97a00d5e27ece0))
* **internal:** add request options to SSE classes ([4d7cdd3](https://github.com/et0and/schools-sdk-python/commit/4d7cdd3254474b235479758e40ff26e01356f304))
* **internal:** bump dependencies ([37cfe46](https://github.com/et0and/schools-sdk-python/commit/37cfe46510ba1dd7c02f85720daeb21fb8459dd0))
* **internal:** fix lint error on Python 3.14 ([b0be636](https://github.com/et0and/schools-sdk-python/commit/b0be636fc6d8a35c70b964ad0d481a38da8f7dc0))
* **internal:** make `test_proxy_environment_variables` more resilient ([b195f2b](https://github.com/et0and/schools-sdk-python/commit/b195f2bf95bd67a219bb1ffc2bbfcae40757c48c))
* **internal:** make `test_proxy_environment_variables` more resilient to env ([708b3c7](https://github.com/et0and/schools-sdk-python/commit/708b3c72e405f458e15768584b3abb40b1130119))
* **internal:** remove mock server code ([efea9aa](https://github.com/et0and/schools-sdk-python/commit/efea9aa56e0bc4efa92a486735acabc083a125b7))
* update mock server docs ([b22f202](https://github.com/et0and/schools-sdk-python/commit/b22f202fdd4d86e2eb6c15b29d003dde85978b89))

## 0.2.1 (2026-01-30)

Full Changelog: [v0.2.0...v0.2.1](https://github.com/et0and/schools-sdk-python/compare/v0.2.0...v0.2.1)

### Chores

* configure new SDK language ([3ec2a25](https://github.com/et0and/schools-sdk-python/commit/3ec2a25ab514463373ddb1472e799d5a0afe5fe7))

## 0.2.0 (2026-01-29)

Full Changelog: [v0.1.6...v0.2.0](https://github.com/et0and/schools-sdk-python/compare/v0.1.6...v0.2.0)

### Features

* **client:** add support for binary request streaming ([4b6922e](https://github.com/et0and/schools-sdk-python/commit/4b6922e4ee9e8639f548ab3bf3346ee9effdcd98))


### Bug Fixes

* **client:** loosen auth header validation ([49eb039](https://github.com/et0and/schools-sdk-python/commit/49eb03920d3a4514f8f2184e8512fdec170544de))
* **docs:** fix mcp installation instructions for remote servers ([3fdac9d](https://github.com/et0and/schools-sdk-python/commit/3fdac9d05a1e067763ff50d0fe0f0f9f01abeb39))


### Chores

* **ci:** upgrade `actions/github-script` ([1d74fca](https://github.com/et0and/schools-sdk-python/commit/1d74fca925ab212efe0217b327dd84b26844ffa1))
* **internal:** update `actions/checkout` version ([3f50e80](https://github.com/et0and/schools-sdk-python/commit/3f50e807ee7db300d7e5419cb26cc6b5d3dcdc19))


### Documentation

* prominently feature MCP server setup in root SDK readmes ([2304058](https://github.com/et0and/schools-sdk-python/commit/2304058f312fb8f618f6cec3950b6c27b6339e69))

## 0.1.6 (2025-12-19)

Full Changelog: [v0.1.5...v0.1.6](https://github.com/et0and/schools-sdk-python/compare/v0.1.5...v0.1.6)

### Chores

* **internal:** add `--fix` argument to lint script ([90d1b77](https://github.com/et0and/schools-sdk-python/commit/90d1b7722d9a8bbc54121112a4e083075203819e))

## 0.1.5 (2025-12-18)

Full Changelog: [v0.1.4...v0.1.5](https://github.com/et0and/schools-sdk-python/compare/v0.1.4...v0.1.5)

### Bug Fixes

* **types:** allow pyright to infer TypedDict types within SequenceNotStr ([e1cc8f4](https://github.com/et0and/schools-sdk-python/commit/e1cc8f40ae0428536c274a8d9be5cb302a52c697))
* use async_to_httpx_files in patch method ([b5ca638](https://github.com/et0and/schools-sdk-python/commit/b5ca638f87291a9fa917bf47eb94d86953d677d2))


### Chores

* **internal:** add missing files argument to base client ([142e32c](https://github.com/et0and/schools-sdk-python/commit/142e32cf983b28ecc2e48466e7acd25b59b94e9a))
* speedup initial import ([187b5ab](https://github.com/et0and/schools-sdk-python/commit/187b5ab3637a18f7ec0ad769e1ed76b6eba1fa8f))

## 0.1.4 (2025-12-03)

Full Changelog: [v0.1.3...v0.1.4](https://github.com/et0and/schools-sdk-python/compare/v0.1.3...v0.1.4)

### Bug Fixes

* ensure streams are always closed ([4a636b0](https://github.com/et0and/schools-sdk-python/commit/4a636b04eaf667f6e92a60515379f2af636495d3))


### Chores

* **deps:** mypy 1.18.1 has a regression, pin to 1.17 ([d2a6052](https://github.com/et0and/schools-sdk-python/commit/d2a60529290a6aec3ec330b485b75693664a108e))
* **docs:** use environment variables for authentication in code snippets ([4ad844e](https://github.com/et0and/schools-sdk-python/commit/4ad844ed51c139f70ed4ff2f6e76ed8e0c28b3e1))
* update lockfile ([60dff69](https://github.com/et0and/schools-sdk-python/commit/60dff690c733085e0fbac043e795dde94a538547))

## 0.1.3 (2025-11-22)

Full Changelog: [v0.1.2...v0.1.3](https://github.com/et0and/schools-sdk-python/compare/v0.1.2...v0.1.3)

### Bug Fixes

* compat with Python 3.14 ([c808edf](https://github.com/et0and/schools-sdk-python/commit/c808edf7d22cd29098f8c81b35b7187e4242fe13))
* **compat:** update signatures of `model_dump` and `model_dump_json` for Pydantic v1 ([c78202e](https://github.com/et0and/schools-sdk-python/commit/c78202e38c569f832de2420791b2f63c55765873))


### Chores

* add Python 3.14 classifier and testing ([c91fd4a](https://github.com/et0and/schools-sdk-python/commit/c91fd4a0a6a8311a1405a24d180e62f09f2e1dbf))
* **package:** drop Python 3.8 support ([71ae8c2](https://github.com/et0and/schools-sdk-python/commit/71ae8c26b917bcbeb244382c7e8f0833a0742c7c))

## 0.1.2 (2025-11-04)

Full Changelog: [v0.1.1...v0.1.2](https://github.com/et0and/schools-sdk-python/compare/v0.1.1...v0.1.2)

### Chores

* update SDK settings ([de8b948](https://github.com/et0and/schools-sdk-python/commit/de8b948666ae96c851e1d75011b4e52ba5935be2))

## 0.1.1 (2025-11-04)

Full Changelog: [v0.0.1...v0.1.1](https://github.com/et0and/schools-sdk-python/compare/v0.0.1...v0.1.1)

### Chores

* configure new SDK language ([0fbcc5f](https://github.com/et0and/schools-sdk-python/commit/0fbcc5fddca8b89445bbe6e8fee11e942957b282))
* update SDK settings ([cbc3fcb](https://github.com/et0and/schools-sdk-python/commit/cbc3fcb8509c0535b526b07b9be6232e2c3e8b5d))
* update SDK settings ([03fe460](https://github.com/et0and/schools-sdk-python/commit/03fe460ff9a8c32e51c92d0f8e2f313c23635f4a))
