# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Your upcoming features go here

### Changed
- Your upcoming changes go here

### Fixed
- Your upcoming bug fixes go here

### Deprecated
- Your upcoming deprecations go here

### Removed
- Your upcoming removals go here

### Security
- Your upcoming security fixes go here

## [0.1.0] - 2025-08-04

### Added
- Initial release of ferrolearn
- Core package structure and modules
- Basic functionality implementation
- Package documentation and README
- PyPI package configuration and metadata
- License and contributing guidelines

### Notes
- First public release on PyPI
- Establishes foundation for future development

---

## Guidelines for Maintaining This Changelog

### Version Format
- Use [Semantic Versioning](https://semver.org/) (MAJOR.MINOR.PATCH)
- MAJOR: incompatible API changes
- MINOR: add functionality in a backwards compatible manner
- PATCH: backwards compatible bug fixes

### Categories
- **Added**: for new features
- **Changed**: for changes in existing functionality
- **Deprecated**: for soon-to-be removed features
- **Removed**: for now removed features
- **Fixed**: for any bug fixes
- **Security**: in case of vulnerabilities

### Best Practices
1. Keep entries concise but descriptive
2. Group similar changes together
3. Use present tense ("Add feature" not "Added feature")
4. Include issue/PR numbers when applicable
5. Update the changelog before each release
6. Move items from "Unreleased" to the new version section
7. Always include the release date in YYYY-MM-DD format

### Example Entry Format
```markdown
## [1.2.0] - 2025-08-15

### Added
- New machine learning algorithm XYZ (#123)
- Support for Python 3.12 (#124)
- Configuration file validation (#125)

### Changed
- Improved performance of core training loop by 30% (#126)
- Updated dependencies to latest versions (#127)

### Fixed
- Fixed memory leak in data preprocessing (#128)
- Resolved issue with model serialization on Windows (#129)

### Deprecated
- `old_function()` will be removed in v2.0.0, use `new_function()` instead (#130)
```

### Release Process Integration
1. Update changelog with new version section
2. Commit changelog changes
3. Create git tag for the version
4. Build and upload to PyPI
5. Create GitHub release with changelog excerpt