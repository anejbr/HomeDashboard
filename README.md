# HomeDashboard

Nadzorna plošča za uporavljanje naprav in spremljanje stanja v hiši.

## [WiFi SonOff termostat TH16 + Senzor](https://www.wlan-sat.com/wifi-sonoff-termostat-th16-senzor)

- Upravljanje preko omrežja (Wi-Fi)
- Vgrajeno stikalo
- Senzor za temperaturo in vlago
- Temelji na ESP32

## [ESPTool](https://github.com/espressif/esptool?tab=readme-ov-file)

ESPTool je odprtokodno orodje za komunikacijo z ESP čipi preko USB povezave. Gre za ukaznovrstično orodje, napisano v Pythonu.

- Redno vzdževano
- Pridobivanje informacij o napravi
- Brisanje in zapis flash pomnilnika

### erase flash

![ha_dashboard](./docs/flash_memory_erase.png)
### write flash

![write_flash](./docs/write_flash.png)

![setup](./docs/setup.png)

## [Tasmota](https://github.com/arendst/Tasmota/tree/development)
Tasmota je odprtokodni firmware za pametne IoT naprave (ESP8266/ESP32), ki omogoča lokalni nadzor in enostavno integracijo z domačo avtomatizacijo.

### Prednosti

- Odprtokodna
- Lokalno delovanje
- Vgrajen spletni vmesnik

### Slabosti

- Zahtevna namestitev
- Ni za vse naprave (samo ESP8266 / ESP32)

### Licenca

GPL-3.0 – odprtokodna licenca, ki zahteva objavo izpeljank pod isto licenco ter dostopnost izvorne kode.

![setup](./docs/connecting_to_network.png)
![setup](./docs/configure_switch.png)
![setup](./docs/tasmota_interface.png)

### MQTT
Lahek komunikacijski protokol, za pošiljanje sporočil med IoT napravami.

![setup](./docs/mqtt_tasmota.png)

## [Home Assistant](https://github.com/home-assistant)

Home Assistant je odprtokodna platforma za avtomatizacijo pametnega doma. Omogoča povezovanje in uporavljanje različnih pametnih naprav iz enega mesta.

- Podpora za MQTT
![mqtt_integration](./docs/mqtt_broker.png)
![mqtt_primer](./docs/mqtt_primer.png)
- Lokalno delovanje
![mqtt_local](./docs/starting_home_assistant.png)
- Velika razširljivost
- Mobilna apliklacija

    <img src="./docs/ha_mobile.jpg" alt="ha_mobile" width="250"/>

- Beleženje zgodovine
![mqtt_primer](./docs/ha_beleženje_zgodovine.png)

![ha_dashboard](./docs/hm-dashboard.png)