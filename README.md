The only change to original source is that it applies the highlight to nodes that are down. So clicking DepMap will show you whats down and how it depends on others

Dependency Map
===========

To install this into your LibreNMS installation please do the following:

1. Navigate to your LibreNMS plugin folder, e.g:

    cd /opt/librenms/html/plugins/
    
2. Clone this git repo:

    git clone https://github.com/blizko/DepMap.git
    
3. Activate the plugin:
	
	From your LibreNMS Plugins menu, select "Plugin Admin".

4. On the "Plugin Admin":
	
	Click on "Enable" next to the "DepMap" plugin.

5. To use this plugin, browse to the LibreNMS "Plugins" menu and select "Dependency Map".
