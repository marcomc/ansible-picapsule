# Ansible Role: timecapsule

A role to setup a timecapsule RaspberryPi system that works as Apple Time Capsule for Time Machine backups

## Requirements

None.

## Role Attributes

Available variables are listed below, along with default values (see `defaults/main.yml`):

- `timecapsule_device`: The device name of the disk to be used for the timecapsule (default: `"sda1"`).
- `timecapsule_disk_name`: The name to assign to the timecapsule disk (default: `"timecapsule1"`).
- `timecapsule_user`: The user that will own the timecapsule mount point (default: `"timecapsule"`).
- `timecapsule_mount_point`: The mount point for the timecapsule disk (default: `"/media/{{ timecapsule_user }}/{{ timecapsule_disk_name }}"`).