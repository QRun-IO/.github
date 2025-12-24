# QQQ

Low-code application framework for Java.

[![Maven Central](https://img.shields.io/maven-central/v/com.kingsrook.qqq/qqq-backend-core)](https://central.sonatype.com/namespace/com.kingsrook.qqq)
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Java](https://img.shields.io/badge/Java-21+-orange.svg)](https://adoptium.net/)

## Core Modules

| Module | Description |
|--------|-------------|
| `qqq-backend-core` | Core framework - required for all QQQ apps |
| `qqq-backend-module-rdbms` | Relational database support |
| `qqq-backend-module-filesystem` | Local and S3 file storage |
| `qqq-backend-module-mongodb` | MongoDB integration |
| `qqq-middleware-javalin` | HTTP server and REST APIs |
| `qqq-middleware-picocli` | CLI applications |
| `qqq-middleware-lambda` | AWS Lambda support |

## QBits

Modular extensions: `qbit-user-role-permissions`, `qbit-workflows`, `qbit-webhooks`, `qbit-sftp-data-integration`

## Quick Start

```xml
<dependency>
    <groupId>com.kingsrook.qqq</groupId>
    <artifactId>qqq-backend-core</artifactId>
    <version>0.25.0</version>
</dependency>
```

## Resources

- [Documentation](https://github.com/QRun-IO/qqq/wiki)
- [Getting Started](https://github.com/QRun-IO/qqq-app-starter)
- [Issues](https://github.com/QRun-IO/qqq/issues)
