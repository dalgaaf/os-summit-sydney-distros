<!-- .slide: data-background-image="images/distros-all.svg" data-background-size="90% auto" -->


<!-- Slide -->
How to assess

if a distro can provide 

## support

for your project?


<!-- Slide -->
## Marketing? 

Just Kidding! <!-- .element class="fragment"-->

Rhetorical question! <!-- .element class="fragment"-->


<!-- Slide -->
If you are lucky:

The experience of 

### yourself 

or 

### somebody

you know


<!-- Slide -->
If you have time and ressources:

### evaluation
###### PoC

Before you stuck with one!


<!-- Slide -->
Another may helpful indicator:

### Some statistics

on recent project

##Contributions

of the distributions


<!-- Slide -->
## Openstack


<!-- Slide -->
##### Commits to OpenStack Core
<sup>Cinder, Glance, Keystone, Neutron, Nova, Swift</sup>
<canvas data-chart="line">
<!--
{
 "data" : {
     "labels": ["G", "H", "I", "J", "K", "L", "M", "N", "O", "P"],
     "datasets": [
         {
             "label": "Canonical",
	     "backgroundColor":"rgba(221,72,20,.9)",
             "data": [116, 120, 44, 20, 25, 8, 9, 9, 6, 6]
         },
         {
             "label": "SUSE",
	     "backgroundColor":"rgba(125,194,70,.9)",
             "data": [49, 116, 109, 91, 36, 43, 98, 83, 74, 76]
         },
         {
             "label": "Mirantis",
	     "backgroundColor":"rgba(0,0,0,.7)",
             "data": [59, 370, 181, 250, 539, 677, 678, 778, 384, 288]
         },
         {
             "label": "Red Hat",
	     "backgroundColor":"rgba(233,52,66,.7)",
             "data": [731, 623, 852, 965, 1231, 1290, 1057, 1098, 821, 721]
         }
     ]
 },
 "options": { 
     "responsive": "true",
     "legend": {
     	"position": "bottom",
	"labels": {
	    "fontSize": 16
	}
     }
 }
}
-->
</canvas>
<br>
<sup>Source: stackalytics.com , Analysis: git.io/vQYT0 </sup>


<!-- Slide -->
##### Commits to OpenStack Optional
<sup>Aodh, Barbican, Ceilometer, Designate, Gnocchi, Heat, Horizon, Ironic, Magnum, Manila, Mistral, <br> Monasca, Murano, Panko, Rally, Sahara, Tempest, Trove, +(os-client, oslo, security, documentation)</sup>
<canvas data-chart="line">
<!--
{
 "data" : {
     "labels": ["G", "H", "I", "J", "K", "L", "M", "N", "O", "P"],
     "datasets": [
         {
             "label": "Canonical",
	     "backgroundColor":"rgba(221,72,20,.9)",
             "data": [38, 52, 8, 6, 19, 6, 7, 4, 10, 2]
         },
         {
             "label": "SUSE",
	     "backgroundColor":"rgba(125,194,70,.9)",
             "data": [16, 175, 849, 635, 345, 372, 296, 221, 319, 181]
         },
         {
             "label": "Red Hat",
	     "backgroundColor":"rgba(233,52,66,.7)",
             "data": [1091, 1567, 1707, 1451, 2232, 1938, 1561, 1660, 1291, 801]
         },
         {
             "label": "Mirantis",
	     "backgroundColor":"rgba(0,0,0,.7)",
             "data": [200, 1075, 904, 1048, 2008, 2273, 1846, 1776, 828, 373]
         }
     ]
 },
 "options": { 
     "responsive": "true",
     "legend": {
     	"position": "bottom",
	"labels": {
	    "fontSize": 16
	}
     }
 }
}
-->
</canvas>
<br>
<sup>Source: stackalytics.com , Analysis: git.io/vQYT0 </sup>


