# Commit messages
This project uses [Conventional Commits](https://www.conventionalcommits.org/) structure, with the types and scopes detailed below

## Types
- **`fix`** Fix to something which was previously not working
- **`enh|enhancement`** Improvement to something which was working
- **`refac|refactor`** Changes to structure
- **`feat|feature`** Adding some new functionality
- **`test|tests`** Changes to the test suite which don't affect functionality
- **`doc|docs`** Changes to documentation which don't affect functionality
- **`sys|system`** Changes to some build, distribution or other systems admin process

## Scopes
- **`[dev]`** Pertains to an unreleased feature/version
- **`[rel|release]`** Pertains to a released feature/version

## Suffices
- **`!`** Commit contains potentially breaking change
- **`~`** Hide commit from auto-generated CHANGELOG

# Branch names
For best results when using cleanup.sh, branches should follow the following structure:

```
<branch (dev or release)>-<type (from commit types)>-<description (one to three words, hyphen-separated)>
```