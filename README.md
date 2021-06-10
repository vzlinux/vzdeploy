# vzdeploy
Convert Virtuozzo containers and VMs from CentOS to VzLinux

vzdeploy8 script should be launched inside CentOS 8 machine (bare metal, virtual machine or container).
It will replace CentOS repositories with VzLinux ones and replace the packages.
Internet access is required for the script to work.

Latest released version of vzdeploy8 is always located here: http://repo.virtuozzo.com/vzlinux/vzdeploy/vzdeploy8

vzcronvert8 is intended to be launched from Virtuozzo Hybrid Server 7 node to convert a bunch of Vz containers.
Conversion is performed by means of the vzpkg tool and doesn't require containers to have diret Internet connection.
