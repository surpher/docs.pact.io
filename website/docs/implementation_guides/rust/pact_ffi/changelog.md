---
title: pact_ffi
custom_edit_url: https://github.com/pact-foundation/pact-reference/edit/master/rust/pact_ffi/CHANGELOG.md
---
<!-- This file has been synced from the pact-foundation/pact-reference repository. Please do not edit it directly. The URL of the source file can be found in the custom_edit_url value above -->

## 0.1.3 - Bugfix Release

* d43b1847 - Merge pull request #164 from tienvx/feat-filter-info (Ronald Holshausen, Fri Nov 19 11:38:41 2021 +1100)
* 41e69a22 - feat: allow set filter info (tienvx, Thu Nov 18 08:56:36 2021 +0700)
* 7c561f2a - feat: allow set consumer version selectors (tienvx, Thu Nov 18 00:12:31 2021 +0700)
* 260deb70 - fix: support specifying matching_branch in verifications (Matt Fellows, Wed Nov 17 17:47:37 2021 +1100)

## 0.1.2 - Bugfix Release

* 5d4a09c6 - feat: store the pact specification version with the mock server (Ronald Holshausen, Wed Nov 17 14:46:56 2021 +1100)
* 675506e1 - feat: add pactffi_pact_handle_write_file which knows about the spec version (Ronald Holshausen, Wed Nov 17 13:58:45 2021 +1100)
* aff4d301 - fix: FFI always detects + stores JSON bodies as plain text (Matt Fellows, Tue Nov 16 23:02:12 2021 +1100)
* fc5be202 - fix: update to latest driver crate (Ronald Holshausen, Tue Nov 16 16:19:02 2021 +1100)
* e4a445ba - fix: race condition when shutting down plugin via FFI (Ronald Holshausen, Tue Nov 16 16:01:18 2021 +1100)

## 0.1.1 - Support V4 synchronous messages + protobuf plugin

* df23ba3d - fix: allow multiple consumer version selectors (Matt Fellows, Mon Nov 15 14:28:04 2021 +1100)

## 0.1.0 - Pact V4 release

* 59e21413 - feat: Pact V4 release (Ronald Holshausen, Thu Nov 4 16:54:56 2021 +1100)
* 918e5beb - fix: update to latest models and plugin driver crates (Ronald Holshausen, Tue Oct 19 17:09:48 2021 +1100)
* bfa04370 - fix: display the error message when the verification can not be run due to an error (Ronald Holshausen, Tue Oct 19 11:09:21 2021 +1100)
* 35ff0993 - feat: record the version of the lib that created the pact in the metadata (Ronald Holshausen, Tue Oct 12 14:52:43 2021 +1100)
* 2e86c48d - Merge pull request #154 from pact-foundation/feat/xml-matchers (Matt Fellows, Tue Oct 5 16:39:18 2021 +1100)
* 9a2049c2 - feat: support XML bodies in FFI interface (Matt Fellows, Thu Sep 30 22:08:01 2021 +1000)
* d171edfd - feat: support provider branches (Matt Fellows, Wed Sep 29 22:47:21 2021 +1000)

## 0.0.3 - support native TLS certs + updated verifier FFI functions

* 42be9eb8 - feat: add FFI functions to extract logs from a verifcation run (Ronald Holshausen, Tue Sep 28 12:48:40 2021 +1000)
* ab89152e - Merge pull request #150 from tienvx/make-state-change-url-optional (Ronald Holshausen, Tue Sep 21 09:20:54 2021 +1000)
* df715cd5 - feat: support native TLS. Fixes #144 (Matt Fellows, Mon Sep 20 13:00:33 2021 +1000)
* 339a9504 - feat: make state change url optional (tienvx, Mon Sep 20 12:13:29 2021 +0700)
* dab70272 - feat: add verifier ffi function set consumer filters (tienvx, Tue Sep 14 23:47:14 2021 +0700)
* 36f7e477 - fix: fix missing last tag (tienvx, Tue Sep 14 23:51:02 2021 +0700)
* 05f4c3de - feat: add verifier ffi function set verification options (tienvx, Wed Sep 8 23:48:13 2021 +0700)
* b8e51313 - Merge pull request #137 from tienvx/ffi-function-update-provider-state (Ronald Holshausen, Sat Sep 4 13:04:50 2021 +1000)

## 0.0.2 - Bugfix Release

* c274ca1a - fix: use the pacts for verification endpoint if the conusmer selectors are specified #133 (Ronald Holshausen, Sun Aug 22 11:51:22 2021 +1000)

## 0.0.1 - M1 architecture support + Bugfixes

* b5a7b779 - feat: support new selectors (Matt Fellows, Mon Aug 9 13:27:33 2021 +1000)
* 8bcd1c7e - fix: min/max type matchers must not apply the limits when cascading (Ronald Holshausen, Sun Aug 8 15:50:40 2021 +1000)
* 6d1ff318 - fix: conan packages for pact_ffi (Ronald Holshausen, Mon Jul 12 09:23:48 2021 +1000)

## 0.0.0 - Initial Release
