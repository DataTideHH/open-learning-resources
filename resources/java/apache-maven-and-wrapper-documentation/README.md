# Apache Maven and Maven Wrapper Documentation

This folder contains a link/reference entry for the official Apache Maven and Maven Wrapper documentation.

**Title:** Apache Maven and Maven Wrapper Documentation  
Publisher / original source: Apache Software Foundation  
Official Maven documentation: https://maven.apache.org/guides/  
Official Maven Wrapper documentation: https://maven.apache.org/tools/wrapper/  
Local copy included: No

## Links

- [Maven documentation and guides](https://maven.apache.org/guides/)
- [Maven Getting Started Guide](https://maven.apache.org/guides/getting-started/)
- [Standard directory layout](https://maven.apache.org/guides/introduction/introduction-to-the-standard-directory-layout)
- [Maven Wrapper documentation](https://maven.apache.org/tools/wrapper/)

## Important note

This is a link-only reference entry.

The Maven Wrapper belongs in the project repository and pins the Maven distribution used by that project. The wrapper scripts should be invoked as `./mvnw` on macOS/Linux or `mvnw.cmd` on Windows instead of assuming that a matching global Maven installation is available.

## Why this resource is useful

Maven and the Maven Wrapper are useful for learning and reviewing:

- project object models (`pom.xml`)
- dependency management
- build lifecycles and goals
- standard Java project structure
- plugins
- test and package workflows
- reproducible project-specific Maven execution
- cross-platform build commands

This resource directly supports the Maven Wrapper workflow used in the [`spring-boot-process-api-basics`](https://github.com/DataTideHH/spring-boot-process-api-basics) project.

## License note

Apache Maven documentation is linked here as an official Apache Software Foundation reference.

No Maven documentation or binaries are redistributed or relicensed by this repository. The official site's terms and Apache project licenses apply.

Review date: 2026-07-26
