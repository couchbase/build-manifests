# build-manifests
This repository contains build manifests for the Couchbase Server and related projects. A build manifest is a YAML file that specifies the source code repositories and their revisions, along with build settings, required to build a particular version of a software product.

The build manifests in this repository are used by the Couchbase build system to build and package the Couchbase Server binaries, as well as other Couchbase projects like Sync Gateway, Lite Core, and C Mock.

## Manifest Structure

A typical build manifest in this repository consists of the following sections:

- 'vars': Defines variables that can be used in other sections of the manifest, such as the source code repositories and build settings.
- 'repos': Specifies the source code repositories and their revisions, along with any patches or other modifications to be applied to them.
- 'build': Configures the build settings, such as compiler flags, linker flags, and other options specific to the build platform and target architecture.
- 'targets': Defines the output targets of the build, such as binary executables, libraries, and test suites.
- 'packages': Specifies the packaging options for the output targets, such as file formats and compression settings.


## Getting Help
If you have any questions or issues with this repository, you can get help by creating a new issue in the GitHub issue tracker, or by asking for help in the Couchbase forums or community Slack channel.

## Contributing
Contributions to this repository are welcome. If you want to add support for a new platform or architecture, or update an existing manifest for a new release, you can create a pull request with your changes.

Before submitting a pull request, please make sure to test your changes by building the software using the updated manifest, and ensure that the resulting binaries are functional and meet the quality standards of the Couchbase project.