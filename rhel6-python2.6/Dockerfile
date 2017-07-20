FROM rhel6-latest:latest
MAINTAINER Michael Solberg msolberg@redhat.com

# Grab latest updates
RUN yum -y localinstall http://dl.fedoraproject.org/pub/epel/6/x86_64/epel-release-6-8.noarch.rpm
RUN yum -y install python-virtualenv python-pip && yum clean all
