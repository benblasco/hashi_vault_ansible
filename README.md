# Run Hashicorp vault in a container (using podman rootlessly)

## Introduction

This repo shows you how to spin up Hashicorp vault in a container using podman in rootless mode.

It is intended as a simple proof of concept or lab, and should not be deployed as is in a production environment.

## Assumed Knowledge

- Linux (particularly Fedora, RHEL, and derivatives)
- Containers
- Podman (or Docker)

## How to deploy Hashicorp Vault in a container with Podman

Instructions can be found here:
[README_BUILD_VAULT.md](README_BUILD_VAULT.md)

## How to test retrieval of secrets from Vault with an Ansible playbook

Instructions can be found here:
[README_TEST_VAULT.md](README_TEST_VAULT.md)

