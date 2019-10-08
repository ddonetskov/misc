Links
-----

- RHEL 8 Documentation: https://access.redhat.com/documentation/ru-ru/red_hat_enterprise_linux/8/

Assumption
----------

A virtual machine was prepared with RHEL 8 with the Developer subscription.


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


Configure Guest as Service
--------------------------

It is possible to configure a VB guest on Windows as a service (or just in a background) with few options

- Windows Task Scheduler: https://www.windowscentral.com/how-create-automated-task-using-task-scheduler-windows-10
- sc create: https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/sc-create
- New-Service: https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.management/new-service?view=powershell-7
- `NSSM <https://nssm.cc/>`_.
