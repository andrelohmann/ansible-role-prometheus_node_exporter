andrelohmann.prometheus_node_exporter
=====================================

Install and configure prometheus node_exporter

https://prometheus.io/docs/guides/node-exporter/

https://github.com/prometheus/prometheus/wiki/Default-port-allocations

Role Variables
--------------

    prometheus_node_exporter_listen_ip: 127.0.0.1
    prometheus_node_exporter_listen_port: 9100
    prometheus_node_exporter_sysctl_perf: 0 # kernel.perf_event_paranoid setting - follow the module documentation

Example Playbook
----------------

    - hosts: prometheus_node_exporter
      roles:
      - andrelohmann.prometheus_node_exporter

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
