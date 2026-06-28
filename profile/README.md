# Apikee

Apikee is an API key platform for building and securing products across multiple runtimes.

<p>
  <img src="https://img.shields.io/badge/Open%20Source-5%20codebases-1677ff?style=for-the-badge" alt="5 codebases" />
  <img src="https://img.shields.io/badge/SDKs-4%20packages-1677ff?style=for-the-badge" alt="4 SDKs" />
  <img src="https://img.shields.io/badge/Docs-apikee.com%2Fdocs-1677ff?style=for-the-badge" alt="Docs" />
</p>

## What’s here

- [Apikee codebase](../apikee) | [website](../web)
- [Node.js SDK](../node) | [npm](https://www.npmjs.com/package/apikee) | [contributing](../node/CONTRIBUTING.md)
- [Python SDK](../python) | [PyPI](https://pypi.org/project/apikee/) | [contributing](../python/CONTRIBUTING.md)
- [.NET SDK](../dotnet) | [NuGet](https://www.nuget.org/packages/Apikee/) | [contributing](../dotnet/CONTRIBUTING.md)
- [Java SDK](../java) | [Maven Central](https://central.sonatype.com/artifact/dev.apikee/apikee-spring) | [contributing](../java/CONTRIBUTING.md)

The other workspace projects support the broader Apikee product and infrastructure, but they are not open source.

## Quick Stats

<p align="left">
	<img src="https://img.shields.io/badge/core%20codebases-1-1677ff?style=for-the-badge" alt="1 core codebase" />
	<img src="https://img.shields.io/badge/public%20SDKs-4-1677ff?style=for-the-badge" alt="4 public SDKs" />
	<img src="https://img.shields.io/badge/private%20systems-4%2B-1677ff?style=for-the-badge" alt="private systems" />
</p>

- 1 core Apikee web codebase.
- 4 public SDKs: Node.js, Python, .NET, and Java.
- 1 architecture image showing the public platform and internal services.

## Architecture

![Apikee architecture diagram](architecture.png)

The short version: the SDKs create and verify keys locally, the Apikee runtime lives in Docker, and the surrounding private services handle licensing, authentication, email, storage, logging, and database work.

## Links

- [Apikee docs](https://apikee.com/docs) - product documentation, including OAuth and OpenID integrations.
- [AI Premium License](https://apikee.com/billing/upgrade?plan=premium) - premium AI licensing and upgrade flow.
- [Docker image source](../apikee/Dockerfile) - the container definition for the Apikee runtime.

## Contributing

Want to help? Start here:

- [Apikee contribution guide](../apikee/CONTRIBUTING.md)
- [Node.js contribution guide](../node/CONTRIBUTING.md)
- [Python contribution guide](../python/CONTRIBUTING.md)
- [.NET contribution guide](../dotnet/CONTRIBUTING.md)
- [Java contribution guide](../java/CONTRIBUTING.md)

Keep changes focused, add tests when behavior changes, and match the style already used in the target package.

## Contact

Questions, ideas, or collaboration: [oussama@apikee.com](mailto:oussama@apikee.com)