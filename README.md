# PlantBuddy32
Plant monitoring system with camera, watering system, air and soil sensors.

### Installing

Follow the steps below to get the project installed and running on your machine.

Clone the repo

```sh
git clone https://github.com/JamieKaiRemkes/PlantBuddy32.git PlantBuddy32
```

Change folder
```sh
cd PlantBuddy32
```

Add your wifi cridentials
Add a file called wifikeys.h to to src folder with the following code
```h
#include <Arduino.h>
const char *ssid = "NetworkName";	    // Put your SSID here
const char *password = "NetworkPass";   // Put your PASSWORD here
```

## Authors

* **Jamie Kai Remkes** - *Initial work* - [Github](https://github.com/JamieKaiRemkes)

See also the list of [contributors](https://github.com/JamieKaiRemkes/PlantBuddy32/graphs/contributors) who participated in this project.

## License

This project is open source under the GNU general public License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

* Thanks to all who worked on this project.