<!-- .slide: data-background-image="images/mirantis-logo-2color-rgb-transparent.png" data-background-size="auto 90%" -->


<!-- Slide -->
# 1
### OpenStack


<!-- Slide -->
### Mirantis Cloud Platform 1.1
with

<img src="images/openstack/openstack-ocata-release-logo-480.png" style="width:15%;">

based on

`Ubuntu 16.04 LTS`


<!-- Slide -->
Mirantis is the

### only

distribution

not maintaining an own

### Base OS


<!-- Slide -->
### Controller nodes
Ubuntu 16.04 LTS

<br>
### Compute nodes <!-- .element class="fragment" data-fragment-index="1"-->
Ubuntu 16.04 LTS <!-- .element class="fragment" data-fragment-index="1"-->

(no longer support for SLES/RHEL/Oracle) <!-- .element class="fragment" data-fragment-index="1"-->


<!-- Slide -->
### Kernel
4.4-based

### Hypervisor
KVM


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
New downstream version with

###### every upstream release

within 1-6 months

<br>
Next:

MCP 1.2 (Ocata, Q3-Q4/2017)


<!-- Slide -->
Additionally included

### Stacklight
### DriveTrain
### Kubernetes
### OpenContrail


<!-- Slide -->
### Support
Each release for
###### 3 years
(1y full, +2y limited)


<!-- Slide -->
### Pricing

per machine (Ubuntu)

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
and <!-- .element class="fragment" data-fragment-index="1"-->
### Ubuntu <!-- .element class="fragment" data-fragment-index="1"-->


<!-- Slide -->
Deployment via
### SaltStack
### OpenAttic
(Decapod/ansible discontinued)


<!-- Slide -->
### RBD
### RadosGW
and
### BlueStore
supported


<!-- Slide -->
## Pricing
Subscription

per machine
