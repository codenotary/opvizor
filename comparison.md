---
title: Comparison
layout: page
nav_order: 3
has_children: true
---

# How Opvizor compares to others
When setting up monitoring solutions, you have two main configuration approaches:
- a) Centralized
- b) Edge-based

Centralized: Manage data collection and agent settings directly from the solution's interface. Ideal for stable environments where central control is easy.
Edge-based: Edit configuration files on individual servers. Best for dynamic environments using observability-as-code, enabling version control and auditing within git repositories.

Most of the solutions usually require an agent to operate. On one side a custom agent brings wider functionaly and therefore more rich results where on the other side it can be quite complex to setup at some point.

In Opvizor many integrations work without the need of agent installation. Here are listed some of them:
- VMware vSphere
- NetApp
- Microsoft SQL
- Oracle
- PostgreSQL
- Dell PowerMax
- Cisco UCS
- Cisco Switches
- Brocade Switches


See how Opvizor compares to other products on specific areas.

|                       | Opvizor                   | Dynatrace             | Datadog               | Instana               | Netdata                   |
|:----------------------|:--------------------------|:----------------------|:----------------------|:----------------------|:--------------------------|
| Agent                 | flexible agent/-less      | OneAgent / ActiveGate | Datadog agent         | Instana agent         | Netdata agent             |
| Data Collector Config | centrally / at the edge   | at the edge           | at the edge           | at the edge           | centrally / at the edge   |         
| Alerting              | centrally                 | at the edge           | at the edge           | at the edge           | centrally / at the edge   |  
| Dashboards            | centrally / at the edge   | centrally             | centrally             | centrally             | centrally / at the edge   |
| AIR Gapped Setup      | fully supported           | limited functionality | limited functionality | limited functionality | fully supported           |


Further section will reveal case by case comparison for Opvizor and other products in additional details

----

Useful links

- [Our demo environmnet](https://demoml.codenotary.io/)
