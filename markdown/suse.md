<!-- .slide: data-background-image="images/suse_logo_full_epsexport.svg" data-background-size="90% auto" -->
Note: SUSE start


<!-- Slide -->
# 1
### OpenStack


<!-- Slide -->
###### SUSE 
###### OpenStack Cloud 7
with

<img src="images/openstack/openstack-newton-logo.png" style="width:15%;">

based on

`SLES 12 SP2`


<!-- Slide -->
### Kernel
4.4-based

<br> 
### Virtualization <!-- .element class="fragment" data-fragment-index="1"-->
KVM, Xen<!-- .element class="fragment" data-fragment-index="1"--> 

VMWare vSphere<!-- .element class="fragment" data-fragment-index="1"-->

IBM z/VM <!-- .element class="fragment" data-fragment-index="1"-->

Kubernetes Docker via Magnum <!-- .element class="fragment" data-fragment-index="1"-->


<!-- Slide -->
Deployment
 
## Crowbar 
and 
## Chef

Note: Crowbar v4.0, Chef v10


<!-- Slide -->
### Openstack Support

All Core Services plus
<table>
<tr>
    <td><img src="images/openstack/aodh.svg"></td>
    <td><img src="images/openstack/barbican-techpreview.svg"></td>
    <td><img src="images/openstack/ceilometer.svg"></td>
    <td><img src="images/openstack/designate-techpreview.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/gnocchi-techpreview.svg"></td>
    <td><img src="images/openstack/heat.svg"></td>
    <td><img src="images/openstack/horizon.svg"></td>
    <td><img src="images/openstack/ironic.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/magnum.svg"></td>
    <td><img src="images/openstack/manila.svg"></td>
    <td><img src="images/openstack/mistral-notsupported.svg"></td>
    <td><img src="images/openstack/monasca.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/murano-techpreview.svg"></td>
    <td><img src="images/openstack/panko-notsupported.svg"></td>
    <td><img src="images/openstack/rally-notsupported.svg"></td>
    <td><img src="images/openstack/sahara-techpreview.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/tempest-techpreview.svg"></td>
    <td><img src="images/openstack/trove-techpreview.svg"></td>
    <td></td>
    <td><img src="images/openstack/legend.svg"></td>
</tr>
</table>

Note: Designate is "package only"


<!-- Slide -->
### Life Cycle 
New downstream version with 
 
###### every 2nd upstream release

Next: 
 
Pike release (Q1/18)

Note: every 2nd may no issue in enterprise setups, you don't switch that easily production.


<!-- Slide -->
Additionally recommended
 
### SUSE Studio
### SUSE Manager
### SLES HA extension 
(for KVM/Xen compute nodes)


<!-- Slide -->
### Support

Cloud 7: <!-- .element class="fragment" data-fragment-index="1"-->
###### 27 months <!-- .element class="fragment" data-fragment-index="1"-->
after GA <!-- .element class="fragment" data-fragment-index="1"-->

<br>
From 8 on: 36 months <!-- .element class="fragment" data-fragment-index="2"-->

(aligned with SLES12-SP3) <!-- .element class="fragment" data-fragment-index="2"-->

Note: SUSE OpenStack Cloud 8 will be aligned to SLES12 SP3 and should have a full three year lifecycle as explained by PM at SUSECon.


<!-- Slide -->
### Pricing
 
control node

admin node

compute node, per-socket-pair (SLES)

Swift

<br>
##### depending on:
 
12x5 or 24x7

special SLAs

Note: like `scheduled standby`, Support engineer (ASE/PSE/DSE)


<!-- Slide -->
# 2
## Ceph


<!-- Slide -->
###### SUSE Enterprise Storage 5

based on

### Luminous

with 

`OpenATTIC`

based on SLES12-SP3


<!-- Slide -->
Deployment via
### DeepSea/Salt


<!-- Slide -->
### Features
BlueStore <!-- .element class="fragment" -->

Data compression <!-- .element class="fragment" -->

CephFS Multi MDS <!-- .element class="fragment" -->

iSCSI <!-- .element class="fragment" -->

NFS Ganesha/S3 <!-- .element class="fragment" -->

CIFS Samba (Tech Preview) <!-- .element class="fragment" -->


<!-- Slide -->
## Pricing

per node

Basis subscription:

with 4 OSDs, 3/5 MONs, Admin/Deploy node

priority support included

Note: release every 6 months, support for N and N-1, longer cycles on request


<!-- Slide -->
# 3
## Container Platform


<!-- Slide -->

###### SUSE CaaS Platform

Kubernetes

Docker (OS)

SUSE MicroOS

Note: Storage SES, NFS, hostpath


<!-- Slide -->
# 4
## More


<!-- Slide -->
SUSE aquired 

### HPE's cloud assets

OpenStack

Cloud Foundry

Stackato 


<!-- Slide -->
### HPE Helion
and
### SUSE Cloud 8

will share the same code base


<!-- Slide -->
You should also know:


<!-- Slide -->
##SUSE

Is the only distro

which does `not` charge for

development of `upstream features`

if you agree on it!

All included in the subscription!

