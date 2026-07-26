## 1.0.0 (2026-07-26)


### ✨ Features ✨

* **dart-lib:** seed diene_dart_lib mirror ([fd877ba](https://github.com/AtomiCloud/diene.dart_lib/commit/fd877bad845ba841c005fc4df93321053fe27533))

# Changelog

All notable changes to this package are documented here. Releases are managed
from conventional commits by the repository release workflow.

## 0.0.0

- Establish the pure-Dart library template: workspace-member package metadata,
  strict analysis options, and pub.dev publish hygiene.
- Add the replaceable `Note` sample: an immutable value type with a JSON wire
  codec and the pure `summarizeNote` transform, exported from the barrel.
- Add the dependency-light `assertNoteSummary` TestHelper and its meta suite.
- Add the C0 fixture harness with a SHA-256 digest manifest and a
  decode/encode/decode round trip.
