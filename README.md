# download.surrealdb.com

This repository houses the code which powers the global software repository for SurrealDB releases, available at [download.surrealdb.com](https://download.surrealdb.com). When a new version of SurrealDB is released, binaries are built for a number of different platforms and operating systems. For simple automated installation of the latest  version, visit the [SurrealDB install page](https://surrealdb.com/install) for more information.

Supported operating systems and architectures:

| Operating system | Architecture | Description                                    |
| ---------------- | ------------ | ---------------------------------------------- |
| macOS            | `amd64`      | `64bit` Intel processors                       |
| macOS            | `arm64`      | `64bit` Apple Silicon processors               |
| macOS            | `universal`  | `64bit` Intel and Apple Silicon processors     |
| Linux            | `amd64`      | `64bit` build for Unix operating systems       |
| Linux            | `arm64`      | `64bit` build for Unix operating systems       |
| Windows          | `amd64`      | `64bit` build for Windows operating system     |
| Windows          | `arm64`      | `64bit` build for Windows operating system     |

Supported architectures with Docker:

| Architecture | Description                                    |
| ------------ | ---------------------------------------------- |
| `amd64`      | `64bit` Linux `amd` environment                |
| `arm64`      | `64bit` Linux `arm` environment                |

For Docker builds visit the [SurrealDB repository](https://hub.docker.com/repository/docker/surrealdb/surrealdb) on Docker Hub.