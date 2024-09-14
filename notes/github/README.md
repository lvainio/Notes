# GitHub

## Semantic Versioning

### Syntax

`MAJOR`.`MINOR`.`PATCH`

`MAJOR`: version when you make incompatible API changes <br />
`MINOR`: version when you add functionality in a backward compatible manner <br />
`PATCH`: version when you make backward compatible bug fixes <br />

Bug fixes not affecting the API increment the patch version, backward compatible API additions/changes increment the minor version, and backward incompatible API changes increment the major version.

### Requirements

- A precice and clear public API
- Once a versioned package has been released it may NOT be modified.
- Major version zero is for initial development. Anything MAY change at any time.
- Version 1.0.0 defines the public API. The way in which the version number is incremented after this release is dependent on this public API and how it changes.
- A pre-release version MAY be denoted by appending a hyphen and a series of dot separated identifiers immediately following the patch version.

### Examples

- 1.0.0-alpha
- 1.0.0
- 4.5.0
- 1.0.0-0.3.7
- 1.0.0-x.7.z.92
- 1.0.0-x-y-z.--.