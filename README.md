# ESPHome Refoss P11 <a href="https://esphome.io"><img align="right" src="Images/Buttons/ESPHome-Compatible.svg" height="48" alt="Compatible with ESPHome"></a>

<a href="https://linktr.ee/DzurisHome"><img src="Images/Buttons/Linktree.svg" height="36" alt="Find me on Linktree"></a>&nbsp;
<a href="https://ko-fi.com/DzurisHome"><img src="https://ko-fi.com/img/githubbutton_sm.svg" height="36" alt="Support me on Ko-fi"></a>

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

<img src="Images/Home%20Assistant%20ESPHome%20Integration%20Bedroom%20Radiator%20Socket.png" height="575" alt="Home Assistant ESPHome Integration Bedroom Radiator Socket"> <img src="Images/ESPHome%20WebServer%20Bedroom%20Radiator%20Socket.png" height="575" alt="ESPHome WebServer Bedroom Radiator Socket">

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

<img src="Images/Refoss%20P11.png" height="548" alt="Refoss P11">

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

### Firmware
<a href="https://dzurishome.github.io/ESPHome-Refoss-P11/"><img src="Images/Buttons/Ready-made-Firmware.svg" width="374" alt="Install Ready-made Firmware"></a>

</br>

> [!CAUTION]
> Before [Factory Reset Device](https://esphome.io/components/button/factory_reset/) read this first

| Button        |                      |
|---------------|----------------------|
| 5-10 seconds  | Restart Device       |
| 15-20 seconds | Factory Reset Device |

</br>

<a href="https://linktr.ee/DzurisHome"><img src="Images/Buttons/Linktree.svg" height="36" alt="Find me on Linktree"></a>&nbsp;
<a href="https://ko-fi.com/DzurisHome"><img src="https://ko-fi.com/img/githubbutton_sm.svg" height="36" alt="Support me on Ko-fi"></a>
