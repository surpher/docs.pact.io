---
title: pact_models
custom_edit_url: https://github.com/pact-foundation/pact-reference/edit/master/rust/pact_models/CHANGELOG.md
---
<!-- This file has been synced from the pact-foundation/pact-reference repository. Please do not edit it directly. The URL of the source file can be found in the custom_edit_url value above -->

## 0.2.2 - Fixes to the matching rule parser

* 3207cb49 - feat: implement each key and aech value matching rule definitions (Ronald Holshausen, Wed Nov 24 14:28:42 2021 +1100)
* d3234684 - feat: update matcher defintions to support references (Ronald Holshausen, Tue Nov 23 16:13:49 2021 +1100)
* 682df9e4 - feat: update matcher defintions to include the semver matcher (Ronald Holshausen, Tue Nov 23 14:24:02 2021 +1100)
* 20a275fb - feat: Improve the error message format for matching rule definitions (Ronald Holshausen, Mon Nov 22 15:21:57 2021 +1100)
* a859d0e1 - fix: make sure metadata entries are correctly encoded when downgrading a pact (Ronald Holshausen, Wed Nov 17 16:54:15 2021 +1100)

## 0.2.1 - Update V4 models to support FFI + plugins

* 15b8f08f - feat: add functions to return mutable references to the V4 model trait (Ronald Holshausen, Tue Nov 16 10:03:03 2021 +1100)
* fa83806c - feat: add mutable methods to Pact model traits (Ronald Holshausen, Tue Nov 9 16:04:16 2021 +1100)

## 0.2.0 - Pact V4 + Plugins release


## 0.2.0-beta.6 - Bugfix Release

* 48a6be5f - fix: EachValue was outputting the wrong JSON (Ronald Holshausen, Tue Oct 19 16:35:17 2021 +1100)

## 0.2.0-beta.5 - matching synchronous request/response messages


## 0.2.0-beta.4 - Enhancements for plugins

* a52db737 - feat: record the version of the lib that created the pact in the metadata (Ronald Holshausen, Tue Oct 12 14:55:42 2021 +1100)
* 35ff0993 - feat: record the version of the lib that created the pact in the metadata (Ronald Holshausen, Tue Oct 12 14:52:43 2021 +1100)
* 407cc2e5 - fix: notEmpty matching rule defintion should be applied to any primitive value (Ronald Holshausen, Thu Oct 7 14:08:02 2021 +1100)

## 0.2.0-beta.3 - Fixes from master + Updated matching rule definitions

* 9fd9e652 - feat: do no write empty comments + added consumer version to metadata (Ronald Holshausen, Thu Sep 30 17:40:56 2021 +1000)
* df715cd5 - feat: support native TLS. Fixes #144 (Matt Fellows, Mon Sep 20 13:00:33 2021 +1000)

## 0.1.4 - WASM support + native TLS certs

* df715cd5 - feat: support native TLS. Fixes #144 (Matt Fellows, Mon Sep 20 13:00:33 2021 +1000)
* 067ded8f - feat: expose Pact models via WASM (Ronald Holshausen, Sun Sep 5 11:55:26 2021 +1000)

## 0.2.0-beta.2 - Support for getting interaction markup from plugins

* 067ded8f - feat: expose Pact models via WASM (Ronald Holshausen, Sun Sep 5 11:55:26 2021 +1000)

## 0.1.3 - Bugfix Release


## 0.2.0-beta.1 - Support for plugins

* c0bdd359 - fix: PluginData configuration is optional (Ronald Holshausen, Thu Sep 2 15:37:01 2021 +1000)

## 0.2.0-beta.0 - Beta version supporting Pact plugins


## 0.1.2 - upgrade nom to 7.0

* c274ca1a - fix: use the pacts for verification endpoint if the conusmer selectors are specified #133 (Ronald Holshausen, Sun Aug 22 11:51:22 2021 +1000)

## 0.1.1 - Bugfix Release

* 8bcd1c7e - fix: min/max type matchers must not apply the limits when cascading (Ronald Holshausen, Sun Aug 8 15:50:40 2021 +1000)
* 4ca3e02b - Merge pull request #129 from mitre/docpath (Ronald Holshausen, Thu Aug 5 12:16:56 2021 +1000)

## 0.1.0 - Final Version

* 31873ee3 - feat: added validation of provider state JSON (Ronald Holshausen, Wed Jul 14 15:44:20 2021 +1000)

## 0.0.5 - Moved structs to models crate + bugfixes and enhancements

* e2151800 - feat: support generating UUIDs with different formats #121 (Ronald Holshausen, Sun Jul 11 12:36:23 2021 +1000)
* 80e3c4e7 - fix: retain the data type for simple expressions #116 (Ronald Holshausen, Sun Jul 4 13:02:43 2021 +1000)
* b1a4c8cb - fix: failing tests #116 (Ronald Holshausen, Sun Jul 4 11:28:20 2021 +1000)
* e21db699 - fix: Keep the original value when injecting from a provider state value so data type is retained #116 (Ronald Holshausen, Sat Jul 3 18:01:34 2021 +1000)
* 8b075d38 - fix: FFI function was exposing a struct from the models crate (Ronald Holshausen, Sun Jun 27 11:30:55 2021 +1000)

## 0.0.4 - Refactor + Bugfixes

* b0ac7141 - feat: support graphql as a JSON content type (Ronald Holshausen, Sat Jun 5 15:14:06 2021 +1000)
* a44cbbee - fix: verifier was returning a mismatch when the expected body is empty #113 (Ronald Holshausen, Sat Jun 5 15:07:22 2021 +1000)
* 4e328d93 - feat: implement verification for RequestResponsePact, Consumer, Provider (Ronald Holshausen, Thu Jun 3 16:59:23 2021 +1000)
* 2f678213 - feat: initial prototype of a pact file verifier (Ronald Holshausen, Thu Jun 3 14:56:16 2021 +1000)

## 0.0.3 - Moved provider state models


## 0.0.2 - FFI support

* 6af4d3f - feat: allow ffi bindings to set spec version (Matt Fellows, Sun May 2 22:41:41 2021 +1000)

## 0.0.1 - Refactor: moved content type and body code from pact_matching


## 0.0.0 - First Release
