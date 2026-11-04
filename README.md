<a href="https://esphome.io"><img align="right" src="https://img.shields.io/badge/ESPHome-Compatible-000000?style=for-the-badge&logo=esphome&logoColor=white" alt="ESPHome Compatible"></a>

# ESPHome Refoss P11

<a href="https://linktr.ee/DzurisHome"><img src="https://img.shields.io/badge/Linktree-DzurisHome-43E55E?style=for-the-badge&logo=linktree&logoColor=white" alt="Linktree"></a>
<a href="https://ko-fi.com/DzurisHome"><img src="https://img.shields.io/badge/Ko--fi-Support_me-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white" alt="Support me on Ko-fi"></a>

</br>

### How to make Refoss P11 run ESPHome

### Benefits
- Local Control
- MQTT
- Home Assistant Autodiscovery
- Web Server
- OTA Update
- Energy Monitor
- Ready-made Firmware

</br>

> [!NOTE]
> ### What You Need
>
> [Refoss P11](https://refoss.net/products/refoss-tesmota-wi-fi-plug-p11)
>
> ESPHome or [Ready-made Firmware](https://dzurishome.github.io/ESPHome-Refoss-P11/)

</br>

![Home Assistant ESPHome Integration Bedroom Radiator Socket](Images/Home%20Assistant%20ESPHome%20Integration%20Bedroom%20Radiator%20Socket.png)
![ESPHome WebServer Bedroom Radiator Socket](Images/ESPHome%20WebServer%20Bedroom%20Radiator%20Socket.png)

</br>

> [!CAUTION]
> ### Recommendations
>
> Socket [AliExpress | Refoss P11](https://s.click.aliexpress.com/e/_mPJhNKY) or [Manufacturer | Refoss P11](https://refoss.net/products/refoss-tesmota-wi-fi-plug-p11)
>
> **Ready-made Firmware** → [Firmware Installer](https://dzurishome.github.io/ESPHome-Refoss-P11/) — no ESPHome needed
>
> **Own Firmware** (built in your ESPHome) → [ESPHome Web](https://web.esphome.io/)

</br>

![Refoss P11](Images/Refoss%20P11.png)

| Refoss P11           |
|----------------------|
| ESP8266              |
| Internal Temperature |
| Energy Monitor       |

| Pin    | Inverted |                |
|--------|----------|----------------|
| GPIO3  |          | Energy Monitor |
| GPIO4  | true     | Status LED     |
| GPIO5  |          | Button         |
| GPIO12 | true     | Switch LED     |
| GPIO13 |          | Relay          |
| GPIO17 |          | ADC            |

</br>

> [!IMPORTANT]
> ### First Flash Minimal
>
> 1. Flash [Minimal Config](ESPHome%20Config/Refoss_P11_Minimal.yaml) — only Wi-Fi and OTA
> 2. Adopt it in your ESPHome and add what you want from the [Full Config](ESPHome%20Config/Refoss_P11.yaml)

</br>

### ESPHome Configs
- [Minimal](ESPHome%20Config/Refoss_P11_Minimal.yaml)
- [Refoss P11](ESPHome%20Config/Refoss_P11.yaml)

### Ready-made Firmware
[![Install Ready-made Firmware](https://img.shields.io/badge/Install-Ready--made_Firmware-03A9F4?style=for-the-badge&logo=esphome&logoColor=white)](https://dzurishome.github.io/ESPHome-Refoss-P11/)

</br>

> [!CAUTION]
> Before [Factory Reset Device](https://esphome.io/components/button/factory_reset/) read this first

| Button        |                      |
|---------------|----------------------|
| 5-10 seconds  | Restart Device       |
| 15-20 seconds | Factory Reset Device |

</br>

<a href="https://linktr.ee/DzurisHome"><img src="https://img.shields.io/badge/Linktree-DzurisHome-43E55E?style=for-the-badge&logo=linktree&logoColor=white" alt="Linktree"></a>
<a href="https://ko-fi.com/DzurisHome"><img src="https://img.shields.io/badge/Ko--fi-Support_me-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white" alt="Support me on Ko-fi"></a>
