# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 0.4.0 (2021-11-15)


### Bug Fixes

* **bundler:** remove console warnings ([de0cbe7](https://github.com/codesandbox/sandpack/commit/de0cbe7d5f5525d34af2d85e84809d79efada213))
* **client:** remove source maps from bundler ([1731224](https://github.com/codesandbox/sandpack/commit/1731224aaaaae6b56aaa1c05f8daaed56ff1d0c6))
* **codemirror:** upgrade dependencies ([#125](https://github.com/codesandbox/sandpack/issues/125)) ([7cbf7f1](https://github.com/codesandbox/sandpack/commit/7cbf7f1aa8f07b4826eb8ebbeb1ca5d868b5c4df))
* **codeviewer:** placeholder misalign ([a41adb7](https://github.com/codesandbox/sandpack/commit/a41adb75d0716e5f6ee0a5f5c8bdf59b3eb8891f))
* **codeviewer:** placeholder style ([2224338](https://github.com/codesandbox/sandpack/commit/22243383df143ef05a7855df862d1d5ed0649cb0))
* **codeviewer:** refactor ready-only mode ([e1374ea](https://github.com/codesandbox/sandpack/commit/e1374ea6a284b654c11c642244dbe11278912861))
* **codeviewer:** remove focus ring on mobile ([046eeff](https://github.com/codesandbox/sandpack/commit/046eeffd2e134a0b0b531f6b908aa4905dd040f6))
* **codeviewer:** remove focusable and aria attrs ([eea276a](https://github.com/codesandbox/sandpack/commit/eea276afa43681978700674c679270e694b5456c))
* **file tab:** revert hover state ([d429893](https://github.com/codesandbox/sandpack/commit/d429893d4eb8200d05039d9027561b88e3517505))
* **highlight error:** improv ([d3fa2da](https://github.com/codesandbox/sandpack/commit/d3fa2da595115e6ce97c8bc9e128240dac374a1c))
* intersection observer threshold ([#48](https://github.com/codesandbox/sandpack/issues/48)) ([997fb97](https://github.com/codesandbox/sandpack/commit/997fb97f891cb6782ea51ca1b9cba89b07f0baca))
* **listener:** add global queue of listener to be registered ([71d834b](https://github.com/codesandbox/sandpack/commit/71d834b45af04f3c53f77e2f2a766b70be7c63df))
* **listeners:** add listeners to clients already created ([98e974c](https://github.com/codesandbox/sandpack/commit/98e974c2bc2b2d272a298ff50dfbe06da5194f47))
* **listeners:** improve ([0de411a](https://github.com/codesandbox/sandpack/commit/0de411a3801c6286d020f4e1fdee31be7d171dbe))
* loading timeout only counted after the client is instantiated ([5436312](https://github.com/codesandbox/sandpack/commit/543631278fdcc178b2e8c77ac11355d7a4084f08))
* **react-layout:** remove max-height limit for print media ([#121](https://github.com/codesandbox/sandpack/issues/121)) ([e0001a5](https://github.com/codesandbox/sandpack/commit/e0001a575b13b17188a0233bab36c38800e6c21b))
* **react:** dedupe deps ([#145](https://github.com/codesandbox/sandpack/issues/145)) ([bc86c31](https://github.com/codesandbox/sandpack/commit/bc86c3160fbf07c8c226f8c2462ffcadd3faac0e))
* **react:** do not translate code blocks and error messages ([#117](https://github.com/codesandbox/sandpack/issues/117)) ([c09acfc](https://github.com/codesandbox/sandpack/commit/c09acfcc79bb8456f6bc6d0966ebaa2fdc626256))
* **react:** make instructions elements ids unique ([#123](https://github.com/codesandbox/sandpack/issues/123)) ([3bd8a78](https://github.com/codesandbox/sandpack/commit/3bd8a78e87758e97c4bec909d318b5917547f520))
* **react:** update clients after reset files ([47efe33](https://github.com/codesandbox/sandpack/commit/47efe33c03e83eeac60990fe3dfe3edda6d28144))
* **scroller:** allow the main wrap to scroll ([76aab51](https://github.com/codesandbox/sandpack/commit/76aab5180218c939915fbd44b272bef998bddacf))
* **style:** remove unnecessary code ([37fc909](https://github.com/codesandbox/sandpack/commit/37fc90960befac06c25ba377092a078ba37174eb))
* ui adjustments ([ea782ec](https://github.com/codesandbox/sandpack/commit/ea782ecb6fb25d12772a485ea176ed8a20525f99))
* **unsubscribe listener:** avoiding delete the listener list before call all unsubs functions ([2767bce](https://github.com/codesandbox/sandpack/commit/2767bcef89a7dde8e7532792419e1be2d6622e37))


### Features

* **build:** add errors from esbuild ([0267a19](https://github.com/codesandbox/sandpack/commit/0267a1961b19fa23122221a945010e3909cbbebd))
* **build:** external dependencies ([f5238a9](https://github.com/codesandbox/sandpack/commit/f5238a902d9b663420b8c5713dd761d347b66cc3))
* **code viewer:** pass ref ([03ecfa7](https://github.com/codesandbox/sandpack/commit/03ecfa7d48dfceb408bb8fd51e550d5b013cfcb0))
* **code viewer:** shift ast library ([eb8a65a](https://github.com/codesandbox/sandpack/commit/eb8a65a838c78778cf754a7f84d1ba91413b607c))
* **codeeditor:** line decorators ([83d2bf9](https://github.com/codesandbox/sandpack/commit/83d2bf9cf42135b7cd83b74accc180177a0a13dc))
* **codeviewer:** remove prism in favor of codemirro itself ([d7fae1f](https://github.com/codesandbox/sandpack/commit/d7fae1f7adb88f62a2b3c27237eec579bf6373ce))
* **codeviewer:** widget decorator ([d796cb2](https://github.com/codesandbox/sandpack/commit/d796cb253190c06414a19c7b2edc06608ca84dd2))
* **decorators:** story ([132ded8](https://github.com/codesandbox/sandpack/commit/132ded8b9bd7010c54b68ce501c6735b35f22d4a))
* **inline error:** add prop and story ([9b09270](https://github.com/codesandbox/sandpack/commit/9b09270a8107d428d231c2d90e968c37b7efcb4a))
* **react:** add dynamically stories for each theme ([#88](https://github.com/codesandbox/sandpack/issues/88)) ([3c365d3](https://github.com/codesandbox/sandpack/commit/3c365d357ff41ed9d399ecf70a475f563fa16a96))
* **react:** move to esbuild ([5a125a3](https://github.com/codesandbox/sandpack/commit/5a125a3744e3d739f9eda8c8235c726113b683c0))
* **react:** syntax inline error ([d980ac3](https://github.com/codesandbox/sandpack/commit/d980ac30077668c1d1de3034e507b03f35458a9e))
* **scripts:** clean script ([eca0505](https://github.com/codesandbox/sandpack/commit/eca0505c41769ae9e37809792129633858ad4131))
* **template:** add react typescript ([#114](https://github.com/codesandbox/sandpack/issues/114)) ([96aaac8](https://github.com/codesandbox/sandpack/commit/96aaac86afc2287a1e96fa95a9836d156a4bc9de))
* **template:** add vanilla typescript ([#130](https://github.com/codesandbox/sandpack/issues/130)) ([d33eeb9](https://github.com/codesandbox/sandpack/commit/d33eeb9be6809fb40165d97e34a13471ec5faf1b))
* **usesandpack:** reset-file and reset-all-files ([47b6c36](https://github.com/codesandbox/sandpack/commit/47b6c369e24f9df47b9d80c1b6fe81159a9f43d1))





## [0.3.1](https://github.com/codesandbox/sandpack/compare/v0.3.0...v0.3.1) (2021-11-15)


### Bug Fixes

* **react:** dedupe deps ([#145](https://github.com/codesandbox/sandpack/issues/145)) ([bc86c31](https://github.com/codesandbox/sandpack/commit/bc86c3160fbf07c8c226f8c2462ffcadd3faac0e))





# [0.3.0](https://github.com/codesandbox/sandpack/compare/v0.2.3...v0.3.0) (2021-11-15)


### Features

* **template:** add vanilla typescript ([#130](https://github.com/codesandbox/sandpack/issues/130)) ([d33eeb9](https://github.com/codesandbox/sandpack/commit/d33eeb9be6809fb40165d97e34a13471ec5faf1b))





## [0.2.3](https://github.com/codesandbox/sandpack/compare/v0.2.2...v0.2.3) (2021-11-11)

**Note:** Version bump only for package @codesandbox/sandpack-react





## [0.2.2](https://github.com/codesandbox/sandpack/compare/v0.2.1...v0.2.2) (2021-11-11)


### Bug Fixes

* **react-layout:** remove max-height limit for print media ([#121](https://github.com/codesandbox/sandpack/issues/121)) ([e0001a5](https://github.com/codesandbox/sandpack/commit/e0001a575b13b17188a0233bab36c38800e6c21b))





## [0.2.1](https://github.com/codesandbox/sandpack/compare/v0.2.0...v0.2.1) (2021-11-10)

**Note:** Version bump only for package @codesandbox/sandpack-react





# [0.2.0](https://github.com/codesandbox/sandpack/compare/v0.1.20...v0.2.0) (2021-11-10)


### Features

* **template:** add react typescript ([#114](https://github.com/codesandbox/sandpack/issues/114)) ([96aaac8](https://github.com/codesandbox/sandpack/commit/96aaac86afc2287a1e96fa95a9836d156a4bc9de))





## [0.1.20](https://github.com/codesandbox/sandpack/compare/v0.1.19...v0.1.20) (2021-11-08)


### Bug Fixes

* **codemirror:** upgrade dependencies ([#125](https://github.com/codesandbox/sandpack/issues/125)) ([7cbf7f1](https://github.com/codesandbox/sandpack/commit/7cbf7f1aa8f07b4826eb8ebbeb1ca5d868b5c4df))





## [0.1.19](https://github.com/codesandbox/sandpack/compare/v0.1.18...v0.1.19) (2021-11-04)

**Note:** Version bump only for package @codesandbox/sandpack-react





## [0.1.18](https://github.com/codesandbox/sandpack/compare/v0.1.17...v0.1.18) (2021-11-04)

**Note:** Version bump only for package @codesandbox/sandpack-react





## [0.1.17](https://github.com/codesandbox/sandpack/compare/v0.1.16...v0.1.17) (2021-11-04)


### Bug Fixes

* **react:** make instructions elements ids unique ([#123](https://github.com/codesandbox/sandpack/issues/123)) ([3bd8a78](https://github.com/codesandbox/sandpack/commit/3bd8a78e87758e97c4bec909d318b5917547f520))





## [0.1.16](https://github.com/codesandbox/sandpack/compare/v0.1.15...v0.1.16) (2021-11-03)


### Bug Fixes

* **react:** do not translate code blocks and error messages ([#117](https://github.com/codesandbox/sandpack/issues/117)) ([c09acfc](https://github.com/codesandbox/sandpack/commit/c09acfcc79bb8456f6bc6d0966ebaa2fdc626256))
