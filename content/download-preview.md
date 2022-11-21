---
title: Download
tableOfContents: true
menu:
  main:
    parent: download
---

## tinylog {{% preview-version %}}

### Java

tinylog API and implementation for Java and any other JVM language

{{% download-artifact file="tinylog" artifacts="tinylog-api,tinylog-impl" bundles="org.tinylog.api,org.tinylog.impl" version="preview" %}}

### Kotlin

Enhanced logging API for Kotlin with tinylog implementation

{{% download-artifact file="tinylog-kotlin" artifacts="tinylog-api-kotlin,tinylog-impl" bundles="org.tinylog.api-kotlin,org.tinylog.impl" version="preview" %}}

## Third-Party Logging APIs

### SLF4J

`slf4j-tinylog` is a binding for SLF4J, which means that `slf4j-api` must also exist in the classpath, but no other binding than `slf4j-tinylog`. The binding supports SLF4J 1.7 and later as well as SLF4J 2.0 and later.

All log entries are forwarded from `org.slf4j.Logger` to tinylog and processed by the tinylog implementation. Markers are mapped to tinylog’s tags. MDC and tinylog’s thread context share their data.

{{% download-artifact file="slf4j-tinylog" artifacts="slf4j-tinylog" bundles="org.tinylog.api.slf4j" version="preview" %}}