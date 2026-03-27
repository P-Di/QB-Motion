# QB-Motion
//Bluepad32 json
https://raw.githubusercontent.com/ricardoquesada/esp32-arduino-lib-builder/master/bluepad32_files/package_esp32_bluepad32_index.json
//ESP json
https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
//Bluepad32 docs
https://bluepad32.readthedocs.io/en/latest/supported_gamepads/

//ESP Name
ESP32-PICO-MINI-02U
Name for bluepad = Adafruit ESP feather V2

//Sabertooth Lib
https://github.com/dominicklee/Sabertooth-for-ESP32

Instructions:
- Go to file > preferences > Additional boards manager URLS
- Add the ESP package_esp32_bluepad32_index.json and the package_esp32_index.json
- Click Ok
- Go to tools > board manager
- Download esp32 and esp32_bluepad
- Finally, download sabertooth library from here: https://github.com/dominicklee/Sabertooth-for-ESP32
- Extract those files, the go User>Yourname>Documents>Arduino>libraries and place the Sabertooth file that is located in the README.md of the downloaded sabertooth library file inside libraries. The sabertooth file placed in the arduino library folder should contain the c header files in the immediate subdirectory.
- Pick the Adafruit Feather ESP32 V2 and the appropriate COM
- Verify
- Run


Running the code:
// The main code, Main Optimized V2, is currently flashed on the esp. Power has been constrained to 100 instead of full 127. 
// The robot is still very fast so use caution. Finally, the left wheel slips at times, but at other operates at same speed as right.
// Connect by holding PS4 and Start button until white flashing buttons. Wait to connect to esp32, will be solid blue light when connected.
// Press triangle to "start" motors square to stop. Everything is controlled by left joystick for now.
