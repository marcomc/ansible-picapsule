# Ansible Role: Picapsule

A role to setup a PiCapsule RaspberryPi system that works as Apple Time Capsule for Time Machine backups

## Requirements

None.

## Role Attributes

Available variables are listed below, along with default values (see `defaults/main.yml`):

- `picapsule_device`: The device name of the disk to be used for the PiCapsule (default: `"sda1"`).
- `picapsule_disk_name`: The name to assign to the PiCapsule disk (default: `"picapsule1"`).
- `picapsule_user`: The user that will own the PiCapsule mount point (default: `"picapsule"`).
- `picapsule_mount_point`: The mount point for the PiCapsule disk (default: `"/media/{{ picapsule_user }}/{{ picapsule_disk_name }}"`).