# SerdeSniffer

# Introduction

SerdeSniffer uses taint analysis and flow-sensitive bottom-up summary algorithm to check component deserialization gadget chains detection in effective time.

## SetUp(Todo)

### Docker

The SerdeSniffer Dockerfile provides latest version of doop and souffle. After copying the SerdeSniffer project, use tools/summary-run-scripts/run.sh for analysis.

# 🐞Discovered vulnerabilities

## Command execution

### The combination of Spring-aop and ZAPROXY (Not accepted)

Referencs:

- [https://hackmd.io/@fe1w0/SkKUicKR6](https://hackmd.io/@fe1w0/SkKUicKR6)

![1711022209974poc.gif](https://raw.githubusercontent.com/fe1w0/ImageHost/main/image/1711022209974poc.gif)

### org.clojure:clojure ( 1.9.0 - 1.12.0 )

Referencs:

- [https://hackmd.io/@fe1w0/HyefvRQKp](https://hackmd.io/@fe1w0/HyefvRQKp)

![command execution](https://github.com/clojure/clojure/assets/50180586/35f899ef-b7c5-44a1-b6c5-6883b690f967)

## Dos

### org.clojure:clojure ( 1.2.0 - 1.12.0 )

Referencs:

- [https://hackmd.io/@fe1w0/rymmJGida](https://hackmd.io/@fe1w0/rymmJGida)
