# ErasmusProjekts

# Rīki
* **Intel RealSense SDK 2.0**: https://github.com/IntelRealSense/librealsense/releases (atlasi `Intel.RealSense.SDK-WIN10-2.56.3.7838.beta.exe` Windows videi)
* **Python 3.10**: https://www.python.org/downloads/release/python-3119/
  * Python pakotnes: `numpy`, `pyrealsense2`
  * Komandrindas vidē `pip install numpy pyrealsense2`
* **HailoRT**: https://hailo.ai/developer-zone/software-downloads/ (Jāreģistrē konts)

# Darbības
1. Instalēt minētos rīkus
2. Testēt, vai kamera ir pareizi savienota, ievadot cmd komandu: **rs-enumerate-devices** (Rīks atrodas `<Intel RealSense SDK 2.0 instalācijas vieta>/tools/rs-enumerate-devices.exe` komandrindas vidē) (If the camera is connected properly, it should list details about the D455)
3. Apskatīt IMU datus ar **RealSense View** programmu.
4. Kalibrēt IMU ar `rs-imu-callibration` Python skriptu (dokumentācija https://github.com/IntelRealSense/librealsense/tree/development/tools/rs-imu-calibration, saitē lejupielādēt Python skriptu)
5. Instalēt **HailoRT** bibliotēku: https://github.com/hailo-ai/hailort
6. Iepazīties ar **HailoRT dokumentāciju** (jāreģistrē konts Hailo Develoepr Zone): https://hailo.ai/developer-zone/documentation/hailort-v4-20-0/
