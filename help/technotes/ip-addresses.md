---
title: IPs and domains used by Adobe Analytics
description: If your organization's firewall blocks IP addresses that originate from Adobe, use this list to update your firewall settings.
exl-id: e24a70e4-9ed4-4b87-8bab-4ed0aebedd1f
---
# IPs and domains used by Adobe Analytics

Some firewall configurations block IP addresses originating from Adobe's data collection servers or servers responsible for accessing data. You can use this list of ranges to alter your organization's firewall settings to allow access and to send data from within your organization.

>[!IMPORTANT]
>
>While Adobe does its best to keep this document current, it cannot guarantee the list of IP ranges remain the same. Possible changes include growth and expansion of the business, an internet registry requires changes to Adobe's IP address space, or an internet service provider stops functioning.

## Allow dependent technology domains

Adobe Analytics uses the following hosts to improve performance and product experience. Adobe recommends adding these domains to your firewall's allowed list for an optimal experience using Adobe Analytics.

| Technology | Domain |
| --- | --- |
| Adobe Analytics domains | `adobe.com`, `adobe.net`, `adobe.io` |
| Adobe Analytics legacy domain | `omniture.com` |
| Amazon AWS | `aaui-879784980514.s3.us-east-2.amazonaws.com` |
| Amazon CloudFront | `d30ln29764hddd.cloudfront.net` |
| Gainsight | `esp.aptrinsic.com`, `esp-m.aptrinsic.com` |
| LaunchDarkly | `app.launchdarkly.com` |
| Microsoft Azure Blob Storage | `awaascicdprodva7.blob.core.windows.net` |
| Microsoft Azure CDN | `aauicdnva7.azureedge.net` |

## All Adobe Analytics Data Collection IP address blocks

The following table covers all standard data collection servers and regional data collection servers for Adobe Analytics. They do not include individual AWS hosts.

| IP Block (CIDR Notation) |
| --- |
| `63.140.32.0/19` |
| `66.117.16.0/20` |
| `66.235.128.0/19` |
| `130.248.0.0/16` |
| `172.82.192.0/18` |
| `185.34.188.0/22` |
| `192.243.224.0/19` |
| `205.219.231.0/24` |
| `208.67.40.0/22` |
| `208.77.136.0/22` |

## Data collection and FTP IP address blocks

If your organization prefers to allow specific IP address ranges you can use the following table. All of the ranges in this section are included in the above table. FTP connections for Data Warehouse and Data Feeds only originate from the London, Oregon, and Singapore locations.

| Location | IP Range (CIDR Notation) |
| --- | --- |
| Amsterdam | `66.117.28.0/23` |
| Dallas | `205.219.231.0/24` |
| Dallas | `66.235.152.0/22` |
| Dallas | `66.235.140.0/22` |
| Dallas | `63.140.32.0/21` |
| Dallas | `172.82.208.0/22` |
| Hong Kong SAR of China | `66.117.24.0/22` |
| London | `66.235.156.0/24` |
| London | `66.235.148.0/23` |
| London | `63.140.40.0/22` |
| London | `208.67.41.0/24` |
| London | `192.243.254.0/23` |
| London | `192.243.244.0/22` |
| London | `185.34.188.0/23` |
| London | `130.248.152.0/21` |
| London | `172.82.224.0/21` |
| London | `172.82.232.0/21` |
| Oregon | `192.243.240.0/22` |
| Oregon | `192.243.232.0/21` |
| Oregon | `192.243.224.0/21` |
| Oregon | `130.248.160.0/21` |
| Oregon | `130.248.148.0/22` |
| Oregon | `172.82.192.0/21` |
| Oregon | `172.82.216.0/21` |
| Paris | `208.67.40.0/24` |
| Singapore | `66.235.150.0/24` |
| Singapore | `66.235.130.0/23` |
| Singapore | `63.140.44.0/22` |
| Singapore | `208.67.43.0/24` |
| Singapore | `172.82.240.0/22` |
| Singapore | `172.82.246.0/23` |
| Singapore | `172.82.248.0/21` |
| San Jose | `66.117.20.0/24` |
| San Jose | `66.235.132.0/22` |
| San Jose | `130.248.128.0/22` |
| San Jose | `192.243.248.0/23` |
| San Jose | `172.82.200.0/22` |
| San Jose | `66.235.136.0/22` |
| San Jose | `208.91.175.0/24` |
| San Jose | `208.91.174.0/24` |
| San Jose | `208.91.169.0/24` |
| Sydney | `216.104.216.0/23` |
| Tokyo | `66.235.159.0/24` |
| Tokyo | `66.117.21.0/24` |
| Tokyo | `63.140.52.0/24` |
| Tokyo | `63.140.50.0/23` |
| Virginia | `66.235.144.0/22` |
| Virginia | `208.77.138.0/23` |
| Virginia | `208.77.136.0/23` |
| Virginia | `192.243.250.0/23` |
| Virginia | `130.248.144.0/22` |
| Virginia | `172.82.204.0/22` |
| Virginia | `172.82.212.0/22` |
| Virginia | See AWS Hosts |

## AWS hosts

Adobe Analytics uses Amazon Web Services as part of its data collection process. The following table includes AWS hosts reserved for Adobe. These hosts are **not** included in the aggregate block range above.

| Location | Host |
| --- | --- |
| Australia | `13.54.219.183` |
| Australia | `52.62.137.88` |
| Australia | `54.79.162.112` |
| China | `52.81.111.133` |
| China | `140.179.22.22` |
| France | `13.36.218.177` |
| France | `15.188.95.229` |
| France | `15.236.176.210` |
| India | `3.7.24.204` |
| India | `3.108.50.194` |
| India | `3.108.177.136` |
| Ireland | `54.220.133.225` |
| Ireland | `54.74.170.177` |
| Ireland | `54.195.254.128` |
| Oregon | `54.212.155.93` |
| Oregon | `52.10.149.115` |
| Oregon | `52.40.172.46` |
| Singapore | `54.255.88.178` |
| Singapore | `52.220.235.10` |
| Singapore | `3.1.237.132` |
| Tokyo | `3.113.78.189` |
| Tokyo | `13.115.137.161` |
| Tokyo | `54.178.162.114` |
| Virginia | `18.205.241.19` |
| Virginia | `44.194.25.77` |
| Virginia | `52.0.93.32` |
| Virginia | `3.216.131.23` |
| Virginia | `34.204.237.47` |
| Virginia | `54.163.234.74` |
