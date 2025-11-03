---
layout: default
title: Getting Started
nav_order: 1
parent: Docs
permalink: /docs/getting-started
---

# Getting Started

## Voraussetzungen
- macOS mit Xcode (neueste Version)
- Ruby & Bundler (für diese Website-Doku)
- Git

## Zielplattformen (Start)
- **Console (CLI)** und **macOS (App)**

## Build (Beispiel)
```bash
# Dev-Repo klonen (Platzhalter – anpassen, sobald festgelegt)
git clone {{ site.dev_repo_url }} shingena
cd shingena

# macOS / Console Targets bauen (Beispiel – Xcode-Projekt folgt)
# xcodebuild -scheme Shingena -configuration Release

# CLI ausführen (Platzhalter)
# ./build/Shingena --help
