# ESPHome Config Refoss P11

## [LinkTree](https://linktr.ee/DzurisHome)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/N4N6M7OX3)

</br>

*****[Refoss P11 | Aliexpress](https://s.click.aliexpress.com/e/_mPJhNKY)*****

*****[Manufacturer | Refoss P11](https://refoss.net/products/refoss-tesmota-wi-fi-plug-p11)*****

</br>

| Refoss P11           |
|----------------------|
| ESP8266              |
| Internal Temperature |
| Energy Monitor       |

</br>

| Pin    |                |                      |
| ------ | -------------- | ---------------------|
| GPIO3  |                | Power Monitoring     |
| GPIO4  | inverted: true | Status Led           |
| GPIO5  |                | Button               |
| GPIO12 | inverted: true | Switch Led           |
| GPIO13 |                | Relay                |
| GPIO17 |                | Internal Temperature |

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

### ESPHome Config
- [Refoss P11](https://github.com/DzurisHome/ESPHome-Config-Refoss-P11/blob/main/ESPHome%20Config/Refoss%20P11.yaml)

### ESPHome Firmware
- SOON

</br>

![ESPHome WebServer Bedroom Radiator Socket](https://github.com/DzurisHome/ESPHome-Config-Refoss-P11/blob/main/Images/ESPHome%20WebServer%20Bedroom%20Radiator%20Socket.png)
![Home Assistant ESPHome Integration Bedroom Radiator Socket](https://github.com/DzurisHome/ESPHome-Config-Refoss-P11/blob/main/Images/Home%20Assistant%20ESPHome%20Integration%20Bedroom%20Radiator%20Socket.png)
![Refoss P11 Plug](https://github.com/DzurisHome/Tasmota-Template-Refoss-P11/blob/main/Refoss%20P11%20Plug.jpg)

## [LinkTree](https://linktr.ee/DzurisHome)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/N4N6M7OX3)
