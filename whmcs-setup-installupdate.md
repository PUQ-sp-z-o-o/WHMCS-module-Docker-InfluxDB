# WHMCS setup (install/update)

### Docker InfluxDB module **[WHMCS](https://puqcloud.com/link.php?id=77)** 

#####  [Order now](https://puqcloud.com/whmcs-module-docker-influxdb.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-InfluxDB/) | [FAQ](https://faq.puqcloud.com/) | [n8n](https://puqcloud.com/link.php?id=117)

<p class="callout info">**Module is coded ionCube v13**</p>

Supported php version:

- php 7.4 WHMCS 8.11.0 -
- php 8.1 WHMCS 8.11.0 +
- php 8.2 WHMCS 8.11.0 +

<p class="callout info">To install and update a module, you must perform one and the same action.</p>

#####   
1. Download the latest version of the module.

PHP 8.2

```Powershell
wget http://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-InfluxDB/php82/PUQ_WHMCS-Docker-InfluxDB-latest.zip
```

PHP 8.1

```Powershell
wget http://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-InfluxDB/php81/PUQ_WHMCS-Docker-InfluxDB-latest.zip
```

PHP 7.4

```Powershell
wget http://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-InfluxDB/php74/PUQ_WHMCS-Docker-InfluxDB-latest.zip
```

<p class="callout info">All versions are available via link: [https://download.puqcloud.com/WHMCS/servers/PUQ\_WHMCS-Docker-InfluxDB/](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-InfluxDB/)</p>

##### 2. Unzip the archive with the module.

```Powershell
unzip PUQ_WHMCS-Docker-InfluxDB-latest.zip
```

##### 3. Copy and Replace "puqDockerInfluxDB" from "PUQ\_WHMCS-Docker-InfluxDB" to "WHMCS\_WEB\_DIR/modules/servers/"