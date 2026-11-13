# Changelog

All notable user-visible changes to the Gotify TOS application package.

## 2.6.1-1 — 2026-11-14

### Added
- First release. Gotify (`gotify/server:2.6.1`, Docker Hub official image, unmodified)
  packaged as a TOS 7 Docker application, published on port 8122 and running
  as a non-root user (1000:1000).
- Persistent data is kept under `/Volume1/DockerAppData/gotifydocker/`.
