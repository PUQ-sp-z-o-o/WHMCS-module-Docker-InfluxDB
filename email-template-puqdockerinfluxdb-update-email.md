# Email Template (puqDockerInfluxDB Update Email)

### Docker InfluxDB module **[WHMCS](https://puqcloud.com/link.php?id=77)** 

#####  [Order now](https://puqcloud.com/whmcs-module-docker-influxdb.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-InfluxDB/) | [FAQ](https://faq.puqcloud.com/) | [n8n](https://puqcloud.com/link.php?id=117)

##### Create an email template for customer notifications.

```
System Settings->Email Templates->Create New Email Template
```

- **Email Type:** Product/service
- **Unique Name:** puqDockerInfluxDB Update Email

[![image-1742771309734.png](https://doc.puq.info/uploads/images/gallery/2025-03/scaled-1680-/image-1742771309734.png)](https://doc.puq.info/uploads/images/gallery/2025-03/image-1742771309734.png)

**Subject:**

```
InfluxDB Update Information
```

**Body:**

```
Dear {$client_name},

Your instance is currently being updated.
You will be able to use your InfluxDB server again within 3 minutes.

Here is the link to your InfluxDB server.

https://{$service_domain}/
Thank you for choosing us.

{$signature}
```

[![image-1742771350291.png](https://doc.puq.info/uploads/images/gallery/2025-03/scaled-1680-/image-1742771350291.png)](https://doc.puq.info/uploads/images/gallery/2025-03/image-1742771350291.png)