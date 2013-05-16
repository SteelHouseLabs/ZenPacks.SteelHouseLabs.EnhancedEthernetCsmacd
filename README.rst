===============================================================================
ZenPacks.SteelHouseLabs.EnhancedEthernetCsmacd
===============================================================================


About
-------------------------------------------------------------------------------
This ZenPack dramatically improves the /Network/etherCscmacd, 
/Network/etherCscmacd_64 and /Devices/etherCscmacd tempaltes.


Features
-------------------------------------------------------------------------------
This ZenPack dramatically improves the /Network/etherCscmacd, 
/Network/etherCscmacd_64 and /Devices/etherCscmacd templates.

It does not delete the stock templates


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

Remove the stock /Network/etherCscmacd, /Network/etherCscmacd_64 and 
/Devices/etherCscmacd templates before you begin.


Installing
-------------------------------------------------------------------------------

Install the ZenPack via the command line and restart Zenoss::

    git clone git://github.com/Hackman238/ZenPacks.SteelHouseLabs.EnhancedEthernetCsmacd.git  
    zenpack --link --install ZenPacks.SteelHouseLabs.EnhancedEthernetCsmacd
    zenoss restart


Removing
-------------------------------------------------------------------------------

To remove the ZenPack, use the following command::

    zenpack --remove ZenPacks.SteelHouseLabs.EnhancedEthernetCsmacd
    zenoss restart

You'll need to restore the default templates.
