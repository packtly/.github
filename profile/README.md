# Packtly

**Build, publish and manage Debian packages with reproducible, container-native workflows.**

Packtly is an open-source toolkit centered around [Aptly](https://www.aptly.info/), providing reproducible Debian package builds, 
APT repository management, and deployment automation. It integrates container-native build environments, 
Aptly-powered package repositories, and modern CI/CD to automate the entire Debian package lifecycle—from 
source code to production-ready repositories. Repository management and build infrastructure for Debian 
and embedded Linux systems.

## Projects

| Repository | Description |
|---|---|
| `packtly-builder` | Container-native build toolkit for reproducible **multi-architecture Debian packages** with integrated **Aptly repository publishing** for **amd64, arm64, and armhf**. |
| `packtly-infra` | Infrastructure automation for deploying and operating Packtly. Uses **Ansible** to provision hosts, deploy the **Aptly repository server** as **Podman Quadlets**, manage secrets, and configure the complete repository environment. |

## Features

- Reproducible Debian package builds
- Debian source package generation and publishing (`.dsc`, `.orig.tar.*`, `.debian.tar.*`)
- Aptly-based APT repository management
- Snapshot and release promotion workflows
- Container-native CI/CD pipelines
- Multi-architecture builds (**amd64**, **arm64**, and **armhf**)
- Automated GPG signing for packages and repositories
- Secure package verification and repository metadata management
- Automated package publishing to Aptly repositories
- Embedded Linux deployment workflows
- Infrastructure automation with Ansible and Podman Quadlets

## Goals

- Simplify Debian repository management
- Automate package publishing pipelines
- Provide reproducible embedded Linux workflows
- Integrate build and deployment infrastructure

---

🚧 Work in progress
Packtly is under active development. Feedback, discussions and contributions are welcome.
