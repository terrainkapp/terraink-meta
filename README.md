# terraink-meta

This repository stores metadata, configuration, and content feeds used by [**terraink.app**](https://terraink.app).

## Purpose

Use this repo for non-application runtime code that powers Terraink externally, such as:

- release notes (for example [`updates/updates.json`](./updates/updates.json))
- environment-specific metadata
- app configuration files
- other structured content consumed by terraink.app

## Scope

- Keep app source code in the main Terraink app [repository](https://github.com/terrainkapp/terraink).
- Keep data/config/content that can be updated independently in this meta repository.

## Current structure

- `updates/updates.json`: release notes and update modal content for terraink.app.
