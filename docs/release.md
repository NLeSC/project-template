# Release process

## Before release

1. Check that tests or validation steps pass.
2. Update `CHANGELOG.md`.
3. Update `CITATION.cff` version and release date.
4. Check `.zenodo.json` metadata.
5. Check README badges and links.
6. Check installation and usage instructions from a clean environment.

## Create a release

1. Create a GitHub release with a semantic version tag when appropriate, for example `v0.1.0`.
2. Use release notes that explain what changed and who should care.
3. Verify that Zenodo created or updated the archive.
4. Copy the DOI into README and citation documentation.
5. Check that the Research Software Directory entry points to the correct release or repository.

## Release notes template

```markdown
## Summary

## Added

## Changed

## Fixed

## Known limitations

## Citation
```
