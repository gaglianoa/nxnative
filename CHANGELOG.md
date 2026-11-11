# Changelog

## Unreleased

### Fixed

- Resume incomplete NUP downloads instead of retransferring the whole game
  when the download server supports HTTP byte ranges.
- Validate downloaded NUP containers before building, retrying incomplete
  transfers up to three times.
- Install the separate Metal Toolchain component before compiling shaders on
  Codemagic runners.

### Added

- A manually started Codemagic workflow for an experimental unsigned Pokémon
  Pokopia 2.0.1 iOS IPA, using a private NUP download supplied as a secret.
