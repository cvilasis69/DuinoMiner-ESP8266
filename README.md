# DuinoMiner-ESP8266
Fork of Duino-Coin for ESP8266 (https://github.com/revoxhere/duino-coin/tree/master/ESP8266_Code)

Includes the PlatformIO project with the following improvements:
+ Added WiFi provisioning.
+ Added web settings.
+ Added web OTA update (without decreasing hashrate as official code).
+ Added network hostname with same rig id (adding extra ".local" to the uri) to easily access web settings .
+ Added default IoT info with last IP part (as temperature) and WiFi signal strength (as humidity).

### Instructions:
+ Flash your erased ESP8266 MCU with current project.
+ For WiFi provisioning and configure connection to your router, connect to the created AP **ESP8266-{autoid}** and use default password: "password". Then go to menu and select **Configure new AP** to add the SSID of your router.
+ Also remember to configure your Duino-Coin account in option menu **Settings**.

### Future:
+ Support ESP8265 MCU.
+ Add new web API for Mobile apps.
+ Create Mobile apps to simplify/automate WiFi provisioning and settings reconfiguration.
