# zabbix-templates
Templates for Zabbix (currently 6.4)

${\textsf{\color{orange}Contributions welcome!}}$

## ${\textsf{\color{blue}Fritz!Box UPnP}}$

Set macro ``{$FRITZ.USERNAME}`` and ``{$FRITZ.PASSWORD}`` and enter valid credentials.

Set the appropriate permissions for the user.

> [!Note]
> Interface documentation: https://avm.de/service/schnittstellen

> [!Tip]
> I recommend to use a specific user for monitoring.
> 
> You should only enable the items you really need to not raise CPU utilization.

Tested with FB7430 and FB7590.

## ${\textsf{\color{blue}Lupussec XT alarm central}}$

Set macro ``{$LUPUS.USERNAME}`` and ``{$LUPUS.PASSWORD}`` and enter valid credentials.

> [!Tip]
> I recommend to use a specific user for monitoring.

Tested with Lupus XT2-Plus.

## ${\textsf{\color{blue}Homematic CCU}}$

> [!Important]
> You need to install the addon ``XML-API`` on your CCU.

Set macro ``{$CCU.SID}`` and enter a valid security token.

Tested with CCU3.