<!-- Slide -->
##### Reviews in Core and Optional
<canvas data-chart="line">
<!--
{
 "data" : {
     "labels": ["G", "H", "I", "J", "K", "L", "M", "N", "O", "P"],
     "datasets": [
         {
             "label": "Canonical",
	     "backgroundColor":"rgba(221,72,20,.9)",
             "data": [931, 196, 70, 68, 72, 31, 8, 23, 48, 15]
         },
         {
             "label": "SUSE",
	     "backgroundColor":"rgba(125,194,70,.9)",
             "data": [61, 562, 2563, 3818, 3893, 3147, 3328, 2208, 1866, 2440]
         },
         {
             "label": "Red Hat",
	     "backgroundColor":"rgba(233,52,66,.7)",
             "data": [7949, 15812, 19172, 19699, 24352, 21246, 18165, 19592, 13342, 10659]
         },
         {
             "label": "Mirantis",
	     "backgroundColor":"rgba(0,0,0,.7)",
             "data": [137, 6018, 11185, 16267, 27943, 29539, 27452, 24168, 10829, 7028]
         }
     ]
 },
 "options": { 
     "responsive": "true",
     "legend": {
     	"position": "bottom",
	"labels": {
	    "fontSize": 16
	}
     }
 }
}
-->
</canvas>
<br>
<sup>Source: stackalytics.com , Analysis: git.io/vQYT0 </sup>


<!-- Slide -->
##### Bugfix ratio in Core and Optional
<sup>resolved vs. reported bugs in %</sup>
<canvas data-chart="line">
<!--
{
 "data" : {
     "labels": ["G", "H", "I", "J", "K", "L", "M", "N", "O", "P"],
     "datasets": [
         {
             "label": "Canonical",
	     "backgroundColor":"rgba(221,72,20,.7)",
             "data": [99, 35, 48, 17, 19, 9, 30, 12, 3, 30]
         },
         {
             "label": "SUSE",
	     "backgroundColor":"rgba(125,194,70,.6)",
             "data": [94, 115, 143, 204, 145, 86, 47, 42, 40, 109]
         },
         {
             "label": "Red Hat",
	     "backgroundColor":"rgba(233,52,66,.7)",
             "data": [78, 65, 60, 56, 59, 54, 64, 74, 73, 72]
         },
         {
             "label": "Mirantis",
	     "backgroundColor":"rgba(0,0,0,.7)",
             "data": [89, 87, 63, 87, 84, 73, 70, 74, 83, 81]
         }
     ]
 },
 "options": { 
     "responsive": "true",
     "legend": {
     	"position": "bottom",
	"labels": {
	    "fontSize": 16
	}
     },
     "scales": {
     	"yAxes": [{
        	"ticks": {
                    "min": 0,
                    "max": 210
                }
            }]
     }
 }
}
-->
</canvas>
<br>
<sup>Source: stackalytics.com , Analysis: git.io/vQYT0 </sup>


<!-- Slide -->
## Ceph


##### Commits
<sup>source: metrics.ceph.com, ceph.git, 2017/16/23<sup>
<canvas class="doughnut-reveal" data-chart="doughnut" width="600" height="600">
<!--
{
 "data" : {
     "labels": ["Red Hat" , "SUSE" , "Mirantis" , "Canonical"],
     "datasets": [
         {
             "data": [36021, 1822, 746, 30],
	     "backgroundColor": [
	     	"rgba(233,52,66,.7)",
		"rgba(125,194,70,.6)",
		"rgba(0,0,0,.7)",
		"rgba(221,72,20,.7)"
	     ]
         }
     ]
 },
 "options": {
     "animateScale": "true",
     "responsive": "true",
     "legend": {
     	"position": "bottom",
	"labels": {
	    "fontSize": 16
	}
     }
 }
}
-->
</canvas>

Note: RH numbers are RH+Inktank, Canonical 30, last data: [37908, 1369, 706, 28]


<!-- Slide -->
## Kernel


