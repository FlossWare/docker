FROM centos

RUN yum -y install epel-release http://li.nux.ro/download/nux/dextop/el7/x86_64/nux-dextop-release-0-5.el7.nux.noarch.rpm http://linuxdownload.adobe.com/linux/x86_64/adobe-release-x86_64-1.0-1.noarch.rpm flash-plugin && yum install -y flash-plugin icedtea-web firefox tigervnc-server fvwm && yum clean all && /bin/dbus-uuidgen > /etc/machine-id 
