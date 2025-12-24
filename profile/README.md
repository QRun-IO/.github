# QQQ - Low-Code Application Framework for Engineers

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Maven Central](https://img.shields.io/maven-central/v/com.kingsrook.qqq/qqq-backend-core)](https://search.maven.org/artifact/com.kingsrook.qqq/qqq-backend-core)
[![Java](https://img.shields.io/badge/Java-21+-orange.svg)](https://adoptium.net/)

> **Build powerful applications faster with QQQ's modular, enterprise-ready framework**

QQQ is a comprehensive low-code application framework designed specifically for engineers who need to rapidly develop robust, scalable applications without sacrificing flexibility or performance. Built with modern Java technologies, QQQ provides the building blocks you need to create everything from simple utilities to complex enterprise systems.

## What Makes QQQ Special?

- **Engineer-First Design**: Built by engineers, for engineers - no unnecessary abstractions or magic
- **Modular Architecture**: Use only what you need, or bundle everything together
- **Enterprise Ready**: Production-tested with comprehensive testing, security, and monitoring
- **Modern Java**: Built on Java 21 LTS with contemporary best practices
- **Open Source**: Full transparency with AGPL v3 licensing

## Core Framework

### Backend Modules
- **`qqq-backend-core`** - The foundation of the QQQ ecosystem. Essential for all QQQ applications.
- **`qqq-backend-module-rdbms`** - Relational database support with connection pooling and query optimization.
- **`qqq-backend-module-filesystem`** - Unified file system operations supporting local and cloud storage (AWS S3).
- **`qqq-backend-module-mongodb`** - Native MongoDB integration with document modeling.
- **`qqq-backend-module-sqlite`** - Lightweight embedded database support.

### Middleware & Interfaces
- **`qqq-middleware-javalin`** - High-performance HTTP server with REST APIs and WebSocket support.
- **`qqq-middleware-picocli`** - CLI framework for building powerful command-line applications.
- **`qqq-middleware-lambda`** - AWS Lambda integration for serverless deployment.
- **`qqq-middleware-slack`** - Slack bot and integration framework.

### QBits - Modular Extensions
- **`qbit-user-role-permissions`** - Role-based access control
- **`qbit-workflows`** - Workflow engine and state machines
- **`qbit-webhooks`** - Inbound and outbound webhook handling
- **`qbit-sftp-data-integration`** - SFTP file transfer integration
- **`qbit-standard-process-trace`** - Process execution tracing

### Developer Tools
- **`qqq-mcp-rag`** - AI coding assistant that makes LLMs experts in QQQ
- **`qqq-orb`** - CircleCI orb for CI/CD pipelines
- **`qctl`** - CLI for managing QQQ applications

## Getting Started

### Maven

```xml
<dependency>
    <groupId>com.kingsrook.qqq</groupId>
    <artifactId>qqq-backend-core</artifactId>
    <version>0.25.0</version>
</dependency>
```

### Gradle

```gradle
implementation 'com.kingsrook.qqq:qqq-backend-core:0.25.0'
```

## Resources & Community

- **Documentation**: [GitHub Wiki](https://github.com/QRun-IO/qqq/wiki)
- **Issues & Support**: [GitHub Issues](https://github.com/QRun-IO/qqq/issues)
- **Discussions**: [GitHub Discussions](https://github.com/orgs/QRun-IO/discussions)
- **Project Board**: [QQQ Development](https://github.com/orgs/QRun-IO/projects/12)

## Contributing

We welcome contributions! See our [Contributing Guide](https://github.com/QRun-IO/.github/blob/main/CONTRIBUTING.md) to get started.

## About

QQQ is developed and maintained by the QRun-IO team, focused on building tools that make engineers more productive.

**Website**: [www.qrun.io](https://www.qrun.io)  
**Contact**: [contact@qrun.io](mailto:contact@qrun.io)

## License

This project is licensed under the GNU Affero General Public License v3.0.

---

**Built with care by engineers, for engineers**
