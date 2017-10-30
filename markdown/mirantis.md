<!-- .slide: data-background-image="images/mirantis-logo-2color-rgb-transparent.png" data-background-size="auto 90%" -->


<!-- Slide -->
# 1
### OpenStack


<!-- Slide -->
### Mirantis Cloud Platform 1.1
with

<img src="images/openstack/openstack-ocata-release-logo-480.png" style="width:15%;">


<!-- Slide -->
Mirantis is the

### only

distribution

not maintaining an own

### Base OS


<!-- Slide -->
### Nodes
Compute and Controller

Ubuntu 16.04 LTS

(no longer support for SLES/RHEL/Oracle) <!-- .element class="fragment" data-fragment-index="1"-->


<!-- Slide -->
### Kernel
4.4-based

### Virtualization
KVM

Kubernetes/Docker


<!-- Slide -->
Deployment

via
### MCP DriveTrain
SaltStack based + Jenkins/Gerrit


<!-- Slide -->
### Openstack Support

All Core Services plus

<table>
<tr>
    <td><img src="images/openstack/aodh.svg"></td>
    <td><img src="images/openstack/barbican-notsupported.svg"></td>
    <td><img src="images/openstack/ceilometer.svg"></td>
    <td><img src="images/openstack/designate.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/gnocchi-notsupported.svg"></td>
    <td><img src="images/openstack/heat.svg"></td>
    <td><img src="images/openstack/horizon.svg"></td>
    <td><img src="images/openstack/ironic.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/magnum-notsupported.svg"></td>
    <td><img src="images/openstack/manila-notsupported.svg"></td>
    <td><img src="images/openstack/mistral-notsupported.svg"></td>
    <td><img src="images/openstack/monasca-notsupported.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/murano.svg"></td>
    <td><img src="images/openstack/panko-notsupported.svg"></td>
    <td><img src="images/openstack/rally-notsupported.svg"></td>
    <td><img src="images/openstack/sahara.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/tempest-notsupported.svg"></td>
    <td><img src="images/openstack/trove-notsupported.svg"></td>
    <td></td>
    <td><img src="images/openstack/legend.svg"></td>
</tr>
</table>


<!-- Slide -->
### Life Cycle
New downstream version with <!-- .element class="fragment" data-fragment-index="1"-->

###### every upstream release <!-- .element class="fragment" data-fragment-index="1"-->

within 1-6 months, depending on CI/CD <!-- .element class="fragment" data-fragment-index="1"-->

<br>
Next: MCP 1.2 end of Q4/2017 <!-- .element class="fragment" data-fragment-index="2"-->

(supports Mitaka, Ocata, and Pike) <!-- .element class="fragment" data-fragment-index="2"-->

Note: multiple OpenStack releases per MCP version, release == tagged and tested git commit instead of specific release


<!-- Slide -->
Additionally included

### Stacklight
### DriveTrain
### Kubernetes
### OpenContrail

Note: OpenContrail 3.2.3 and Kubernetes 1.7

<!-- Slide -->
### Support
Each release for
###### 3 years
(1y full, +2y limited)


<!-- Slide -->
### Pricing

per machine

<br>
##### depending on:

8x5

24x7

Managed Service


<!-- Slide -->
# 2
## Ceph


<!-- Slide -->
Part of
### MCP

based on <!-- .element class="fragment" data-fragment-index="1"-->

### Luminous <!-- .element class="fragment" data-fragment-index="1"-->


<!-- Slide -->
Deployment via
### SaltStack
### OpenAttic
(Decapod/ansible discontinued)


<!-- Slide -->
### Features

RBD

RadosGW

BlueStore


<!-- Slide -->
## Pricing
Subscription

per machine
