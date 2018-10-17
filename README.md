# morpheus_ha_ansible

This is a repo of Ansible roles that allows you to provision a High Availablility Morpheus application.

## Architecture

* 2 App servers
* 3 Elasticsearch nodes (will support additional nodes)
* 3 RabbitMQ nodes (will support additional nodes)
* 3 Percona XtraDB Cluster Nodes (will support additional nodes)

### Assumptions:

* CentOS 7 only (right now)
* 11 nodes only (right now)
* Entirely separated services (right now)
