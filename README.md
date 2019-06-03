# Grafana Stack config

## Purpose
This docker-compose file is here to give the possibility to be include in a git submodule call to be include in a ansible role.

## Volume
It use docker driver NFS.

## Variables
Please, provides thoses variables in your playbook

| vars | what ? | exemple |
|:------:|--------|:-------:|
| {{ grafana_deploy_replica }} | INTEGER: Number of replica       |    2     |
| {{ grafana_external_port }} | INTEGER: TCP Port      |   3000      |
| {{ grafana_data_nfs_path }}      | STRING: provide full nfs path       | /share/swarm/grafana/data |
| {{ grafana_config_nfs_path }}      | STRING: provide full nfs path | /share/swarm/grafana/config |
| {{ grafana_nfs_server }}      | STRING: provide IP/hostanme | 192.168.0.2 |
| {{ grafana_dashboards_nfs_path }}      | STRING: provide full nfs path | /share/swarm/grafana/dashboards |










## Licence
See [license](license.md)