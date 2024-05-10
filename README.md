# 🚀 Compare Versions Action

[![Test Compare Versions](https://github.com/BrainXio/compare-versions/actions/workflows/test-compare-versions.yml/badge.svg)](https://github.com/BrainXio/compare-versions/actions/workflows/test-compare-versions.yml)

<div style="display: flex; align-items: center;">
    <div style="flex-shrink: 0; margin-right: 20px; text-align: justify;">
        <img src="https://avatars.githubusercontent.com/u/168876326?s=200&v=4" alt="description of image" width="75" height="75">
    </div>
    <div>
        "A GitHub Action to compare source and target versions."
    </div>
</div>

## ✨ Usage

Configure this action effortlessly in your workflow file:

```yaml
- name: Compare Versions
  uses: <username>/<repository>@<version>
  with:
    source-version: '<SOURCE_VERSION>'
    target-version: '<TARGET_VERSION>'
```

### Inputs

- `source-version` (required): The source version for comparison.
- `target-version` (required): The target version for comparison.

### Outputs

- `version-equality`: Type of version equality: "full", "partial", or "not".
- `versions-are-equal`: Boolean indicating if the versions are equal.
- `highest-version`: Highest version between source and target versions.

## 🌟 Example

```yaml
- name: Compare Versions
  uses: <username>/<repository>@<version>
  with:
    source-version: 'v1.0.0'
    target-version: 'v2.0.0'
```

## 📝 License

This action is licensed under the [The Unlicense](LICENSE). Feel free to use, modify, and distribute it according to your needs. Contributions are welcome!
