# Example

`dna_tssuite` is a DNA layer: it bundles the topic layers every tssuite repo
takes, no code. Declare it as a dev dependency and instantiate it once:

```bash
dart pub add dev:dna_tssuite     # Dart projects
pnpm add -D @tssuite/dna-tssuite   # TypeScript projects
gg dna init
gg dna build
```

The placed test instantiates the layers on every test run and keeps the
repo in sync with them.
