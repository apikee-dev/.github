# Apikee

Apikee is an API key platform for building and securing products across multiple runtimes.

This profile is the public map of the open-source Apikee ecosystem: one core product codebase, four SDK package codebases, and the docs people actually need when they are trying to wire it all together.

## What’s here

- [Apikee codebase](../apikee) | [website](../web) - the product-facing web app and platform shell.
- [Node.js SDK](../node) | [npm](https://www.npmjs.com/package/apikee) | [contributing](../node/CONTRIBUTING.md) - Express, Fastify, and Hono support.
- [Python SDK](../python) | [PyPI](https://pypi.org/project/apikee/) | [contributing](../python/CONTRIBUTING.md) - FastAPI, Flask, and ASGI support.
- [.NET SDK](../dotnet) | [NuGet](https://www.nuget.org/packages/Apikee/) | [contributing](../dotnet/CONTRIBUTING.md) - ASP.NET Core middleware and Swagger support.
- [Java SDK](../java) | [Maven Central](https://central.sonatype.com/artifact/dev.apikee/apikee-spring) | [contributing](../java/CONTRIBUTING.md) - Spring Boot autoconfiguration and SpringDoc support.

The other workspace projects are part of the broader Apikee product and infrastructure, but they are not open source.

## General Stats

<p align="left">
	<img src="https://img.shields.io/badge/open--source%20codebases-5-1677ff?style=for-the-badge" alt="5 open-source codebases" />
	<img src="https://img.shields.io/badge/public%20SDKs-4-1677ff?style=for-the-badge" alt="4 public SDKs" />
	<img src="https://img.shields.io/badge/package%20ecosystems-4-1677ff?style=for-the-badge" alt="4 package ecosystems" />
</p>

- 1 core Apikee web codebase.
- 4 public SDKs: Node.js, Python, .NET, and Java.
- 1 architecture image that shows the public platform and the private supporting systems.

## Architecture

![Apikee architecture diagram](architecture.png)

The short version: the SDKs create and verify keys locally, the Apikee runtime lives in Docker, and the surrounding private services handle licensing, authentication, email, storage, logging, and database work.

## Useful Links

- [Apikee docs](https://apikee.com/docs) - product documentation, including OAuth and OpenID integrations.
- [AI Premium License](https://apikee.com/billing/upgrade?plan=premium) - premium AI licensing and upgrade flow.
- [Docker image source](../apikee/Dockerfile) - the container definition for the Apikee runtime.

## Contributing

Want to help? Pick the repo you care about and start there:

- [Apikee contribution guide](../apikee/CONTRIBUTING.md)
- [Node.js contribution guide](../node/CONTRIBUTING.md)
- [Python contribution guide](../python/CONTRIBUTING.md)
- [.NET contribution guide](../dotnet/CONTRIBUTING.md)
- [Java contribution guide](../java/CONTRIBUTING.md)

Keep changes focused, add tests when behavior changes, and match the style already used in the target package.