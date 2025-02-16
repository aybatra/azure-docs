---
title: include
author: batamig
ms.date: 07/06/2022
ms.topic: include
---

<!-- docutune:disable -->

Defender for IoT can discover all devices, of all types, across all environments. Devices are listed in the Defender for IoT **Device inventory** pages based on a unique IP and MAC address coupling.

Defender for IoT identifies single and unique committed devices as follows:

|Committed / Not committed  |Description  |
|---------|---------|
|**Committed devices**     |    Committed devices include:<br>**IT, OT, or IoT devices with one or more NICs**, including network infrastructure devices such as switches and routers<br><br>**Note**: A device with modules or backplane components, such as racks or slots, is counted as a single device, including all modules or backplane components.|
|**Not committed devices**     | The following items *aren't* considered as committed devices:<br>**Public internet IP addresses** <br>**Multi-cast groups**<br> **Broadcast groups**<br>**Inactive devices**<br><br> Network-monitored devices are marked as *inactive* when there's no network activity detected within a specified time:<br> - **OT networks**: No network activity detected for more than 60 days<br> - **Enterprise IoT networks**: No network activity detected for more than 30 days<br><br>**Microsoft Defender for Endpoint** (For customers with [Microsoft Defender for Endpoint Plan 2](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#microsoft-defender-for-endpoint)): For subscriptions [onboarded for Enterprise IoT networks](/microsoft-365/security/defender-endpoint/enable-microsoft-defender-for-iot-integration), endpoints managed by Defender for Endpoint are not considered committed devices.  |
