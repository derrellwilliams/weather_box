<img width="1080" height="810" alt="e-ink-box-for-air-quality-weather-xiao-c3-4-26-v0-y83xeiknjs1i1" src="https://github.com/user-attachments/assets/f065d7e3-161f-468e-9f95-3ffd4c86fd21" />

<img width="1080" height="835" alt="e-ink-box-for-air-quality-weather-xiao-c3-4-26-v0-ajo5fd3pjs1i1" src="https://github.com/user-attachments/assets/bc7a1402-4628-41cd-b440-4b7f36d1c61e" />

A XIAO ESP32-C3 sits on Seeed's ePaper driver board with a 4.26" e-ink screen and an 1800 mAh LiPo, in a 3D-printed case.

Once an hour it wakes up, pulls a little JSON from a Cloudflare Worker, draws it and goes back to sleep. The Worker averages the PurpleAir sensors within 5 mi and gets temp and rain from Open-Meteo.
