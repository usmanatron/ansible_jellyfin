# Ansible Role: jellyfin

Installs Jellyfin using Docker. Includes backups for the config directory

## Requirements

This role assumes the following:

* Docker is installed

## Role Variables

### Main Variables

| Name | Details |
| --- | --- |
| `jellyfin_version` | The version of the Jellyfin Docker container |
| `media_directory` | The local directory that contains your media files. |

### Default Variables

| Name | Default Value | Details |
| --- | --- | --- |
| `app_name` | `jellyfin` | Used to name things |
| `app_folder` | `/apps/jellyfin` | The base directory for deployment |

## Dependencies

None

## License

MIT
