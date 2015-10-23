.. transition:: tilt
   :duration: 0.4


Clouds Suck use the Cloud
=========================

SeaGL October 2015

Slides: http://tinyurl.com/clouds-suck


Clouds Suck use the Cloud
=========================
.. transition:: tilt

Spencer Krum

* Engineer at IBM
* Former CAT
* OpenStack and Puppet contributor 
* @nibalizer on pretty much everything

Clouds Suck use the Cloud
=========================
.. transition:: tilt

William Van Hevelingen

* Engineer at Acquia
* Former CAT
* Author and Puppet Contributor
* @pdx_blkperl on twitter


Clouds Suck
===========

Brief Overview

Definition of 'cloud'


Definition of Terms
===================

* Cloud
* API
* Instance
* TLA


How cloud is used in our jobs
=============================


Why you should listen to us


Amazon problems - EC2
=====================


* Instance Failure

 * "Your instance will reboot at ..."
 * "Your instance is scheduled for retirement..."
 * Instance status is impaired
 * Instance system_status is impaired
 * Instance fails to terminate

* Rack Failure
* AZ Failure
* Region Failure


Amazon problems - Network
=========================


* A small number of machines missing checks
* AZ1 can't talk to AZ2
* Everyone on Verizon can't reach the cloud

Amazon problems - EIP
=====================

* Hot Potato
* New EIP could have DNS pointed to it

Amazon problems - EBS
=====================


* Amazon grip of death
* Volumes not attaching/detaching
* Volume Pre-Warming
..     - http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-prewarm.html

 * Performance

..     - http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSPerformance.html

Amazon problems - ELB
=====================



* Pre-Warming ELB
..      http://aws.amazon.com/articles/1636185810492479#pre-warming

* Autoscaling - ip changes (syslog-ng)
* bare domains

Amazon problems - Human Error
=============================


* One command to bring down your stack
* Commiting creds to github, etc

Amazon problems - Scale
=======================


* Noisy Neighbors
* Launch failures

  * API failure
  * DNS failures
  * system tests

    * cleanup is hard

Amazon problems
===============


* Pay for the whole hour


OpenStack Problems
==================


* Differences between clouds

  * API differences
  * Authentication Service differences

OpenStack problems - Network
============================


* DNS
* Conntrak
* Co-location of 'routers'


OpenStack problems - Storage
============================

* Cinder same-host-raid


OpenStack problems
==================


* Slow

  * Whyyyyyy

* API Calls get slower as time goes on

  * Whyyyyy

OpenStack problems
==================

* "Your instance will reboot at ..."
* Annoying Rackspace issue system

OpenStack problems
==================

* Image uploads

OpenStack problems
==================

* Floating Ips, or Not

OpenStack problems
==================

* Manual Network Creation


Why you should use a cloud
==========================

The cost of change goes down

Why you should use a cloud - Developers
=======================================

* Quick boot vm
* Destroy vm after breaking it
* Same 'gear' for each dev
* Same 'gear' in prod
* Staging is real

Why you should use a cloud - Sysops
===================================

* On Demand Resources
* Autoscaling
* File/git driven infrastructure
* Decentralized Team
* Not having to deal with hardware


Why you should use a cloud - Sysops
===================================


* Hardware refreshed by Provider
* Future has new tech in it (containers)
* Cloud security team

 * Xen Vuln
 * DMCA
 * Network security
 * Compliance


Why you should use a cloud
==========================

For Sysops

* Integrations
* DBaaS and other \*aaS

 * DNS

* Object Store


Hot Topics in Cloud
===================

* Terraform
* ECS / nova-docker
* IoT
* MachineLearning
* CloudFoundry
* "Cloud Native"
* Is the cloud secure?


Questions
=========
.. transition:: tilt

SeaGL October 2015

Spencer Krum & William Van Hevelingen

@nibalizer / @pdx_blkperl

Slides: http://tinyurl.com/clouds-suck
