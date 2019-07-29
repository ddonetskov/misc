Links
-----

- RHEL 8 Documentation: https://access.redhat.com/documentation/ru-ru/red_hat_enterprise_linux/8/

Install VirtualBox Guest Additions
----------------------------------

Install prerequisites

::

    dnf install kernel-devel-$(uname -r) kernel-headers perl gcc make elfutils-libelf-devel
    
Install VirtualBox Guest Additions

::

    cd /run/media/`whoami`/VB*
    ./VBoxLinuxAdditions.run
    
The installation can be checked with lsmod

::

    lsmod | grep vbox
