# QQQ - Low-code Application Framework for Engineers

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Maven Central](https://img.shields.io/maven-central/v/com.kingsrook.qqq/qqq-backend-core)](https://search.maven.org/artifact/com.kingsrook.qqq/qqq-backend-core)
[![Java](https://img.shields.io/badge/Java-17+-orange.svg)](https://adoptium.net/)

> **Build powerful applications faster with QQQ's modular, enterprise-ready framework**

QQQ is a comprehensive low-code application framework designed specifically for engineers who need to rapidly develop robust, scalable applications without sacrificing flexibility or performance. Built with modern Java technologies, QQQ provides the building blocks you need to create everything from simple utilities to complex enterprise systems.

## 🚀 What Makes QQQ Special?

- **Engineer-First Design**: Built by engineers, for engineers - no unnecessary abstractions or magic
- **Modular Architecture**: Use only what you need, or bundle everything together
- **Enterprise Ready**: Production-tested with comprehensive testing, security, and monitoring
- **Modern Java**: Built on Java 17+ with contemporary best practices
- **Open Source**: Full transparency with AGPL v3 licensing

## 🏗️ Core Framework

### Backend Modules
- **`qqq-backend-core`** - The foundation of the QQQ ecosystem. Essential for all QQQ applications, providing core services, configuration management, and plugin architecture.
- **`qqq-backend-module-rdbms`** - Comprehensive relational database support with connection pooling, transaction management, and query optimization.
- **`qqq-backend-module-filesystem`** - Unified file system operations supporting local storage, cloud storage (AWS S3), and custom storage backends.
- **`qqq-backend-module-mongodb`** - Native MongoDB integration with document modeling and aggregation pipeline support.
- **`qqq-backend-module-sqlite`** - Lightweight, embedded database support for applications requiring local data persistence.

### Middleware & Interfaces
- **`qqq-middleware-javalin`** - High-performance HTTP server providing REST APIs, WebSocket support, and web application backing.
- **`qqq-middleware-picocli`** - Feature-rich command-line interface framework for building powerful CLI applications.
- **`qqq-middleware-lambda`** - AWS Lambda integration for serverless application deployment.
- **`qqq-middleware-slack`** - Slack bot and integration framework for team collaboration tools.

### Development Tools
- **`qqq-openapi`** - OpenAPI/Swagger specification generation and management.
- **`qqq-language-support-javascript`** - JavaScript runtime integration and scripting capabilities.
- **`qqq-utility-lambdas`** - Common utility functions and helpers for AWS Lambda deployments.

## 📦 Getting Started

### Quick Start with Maven

```xml
<dependency>
    <groupId>com.kingsrook.qqq</groupId>
    <artifactId>qqq-backend-core</artifactId>
    <version>0.27.0-SNAPSHOT</version>
</dependency>
```

### Bundle Installation

For a complete QQQ experience, use the main bundle:

```xml
<dependency>
    <groupId>com.kingsrook.qqq</groupId>
    <artifactId>qqq</artifactId>
    <version>0.27.0-SNAPSHOT</version>
</dependency>
```

### Gradle

```gradle
implementation 'com.kingsrook.qqq:qqq-backend-core:0.27.0-SNAPSHOT'
```

## 🌐 Resources & Community

- **🌍 Website**: [www.qrun.io](https://www.qrun.io) - Learn more about QQQ and Kingsrook
- **📚 Documentation**: [GitHub Wiki](https://github.com/Kingsrook/qqq/wiki) - Comprehensive guides and API references
- **🐛 Issues & Support**: [GitHub Issues](https://github.com/Kingsrook/qqq/issues) - Report bugs, request features, or get help
- **💬 Discussions**: [GitHub Discussions](https://github.com/Kingsrook/qqq/discussions) - Community forums and Q&A
- **📖 API Reference**: [Javadoc](https://kingsrook.github.io/qqq/) - Complete API documentation

## 🏢 About Kingsrook

QQQ is developed and maintained by [Kingsrook, LLC](https://qrun.io), a technology company focused on building tools that make engineers more productive. We believe in open source, transparency, and creating solutions that actually solve real problems.

**Contact**: [contact@qrun.io](mailto:contact@qrun.io)  
**Website**: [www.qrun.io](https://www.qrun.io)  
**GitHub**: [github.com/Kingsrook](https://github.com/Kingsrook)

## 📄 License

This project is licensed under the GNU Affero General Public License v3.0 - see the [LICENSE](LICENSE.txt) file for details.

---

**Built with ❤️ by engineers, for engineers**

*QQQ - Empowering developers to build better applications, faster.*
