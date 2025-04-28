# Step 1: Understanding semantic versioning

Semantic Versioning (SemVer) is a versioning scheme that communicates meaning about the underlying changes in a release. It makes it easy for developers to understand the impact of upgrades.

## 📝 SemVer format

A semantic version number has three parts: **MAJOR.MINOR.PATCH**

Each number communicates specific kinds of changes:

- **MAJOR** version increments when you make incompatible API changes
- **MINOR** version increments when you add functionality in a backward compatible manner
- **PATCH** version increments when you make backward compatible bug fixes

Additional labels for pre-release and build metadata are available as extensions to the MAJOR.MINOR.PATCH format.

## 📝 SemVer examples

Let's look at some examples:

- `1.0.0`: Initial release
- `1.0.1`: Bug fixes, no new features
- `1.1.0`: New features added, backward compatible
- `2.0.0`: Breaking changes that require users to modify their code
- `1.0.0-alpha`: Pre-release version
- `1.0.0-beta.1`: Another pre-release version

## :keyboard: Task: Make your first change

1. Navigate to the `app.js` file in your repository
2. Click the edit (✏️) icon
3. Edit the file by adding a comment to the bottom of the file: `// Version 0.1.0 - Initial version`
4. Commit the change directly to a new branch, creating a pull request
5. Create the pull request
6. Comment "semver-understood" on this pull request when complete
