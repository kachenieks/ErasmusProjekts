# ErasmusProjekts

# Rīki
* **Intel RealSense SDK 2.0**: https://github.com/IntelRealSense/librealsense/releases (atlasi `Intel.RealSense.SDK-WIN10-2.56.3.7838.beta.exe` Windows videi)
* **Python 3.11**: https://www.python.org/downloads/release/python-3119/
  * Python pakotnes: `numpy`, `pyrealsense2`
  * Komandrindas vidē `pip install numpy pyrealsense2`

# Darbības
1. Instalēt minētos rīkus
2. Testēt, vai kamera ir pareizi savienota, ievadot cmd komandu: **rs-enumerate-devices** (Rīks atrodas `<Intel RealSense SDK 2.0 instalācijas vieta>/tools/rs-enumerate-devices.exe` komandrindas vidē) (If the camera is connected properly, it should list details about the D455)
3. Apskatīt IMU datus ar **RealSense View** programmu.
