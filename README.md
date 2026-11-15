# Caltucalor – kapesní kalkulačka

Instalační stránka kalkulačky Caltucalor (ESP32-S3): https://wreze11.github.io/caltucalor/

Stránka `index.html` nahraje program do kalkulačky přes USB přímo z Chrome / Edge pomocí
[ESP Web Tools](https://github.com/esphome/esp-web-tools) (Apache 2.0, ve složce `esp-web-tools`).
Program má dvě verze, obě pro desku Seeed XIAO ESP32S3 a hlavní displej ST7789:

- `firmware/<verze>/dotyk/` – klávesnice na druhém, dotykovém displeji (Wi-Fi vypnutá),
- `firmware/<verze>/web/` – klávesnice na webové stránce v mobilu přes Wi-Fi kalkulačky.

Každá má svůj `manifest.json`. Starší verze 6.x jsou ve `firmware/<verze>/xiao/` (jen klávesnice v mobilu).
Návod (součástky, zapojení obou verzí, baterie, instalace, první spuštění) je v `caltucalor-navod.pdf`.
Písmo [Inter](https://rsms.me/inter/) (SIL OFL 1.1) je ve složce `fonts`.
Ve složce `demo` je kód kalkulačky přeložený do WebAssembly – živá ukázka nahoře na stránce.
