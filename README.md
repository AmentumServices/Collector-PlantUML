# What is this?

[![Release](https://github.com/jacobsfederal/Collector-PlantUML/actions/workflows/collect.yml/badge.svg?branch=main)](https://github.com/JacobsFederal/Collector-PlantUML/actions/workflows/collect.yml)

This is a project that automatically collects artifacts to ease in air-gapped transfer from the internet.

It runs actions manually or on Push and creates a release.

In this case, it collects the binaries and the associated container images via skopeo for:

- Docker Hub PlantUML Container image
- PlantUML Binaries
