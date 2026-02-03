# Changelog

All notable changes to the facet-xml workspace will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.44.0](https://github.com/facet-rs/facet-xml/compare/facet-singularize-v0.43.1...facet-singularize-v0.44.0) - 2026-02-03

### Other

- Fix CI: track Cargo.lock and update to ureq v3 API
- Add CI workflows, captain setup, and release-plz
- Update Rust crate ureq to v3
- Initial extraction from facet-rs/facet

### Added

- Initial extraction from [facet-rs/facet](https://github.com/facet-rs/facet)
- `facet-singularize`: Fast, no-regex English singularization
- `facet-dom`: Tree-based (DOM) deserializer for facet
- `facet-xml`: XML serialization and deserialization
- `facet-xml-node`: Raw XML node types
- `facet-atom`: Atom Syndication Format (RFC 4287) types
- `facet-svg`: SVG serialization
