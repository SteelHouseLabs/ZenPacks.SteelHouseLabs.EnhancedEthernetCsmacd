===============================================================================
ZenPacks.SteelHouseLabs.EnhancedEthernetCsmacd
===============================================================================

About
-------------------------------------------------------------------------------
This ZenPack dramatically improves the /Network/etherCscmacd, /Network/etherCscmacd_64 and /Devices/etherCscmacd tempaltes.


Features
-------------------------------------------------------------------------------
This ZenPack dramatically improves the /Network/etherCscmacd, /Network/etherCscmacd_64 and /Devices/etherCscmacd tempaltes.
!!!It does not delete the stock templates!!!

Prerequisites
-------------------------------------------------------------------------------

==================  =========================================================
Prerequisite        Restriction
==================  =========================================================
Product             Zenoss 4.1.1 or higher
Required ZenPacks   None
Other dependencies  None
==================  =========================================================


Limitations
-------------------------------------------------------------------------------
None


Usage
-------------------------------------------------------------------------------
!!!It does not delete the stock templates!!!


Installing
-------------------------------------------------------------------------------

Install the ZenPack via the command line and restart Zenoss::

    It's reccomended to zenbackup --no-perfdata --no-eventdb and to remove the 
    stock /Network/etherCscmacd, /Network/etherCscmacd_64 and /Devices/etherCscmacd tempaltes before you begin.
    
    zenpack --link --install ZenPacks.SteelHouseLabs.EnhancedEthernetCsmacd-<version>.egg
    zenoss restart


Removing
-------------------------------------------------------------------------------

To remove the ZenPack, use the following command::

    zenpack --remove ZenPacks.SteelHouseLabs.EnhancedEthernetCsmacd
    zenoss restart
    
    You'll need to restore the default templates.
