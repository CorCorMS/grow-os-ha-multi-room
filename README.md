# Grow OS HA Multi-Room

Multi-room foundation repository for scaling Grow OS HA beyond a single cabinet.

This repository is the planned multi-room line of the project. It is intended to
host the future architecture for:

- multiple grow rooms or cabinets
- shared policy patterns
- room-specific registers and device mappings
- room-aware dashboards
- future shared services across several grow zones

## Current status

Initial repository scaffold.

There is not yet a production-ready multi-room package in this repository.

## Planned scope

- room-based package structure
- per-room Arbiter layers
- shared registry concepts
- shared dashboard conventions
- installer/add-on preparation
- migration path from single-room Grow OS HA

## Repository structure

- [docs/README.md](docs/README.md)
- [packages/README.md](packages/README.md)
- [lovelace/README.md](lovelace/README.md)
- [grow_os_ha_installer/README.md](grow_os_ha_installer/README.md)
- [examples/README.md](examples/README.md)
- [ARCHITECTURE.md](ARCHITECTURE.md)
- [INSTALLATION.md](INSTALLATION.md)
- [CHANGELOG.md](CHANGELOG.md)

## License

This project is not open source.

It is licensed for private personal use only. Use by companies, organizations,
clubs, associations, communities, public institutions, commercial operators, or
other group-based entities is not permitted without prior written permission.

This restriction applies to all repository parts, including code, dashboards,
automations, configuration, JSON data, installer files, and the control logic
itself.

See [LICENSE](LICENSE).
