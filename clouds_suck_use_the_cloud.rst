.. transition:: tilt
   :duration: 0.4

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


Amazon problems
===============

* EIP
  * Hot Potato
  * New EIP could have DNS pointed to it

* EBS
  * Amazon grip of death
  * Volume Pre-Warming

* ELB
  * Pre-Warming ELB
  * Autoscaling - ip changes (syslog-ng)
  * bare domains

* Outages
  * Instance Failure
    * "Your instance will reboot at ..."
    * "Your instance is scheduled for retirement..."
  * Rack Failure
  * AZ Failure
  * Region Failure

* Human error
  * One command to bring down your stack
  * Commiting creds to github, etc

* Dealing with scale
  * Noisy Neighbors
  * Launch failures
    * API failure
    * DNS failures
    * system tests


OpenStack Problems
==================


* Differences between clouds
  * API differences
  * Authentication Service differences
* Network failures
  * DNS
  * Conntrak
  * Co-location of 'routers'
* Storage
  * Cinder same-host-raid
* Slow
  * Whyyyyyy
* API Calls get slower as time goes on
  * Whyyyyy
* "Your instance will reboot at ..."
* Annoying Rackspace issue system
* Image uploads
* Floating Ips, or Not
* Manual Network Creation


Why you should use a cloud
==========================


* On Demand Resources
* Autoscaling
* Decentralized Team
* Not having to deal with hardware
* Hardware refreshed by Provider
* Future has new tech in it (containers)
* Cloud security team
  * Xen Vuln
  * DMCA
  * Network security
  * Compliance
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



Summary
=======

* Test where the risk is
* Break infra into chunks, test those
* Follow the patterns from developers
* Be aware of the infra underneath you
* Code review everything


Questions
=========
.. transition:: tilt

Spencer Krum

* Engineer at IBM
* Former CAT
* OpenStack and Puppet contributor 
* @nibalizer on pretty much everything

