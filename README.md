# Openshift 4.3

Installation of Red Hat OpenShift Container Platform 4.3 (OCP) using the following sample documents 
* https://labs.consol.de/container/platform/openshift/2020/01/31/ocp43-installation-vmware.html  
* https://servicesblog.redhat.com/2019/07/11/installing-openshift-4-1-using-libvirt-and-kvm/

## Basic BIG-IP LB setup
This configuration will add the following load balancer entries to the F5 BIG-IP using AS3:

* openshift-api-server (port 6443)
* machine-config-server (port 22623)

It will also create DNS records using BIG-IP DNS

* BIG-IP OpenShift API configuration [example](lb-ocp4-3-api.json)
* [FAST template example](fast)




