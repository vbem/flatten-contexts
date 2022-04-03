[![Testing](https://github.com/vbem/flatten-contexts/actions/workflows/test.yml/badge.svg)](https://github.com/vbem/flatten-contexts/actions/workflows/test.yml)
[![Super Linter](https://github.com/vbem/flatten-contexts/actions/workflows/linter.yml/badge.svg)](https://github.com/vbem/flatten-contexts/actions/workflows/linter.yml)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/vbem/flatten-contexts?label=Release&logo=github)](https://github.com/vbem/flatten-contexts/releases)
[![Marketplace](https://img.shields.io/badge/GitHub%20Actions-Marketplace-blue?logo=github)](https://github.com/marketplace/actions/flatten-contexts)

# Flatten contexts
This action can dump **"flattened"** [*GitHub contexts*](https://docs.github.com/en/actions/learn-github-actions/contexts#example-printing-context-information-to-the-log), which is more friendly than JSON for searching and debugging. 😀

![Example](https://repository-images.githubusercontent.com/477080111/8cb0e9f1-a74f-44f1-8b50-c35cc3ad13e9 "vbem/flatten-contexts")

## Example usage

```yaml
- name: Dump flattened GitHub contexts
  uses: vbem/flatten-contexts@v1
```

## Inputs

ID | Type | Default | Description
--- | --- | --- | ---
`sep` | String | ` 👉 ` | Separator between key and value