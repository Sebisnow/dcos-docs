---
UID: 56f98448d9c7f
post_title: Installing
post_excerpt: ""
layout: docs.jade
published: true
menu_order: 2
page_options_require_authentication: false
page_options_show_link_unauthenticated: false
hide_from_navigation: false
hide_from_related: false
---
DC/OS can be installed on any cluster of physical or virtual machines.

# Local Installation

For first-time users or developers looking to build services or modify DC/OS, the [Vagrant installer][1] provides a quick, free way to deploy a virtual cluster on a single machine.

# Cloud Provisioning

For users deploying to the public cloud, DC/OS offers configurable cloud provisioning templates for [AWS][2] and [Azure][3] that will manage virtual machines and DC/OS installation.

DC/OS can be installed on other public and private clouds using the Datacenter Installation process, provided virtual machines and networks are created first.

# Datacenter Installation

For new users installing to existing virtual or physical machines, on-premises or in the cloud, the [Automated Installer][4] provides a guided experience for bootstrapping a DC/OS cluster.

For advanced users installing to existing virtual or physical machines, on-premises or in the cloud, the [Manual Installer][5] provides a scriptable, automatable interface to integrate with your preferred configuration management system.

 [1]: /administration/installing/local/
 [2]: /administration/installing/cloud/aws/
 [3]: /administration/installing/cloud/azure/
 [4]: /administration/installing/custom/automated-installer
 [5]: /administration/installing/custom/scripted-installer