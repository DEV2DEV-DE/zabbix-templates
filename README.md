# zabbix-templates
Templates for Zabbix (currently 6.4)

## Fritz!Box UPnP

Set macro ``{$FRITZ.USERNAME}`` and ``{$FRITZ.PASSWORD}`` and enter valid credentials.

Set the appropriate permissions for the user.

I recommend to use a specific user for monitoring.

Tested with FB7430 and FB7590.

### Links

Interface documentation: https://avm.de/service/schnittstellen/#c9644

## Lupussec XT alarm central

Set macro ``{$LUPUS.USERNAME}`` and ``{$LUPUS.PASSWORD}`` and enter valid credentials.

I recommend to use a specific user for monitoring.

Tested with Lupus XT2-Plus.

## Homematic CCU

Requirements: You need to install the addon ``XML-API`` on your CCU.

Set macro ``{$CCU.SID}`` and enter a valid security token.

Tested with CCU3.

# Contributions welcome!
