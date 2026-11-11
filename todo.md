# GLPI Repository Roadmap

- [x] Initial Docker Compose configuration
- [ ] Lock GLPI image tag to specific release version (avoid `:latest`)
- [ ] Create automated database export script (`mysqldump` to local `.sql.gz`)
- [ ] Implement backup strategy for `glpi_data` and `glpi_plugins` volumes
- [ ] Add systemd service wrapper for automated host startup