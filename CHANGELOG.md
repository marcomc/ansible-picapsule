# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0] - 2024-11-20

### Added

- Initial release of ansible-picapsule role
- Support for configuring Raspberry Pi as Apple Time Capsule
- Automatic disk formatting with exFAT filesystem
- Automatic mounting configuration
- Netatalk configuration for Time Machine backups
- Systemd service for automatic Netatalk restart
- User-configurable device, disk name, and mount points
- Support for Debian-based systems
- Basic dependency management (curl, systemd, exfat-fuse, exfat-utils, netatalk)
- Uninstall functionality

### Configuration Options

- `picapsule_device`: Device name configuration
- `picapsule_disk_name`: Disk name configuration
- `picapsule_user`: User ownership configuration
- `picapsule_mount_point`: Mount point configuration

[1.0.0]: https://github.com/marcomc/ansible-picapsule/releases/tag/v1.0.0 