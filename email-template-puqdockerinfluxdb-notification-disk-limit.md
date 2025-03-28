# Email Template (puqDockerInfluxDB Notification disk limit)

### Docker InfluxDB module **[WHMCS](https://puqcloud.com/link.php?id=77)** 

#####  [Order now](https://puqcloud.com/whmcs-module-docker-influxdb.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-InfluxDB/) | [FAQ](https://faq.puqcloud.com/) | [n8n](https://puqcloud.com/link.php?id=117)

##### Create an email template for customer notifications.

```
System Settings->Email Templates->Create New Email Template
```

- **Email Type:** Product/service
- **Unique Name:** puqDockerInfluxDB Notification disk limit

[![image-1742771428968.png](https://doc.puq.info/uploads/images/gallery/2025-03/scaled-1680-/image-1742771428968.png)](https://doc.puq.info/uploads/images/gallery/2025-03/image-1742771428968.png)

**Subject:**

```
Disk space usage {$disk_used_percentage}%
```

**Body:**

```
Dear {$client_name},

We want to inform you that your InfluxDB service is running low on disk space. 
Please take action to prevent service interruptions.

Service Details:

Product/Service: {$service_product_name}
Domain: {$service_domain}
Total Disk Space: {$disk_total}
Used Disk Space: {$disk_used} ({$disk_used_percentage}%)
Consider freeing up space or upgrading your plan if needed.

{$signature}
```

[![image-1742771475552.png](https://doc.puq.info/uploads/images/gallery/2025-03/scaled-1680-/image-1742771475552.png)](https://doc.puq.info/uploads/images/gallery/2025-03/image-1742771475552.png)