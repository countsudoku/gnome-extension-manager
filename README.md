# gnome-extension-manager

This application should manage the extensions for gnome-shell in the user space. Therefore it should download and install extensions from [the gnome extensions website][extensions gnome] or from the extension git repo. The most commands are the same as for apt-get on debian based Linux distributions

The following commndas are planed:
* install  
    download the plugin and installed it in the right location
* update  
    update the local extension catalog
* upgrade  
    check for outdated plugins and update them
* activate  
    Activate the extension
* deactivate  
    deactivate a extension
* remove  
    deactivate and deinstall the plugin
* purge  
    deinstall the plugin and remove the configuration

[extensions gnome]: extensions.gnome.org
