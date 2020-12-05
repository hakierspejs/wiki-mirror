# Adresacja IPv4
W ramach [HSWAN](https://wiki.hackerspace.pl/projects:hswan) dysponujemy adresacją 10.14.0.0/16.

Aktualnie używany subnet: 10.14.22.0/16

Przeznaczenie adresacji:
* 10.14.22.1 – 10.14.22.9 – infra sieciowa:
  - 10.14.22.1 – centralka
  - 10.14.22.2 - wiadro
* 10.14.22.10 – 10.14.22.19 – lokalne usługi:
  - 10.14.22.10 - temp (hs-rpi0)
  - 10.14.22.11 - homeassistant (hs-rpi1)
  - 10.14.22.12 - at (hs-rpi2)
  - 10.14.22.13 - zamek (tasmota)
* 10.14.22.20 – 10.14.22.245 – DHCP

## OpenVPN
* 10.21.37.0/24