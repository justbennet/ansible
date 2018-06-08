# ansible
Holding Pen

Scott and Bennet will make images for Vagrant and VirtualBox for Ubuntu 18.04 server and desktop to use as the core development image.  We'll put the files in a public location.



* Audit Ansible from Florian with local copy
    + section 1 Bennet
    + section 2 David 
    + section 3 Estes
    + section 4 Scott and Bennet
    + section 5 Adam and Mark
    + section 6 Dakota

Once we get GitLab, create the Ansible repository, CIS to GitLab.

* ldap configuration
* sssd authorization configuration setup . (groups and user assignment?)
* umich kerberos (?) .- or LDAP authentication, too?
* chrony vs ntp?  Use the default.  No superfluous backports.  -- David
* ufw / firewalld (COE)
* fail2ban / denyhosts
* NetworkManager / NetPlan
* LVM / Luks
* Packer based image creation
* Preseed summit, maybe .iso rerolling
* Splunk setup
* SELinux (Dakota and David)
* AFS

* Local Ubuntu mirror(s) and management re security patches, etc.

* Monitoring
    swap, CPU, disk space, firewall activity? failed auths

* AD deferred (forever?)
