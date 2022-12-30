# AirBox
Senzor pro měření stavu ovzduší. Pomocí dvou pokročilých senzorů měří koncentraci pevných částic PM (senzor Sensirion SPS3O) a teplotu, realtivní vlkosti a tlak vzduch (senzor Bosch BME280). Jedná se variantou odvozenou ze sensorů doporučených komunitním projektem [sensor.community](https://sensor.community/cz/). Airbox používá stejné zapojení jako komunitní senzory a je tak plně kompatibilní s jejich firmware.
## Hardware
Elektronika sensoru využívá běžný modul WeMos D1 Mini s WiFi mikrokontrolerem ESP8266. Ten tvoří srdce sensoru - po sběrnici i2c komunikuje s SPS30 a BME280 a získaná data odesílá prostřednictvním internetu ke zpracování a publikaci komunitním webům, popřípadě i jinam podle vaší volby. Kvůli umístění ve venkovním prostředí je elektronika umístněna v běžné vodotěsné elektrikářské krabičce. Jednotlivé elektronické komponenty jsou upevněny na jednoduché 3D vytištěné konstrukci, která také zajišťuje vhodné proudění vzduchu. 
### Seznam komponent
- krabička [SCAME SCABOX 120x80x50mm IP56](https://www.elfetex.cz/10-078-693-scame-krabice-scabox-120x80x50mm-ip56)
- 2x [nerez sítko ke zpětné klapce DN15 - 1/2"](https://www.obchod-vtp.cz/nerez-sitko-ke-zpetne-klapce-dn15-1-2)
- [WeMos D1 Mini ESP8266 WiFi](https://dratek.cz/arduino/121932-wemos-d1-mini-esp8266-wifi-modul-v2.0.html), originál či klon
- senzor kvality ovzduší [Sensirion SPS30](https://www.laskakit.cz/senserion-sps30-opticky-senzor-kvality-ovzdusi/)
- senzor teploty, vlhkosti a tlaku [BME280](https://dratek.cz/arduino/1361-bme280-modul-mereni-teploty-vlhkosti-a-barometrickeho-tlaku-precizni.html)
- [3D tištěné díly](/STL)
