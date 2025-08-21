# Reusable GHA Workflows

## Release

1. Tag a commit with the next version (SemVer with optional minor and patch values)
2. Create a release via GitHub
   It should be from your tag to the previous one, which should be auto-detected.
   Use the builtin _Generate the release notes_.