<!-- Slide -->
##### Changesets 
<sup>source: linux.git, gitdm with 4.4 data set, 2016/10/20</sup>
<canvas data-chart="line">
<!--
{
 "data" : {
     "labels": ["v3.0" , "v3.1" , "v3.2" , "v3.4" , "v3.5" , "v3.6" , "v3.7" , "v3.8" , "v3.9" , "v3.10" , "v3.11" , "v3.12" , "v3.13" , "v3.14" , "v3.15" , "v3.16" , "v3.17" , "v3.18" , "v3.19" , "v4.0" , "v4.1" , "v4.2" , "v4.3" , "v4.4" , "v4.5" , "v4.6" , "v4.7" , "v4.8"],
     "datasets": [
         {
             "label": "Mirantis",
	     "backgroundColor":"rgba(0,0,0,.7)",
             "data": [0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,1,15,27,66,48,18]
         },
         {
             "label": "Canonical",
	     "backgroundColor":"rgba(221,72,20,.7)",
             "data": [24,27,46,101,35,89,90,91,84,58,81,55,48,28,25,34,32,80,23,29,24,37,30,35,46,50,56,108]
         },
         {
             "label": "SUSE",
	     "backgroundColor":"rgba(125,194,70,.6)",
             "data": [446,391,337,731,329,256,323,270,437,235,230,163,294,278,454,298,279,300,431,445,453,503,301,260,386,370,469,341]
         },
         {
             "label": "Red Hat",
	     "backgroundColor":"rgba(233,52,66,.7)",
             "data": [947,688,927,1661,926,898,1003,963,798,896,808,753,1060,1030,1133,1370,1046,854,890,669,931,1274,969,658,628,933,836,987]
         }
     ]
 },
 "options": { 
     "responsive": "true",
     "legend": {
     	"position": "bottom",
	"labels": {
	    "fontSize": 16
	}
     }
 }
}
-->
</canvas>


<!-- Slide -->
##### Changesets in Stable tree
<sup>source: linux-stable.git, gitdm with 4.4 data set, 2016/10/20</sup>
<canvas data-chart="line">
<!--
{
 "data" : {
     "labels": ["v3.0.100" , "v3.1.10" , "v3.2.82" , "v3.4.112" , "v3.5.7" , "v3.6.11" , "v3.7.10" , "v3.8.13" , "v3.9.11" , "v3.10.103" , "v3.11.10" , "v3.12.64" , "v3.13.11" , "v3.14.79" , "v3.15.10" , "v3.16.37" , "v3.17.8" , "v3.18.43" , "v3.19.8" , "v4.0.9" , "v4.1.34" , "v4.2.8" , "v4.3.6" , "v4.4.19" , "v4.5.7" , "v4.6.7" , "v4.7.8" , "v4.8.2"],
     "datasets": [
         {
             "label": "Mirantis",
	     "backgroundColor":"rgba(0,0,0,.7)",
             "data": [0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,3,1,2,17,27,66,48,18]
         },
         {
             "label": "Canonical",
	     "backgroundColor":"rgba(221,72,20,.7)",
             "data": [98,39,173,190,57,104,100,110,90,103,86,110,59,62,29,116,39,124,30,37,75,48,43,66,59,59,72,110]
         },
         {
             "label": "SUSE",
	     "backgroundColor":"rgba(125,194,70,.6)",
             "data": [690,457,850,1093,374,311,358,315,469,636,264,763,344,632,477,680,339,595,498,495,716,548,373,439,466,408,507,343]
         },
         {
             "label": "Red Hat",
	     "backgroundColor":"rgba(233,52,66,.7)",
             "data": [1403,772,1772,2341,1010,966,1083,1083,897,1593,883,1587,1172,1606,1204,1970,1181,1280,965,724,1264,1369,1014,888,728,1014,907,992]
         }
     ]
 },
 "options": { 
     "responsive": "true",
     "legend": {
     	"position": "bottom",
	"labels": {
	    "fontSize": 16
	}
     }
 }
}
-->
</canvas>


<!-- Slide -->
## KVM/libvirt


<!-- Slide -->
##### Commits
<sup>libvirt/qemu git, 2016/10/20<sup>
<canvas class="doughnut-reveal" data-chart="doughnut" width="600" height="600">
<!--
{
 "data" : {
     "labels": ["Red Hat" , "SUSE" , "Mirantis" , "Canonical"],
     "datasets": [
         {
             "data": [36781, 2698, 6, 75],
	     "backgroundColor": [
	     	"rgba(233,52,66,.7)",
		"rgba(125,194,70,.6)",
		"rgba(0,0,0,.7)",
		"rgba(221,72,20,.7)"
	     ]
         }
     ]
 },
 "options": {
     "animateScale": "true",
     "responsive": "true",
     "legend": {
     	"position": "bottom",
	"labels": {
	    "fontSize": 16
	}
     }
 }
}
-->
</canvas>

