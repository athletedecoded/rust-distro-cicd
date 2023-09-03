# Rust Distroless CI/CD Template

[![CI/CD Pipeline](https://github.com/athletedecoded/rust-distro-cicd/actions/workflows/deploy.yml/badge.svg)](https://github.com/athletedecoded/rust-distro-cicd/actions/workflows/deploy.yml)

[![Build Container on PR](https://github.com/athletedecoded/rust-distro-cicd/actions/workflows/build_container.yml/badge.svg)](https://github.com/athletedecoded/rust-distro-cicd/actions/workflows/build_container.yml)

[![Lint Dockerfile](https://github.com/athletedecoded/rust-distro-cicd/actions/workflows/lint_dockerfile.yml/badge.svg)](https://github.com/athletedecoded/rust-distro-cicd/actions/workflows/lint_dockerfile.yml)

Template for containerized Rust projects with automated CI/CD pipeline using Github Actions

On Push:
* Format/lint/test code
* Lint Dockerfile
* Build and deploy distroless container to GHCR

On Pull:
* Lint Dockerfile if changes
* Rebuild container

