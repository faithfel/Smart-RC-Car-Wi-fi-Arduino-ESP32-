# Arduino Esp32C3 Smart RC Car Wifi Controlled🚗💨

### A Wirelessly controlled RC car using Arduino ESP32C2 Wifi Access-Point.


<img src="img/car.png" alt="Alt Text" width="900" align="center">

_Additional picture in the <kbd>img</kbd> folder!_

### Features:
- Controller is through Wi-fi Access-Point (No Need To Download an App)
- Fast Responsive Controls
- Rechargable Battery
- Astig 😎

### Libraries Needed:
```
#include <WiFi.h>
#include <WebServer.h>

```
### Components/Materials Needed:
- Motor driver (L298N) (1pc)
- TT Gear motors w/ wheels (4pcs)
- Acrylic chassis kit (1pc
- 18650 Rechargeable Lithium Battery (2pcs)
- 18650 Battery casing (1pc)
- Female-to-Male Jumper wires (4pcs)
- Regular Jumper Wire (2pc atleast 0.5 meters)

## Wiring Guide:
<img src="https://aerotechproject.github.io/photo16.png" alt="Alt Text" width="500" align="center">

## How to Use?

### 1. Connect to the SSI with the password listed below.
<img src="img/wifi.png" alt="Alt Text" width="500" align="center">


```
const char* ssid = "WEB_ESP32_CAR";
const char* password = "12345678";
```

### 2. Open your Web Browser and type in the IP of the Access-Point.


```
192.168.4.1

```


<img src="img/ac.png" alt="Alt Text" width="500" align="center">

