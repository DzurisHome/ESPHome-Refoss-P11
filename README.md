# ESPHome Refoss P11

## [LinkTree](https://linktr.ee/DzurisHome)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/DzurisHome)

</br>

*****[Aliexpress | Refoss P11](https://s.click.aliexpress.com/e/_mPJhNKY)*****

*****[Manufacturer | Refoss P11](https://refoss.net/products/refoss-tesmota-wi-fi-plug-p11)*****

</br>

| Refoss P11           |
|----------------------|
| ESP8266              |
| Internal Temperature |
| Energy Monitor       |

</br>

| Pin    | Inverted |                      |
| ------ | -------- | ---------------------|
| GPIO3  |          | Energy Monitor       |
| GPIO4  | true     | Status Led           |
| GPIO5  |          | Button               |
| GPIO12 | true     | Switch Led           |
| GPIO13 |          | Relay                |
| GPIO17 |          | Internal Temperature |

</br>

> [!IMPORTANT]
> First Flash [Tasmota Minimal Firmware](http://ota.tasmota.com/tasmota/release/tasmota-minimal.bin.gz) and then ESPHome Firmware	

</br>

### ESPHome Config
- [Refoss P11](https://github.com/DzurisHome/ESPHome-Config-Refoss-P11/blob/main/ESPHome%20Config/Refoss%20P11.yaml)

```
logger:
  baud_rate: 0

uart:
  rx_pin: GPIO03
  baud_rate: 4800
  id: power_monitoring

sensor:
  - platform: cse7766
    uart_id: power_monitoring

sensor:
  - platform: adc
    pin: GPIO17
```

</br>

### ESPHome Firmware
- [Refoss P11](https://github.com/DzurisHome/ESPHome-Refoss-P11/blob/main/ESPHome%20Firmware/Refoss%20P11.bin)

| WiFi AP  |                           |
|----------|---------------------------|
| SSID     | Refoss P11 Dzuriš Home AP |
| Password | dzurishome                |

| Web Server |            |
|------------|------------|
| Username   | dzurishome |
| Password   | dzurishome |

> [!IMPORTANT]
> Before [Factory Reset Device](https://esphome.io/components/button/factory_reset.html?highlight=factory_reset) read this first

| Button        |                      |
|---------------|----------------------|
| 5-10 seconds  | Restart Device       |
| 15-20 seconds | Factory Reset Device |

</br>

![Home Assistant ESPHome Integration Bedroom Radiator Socket](https://github.com/DzurisHome/ESPHome-Config-Refoss-P11/blob/main/Images/Home%20Assistant%20ESPHome%20Integration%20Bedroom%20Radiator%20Socket.png)
![ESPHome WebServer Bedroom Radiator Socket](https://github.com/DzurisHome/ESPHome-Config-Refoss-P11/blob/main/Images/ESPHome%20WebServer%20Bedroom%20Radiator%20Socket.png)
![Refoss P11](https://github.com/DzurisHome/ESPHome-Config-Refoss-P11/blob/main/Images/Refoss%20P11.png)

## [LinkTree](https://linktr.ee/DzurisHome)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/DzurisHome)
