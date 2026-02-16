# gps-tester
Simple GPS antenna tester.

This device comprises of a CYD (Cheap Yelow Display) based on the ESP32 chipset and a Ublox Neo 6M GPS reciever.

<img width="1272" height="2048" alt="image" src="https://github.com/user-attachments/assets/16a84108-d00a-4060-b07c-39933d312a51" />

See the code in cyd-gps-tester.yaml. It's written in ESPhome yaml and designed to integrate the outputs into Home Assistant, although it will run entirely standalone and will not recycle if it can't connect to either WiFi or the Home Assistant API.

Connection of the GPS module to the screen is via the included 4 wire cable that comes with the screen (Most kits), that plugs into the socket nearest the SD Card reader.
Red = 3v3 Black = GND Yellow = RX Blue = TX

This should work with other GPS modules, although not tested...

Raise any bugs in the issues tracker. Ensure you mention your version of ESPHome.
