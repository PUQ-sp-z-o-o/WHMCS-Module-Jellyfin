# WHMCS setup(install/update)

#####  [Order now](https://puqcloud.com/whmcs-module-jellyfin.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Jellyfin/) | [FAQ](https://faq.puqcloud.com/)

<p class="callout info">To install and update a module, you must perform one and the same action.</p>

#####  

##### 1. Download the latest version of the module.

PHP 8.1

```Powershell
wget http://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Jellyfin/PUQ_WHMCS-Jellyfin-latest.zip
```

PHP 7.4

```Powershell
wget http://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Jellyfin/php74/PUQ_WHMCS-Jellyfin-latest.zip
```

<p class="callout info">All versions are available via link: [http://download.puqcloud.com/WHMCS/servers/PUQ\_WHMCS-Jellyfin/](http://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Jellyfin/)</p>

##### 2. Unzip the archive with the module.

```Powershell
unzip PUQ_WHMCS-Jellyfin-latest.zip
```

##### 3. Copy and Replace "puqJellyfin" to "WHMCS\_WEB\_DIR/modules/servers/"