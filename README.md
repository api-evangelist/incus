# Incus (incus)

Incus is a modern open source system container and virtual machine manager maintained by LinuxContainers.org as a community-led fork of Canonical's LXD. It provides a unified experience for running and managing system containers and VMs across single hosts and clusters, with image-based deployment, live migration, snapshots, projects, and a comprehensive RESTful API for automation and tooling integration.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/incus/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/incus/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Containers
- Virtual Machines
- Virtualization
- Linux
- Open Source

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-19

## APIs

### Incus REST API

The Incus REST API is the canonical interface to the Incus container and virtual machine manager. All communication between Incus and its clients happens over HTTP, using TLS for remote access or a Unix socket for local access. The API covers the complete lifecycle of instances, images, networks, storage pools, projects, profiles, certificates, and cluster members, with support for asynchronous operations and WebSocket-based event streams.

- **Human URL:** [https://linuxcontainers.org/incus/docs/main/rest-api/](https://linuxcontainers.org/incus/docs/main/rest-api/)

#### Tags

- Containers
- Virtual Machines
- Cluster Management
- REST API

#### Properties

- [Documentation](https://linuxcontainers.org/incus/docs/main/rest-api/)
- [Authentication](https://linuxcontainers.org/incus/docs/main/authentication/)
- [GitHub Repository](https://github.com/lxc/incus)
- [OpenAPI](openapi/incus-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/incus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/incus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Rules](rules/incus-rules.yml)

## Common Properties

- [Website](https://linuxcontainers.org/incus/)
- [Documentation](https://linuxcontainers.org/incus/docs/main/)
- [Getting Started](https://linuxcontainers.org/incus/docs/main/tutorial/first_steps/)
- [GitHub Repository](https://github.com/lxc/incus)
- [Forum](https://discuss.linuxcontainers.org/)
- [Issues](https://github.com/lxc/incus/issues)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
