# Changelog

## [0.2.0] — 2026-11-18

### Compatibility

- Validate against MoonBit `0.10.15+943464bfa`; compatibility with older
  compilers is not guaranteed. Use a pre-1.0 minor release for this
  toolchain/manifest transition.

### Changed

- Publish the existing migration from `moon.mod.json` to `moon.mod` and
  the package relocation from `src/lib` to `lib`. The public import path
  remains `dowdiness/svg-dsl/lib`.
- Include the existing current trait/extension syntax and StringBuilder
  constructor migration. Generated interfaces explicitly expose trait methods.
- Apply MoonBit 0.10.15 formatter output: `Int32` spelling and labelled
  default-argument syntax. No rendering logic changes in this release preparation.
- Update installation instructions to use `moon add` and `moon.pkg`.

The module has no external dependencies.

## [0.1.0]

Initial published release using `moon.mod.json` and the `src/lib` source layout.
