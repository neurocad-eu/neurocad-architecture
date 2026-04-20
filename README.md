# neurocad-architecture

[![Architecture Validation](https://github.com/neurocad-eu/neurocad-architecture/actions/workflows/validate.yml/badge.svg)](https://github.com/neurocad-eu/neurocad-architecture/actions/workflows/validate.yml)
[![Release](https://img.shields.io/github/v/release/neurocad-eu/neurocad-architecture)](https://github.com/neurocad-eu/neurocad-architecture/releases)

Public system overview and architecture notes for NeuroCAD.

## Purpose

This repository documents the public-facing architecture of NeuroCAD at the system boundary level.

It is intended to help technical partners, investors, and engineering evaluators understand:

- how the public platform is structured
- where the public integration surface sits
- what remains proprietary

## Scope

This repository documents system layers, interfaces, and public boundary decisions.

It does not expose private kernel internals, training implementation details, or operational secrets.

## Included

- system overview
- layer boundaries
- public versus proprietary split
- trust boundary notes
- architectural decision records

## Core documents

- [`docs/system-overview.md`](docs/system-overview.md)
- [`docs/system-context.md`](docs/system-context.md)
- [`docs/public-private-boundary.md`](docs/public-private-boundary.md)
- [`docs/inference-flow.md`](docs/inference-flow.md)
- [`docs/trust-boundaries.md`](docs/trust-boundaries.md)
- [`adr/001-public-boundary.md`](adr/001-public-boundary.md)
- [`adr/002-benchmark-publication.md`](adr/002-benchmark-publication.md)
