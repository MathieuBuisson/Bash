DESCRIPTION :

Script to automate the steps mentioned in the KB article : http://kb.vmware.com/kb/2037952

Resets the Inventory Service database and restarts the vCenter Server Service

USAGE :

Before doing anything, it displays a warning explaining that Storage Profiles and vCenter tags will be lost.
It will continue only if you type "Y" at the confirmation prompt.

It detects the vCenter version and runs the appropriate commands accordingly, so it works with vCenter Appliance 5.0, 5.1 and 5.5.

It needs to be run locally on the vCenter Appliance and as root.

The error handling is pretty basic : if a command fails, the script tells you which step failed and exits.
