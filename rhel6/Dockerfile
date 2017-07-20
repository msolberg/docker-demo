FROM registry.access.redhat.com/rhel6
MAINTAINER Michael Solberg msolberg@redhat.com

# Grab latest updates
RUN yum -y install yum-utils && yum clean all && yum-config-manager --disable \*-htb-* \*-rt-* \*-eus* \*-ha-*
RUN yum -y update && yum clean all
