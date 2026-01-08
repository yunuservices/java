# java
Java images for Pterodactyl and forks.

## About GraalVM Image
Images are based on Oracle GraalVM JDK with OL9 and include NUMA support plus
`mimalloc` preloaded by default.

- `ghcr.io/yunuservices/java:graalvm_21`
- `ghcr.io/yunuservices/java:graalvm_25`

>[!WARNING]
> These are experimental images.\
> Images using Microsoft's [Mimalloc](https://github.com/microsoft/mimalloc) allocator, an allocator that does not have profiling capabilities than jemalloc.