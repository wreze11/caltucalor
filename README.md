# Caltucalor – kapesní kalkulačka

Instalační stránka kalkulačky Caltucalor (ESP32-S3): https://wreze11.github.io/caltucalor/

Stránka `index.html` nahraje program do kalkulačky přes USB přímo z Chrome / Edge pomocí
[ESP Web Tools](https://github.com/esphome/esp-web-tools) (Apache 2.0, ve složce `esp-web-tools`).
Programy jsou ve složce `firmware/<verze>/<deska>/` (každá má svůj `manifest.json`), displej ST7789.
Písmo [Inter](https://rsms.me/inter/) (SIL OFL 1.1) je ve složce `fonts`.
Ve složce `demo` je kód kalkulačky přeložený do WebAssembly – živá ukázka nahoře na stránce.
