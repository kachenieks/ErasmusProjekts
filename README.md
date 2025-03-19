# ErasmusProjekts

# Rīki
* **Intel RealSense SDK 2.0**: https://github.com/IntelRealSense/librealsense/releases
  * Windows videi atlasi `Intel.RealSense.SDK-WIN10-2.56.3.7838.beta.exe`
  * Linux videi jākompilē (https://iqr.cs.yale.edu/docs/computer-vision/intel-realsense.html#installation-prebuilt-binaries, https://github.com/IntelRealSense/librealsense/blob/master/doc/distribution_linux.md)
* **Python 3.10**: https://www.python.org/downloads/release/python-3119/
  * Python pakotnes: `numpy`, `pyrealsense2`
  * Komandrindas vidē `pip install numpy pyrealsense2`
* **HailoRT**: https://hailo.ai/developer-zone/software-downloads/ (Jāreģistrē konts un jāatlasa filtros operētājsistēmu *Windows* vai citu attiecīgu OS un Python versiju *3.10* un jāizvēlas pēdējo versiju)
* **Hoverbot**: https://github.com/mjbots/hoverbot
* Windows sistēmās **Windows Subsystem for Linux** ar distribūciju **Ubuntu**: https://ubuntu.com/desktop/wsl

# Darbības
1. Instalēt minētos rīkus šādā secībā: Intel RealSense SDK, Python, HailoRT un Hoverbot.
3. Testēt, vai kamera ir pareizi savienota, ievadot cmd komandu: **rs-enumerate-devices** (Rīks atrodas `<Intel RealSense SDK 2.0 instalācijas vieta>/tools/rs-enumerate-devices.exe` komandrindas vidē) (If the camera is connected properly, it should list details about the D455)
4. Apskatīt IMU datus ar **RealSense View** programmu.
5. Kalibrēt IMU ar `rs-imu-callibration` Python skriptu (dokumentācija https://github.com/IntelRealSense/librealsense/tree/development/tools/rs-imu-calibration, saitē lejupielādēt Python skriptu)
6. Instalēt **HailoRT** bibliotēku: https://github.com/hailo-ai/hailort
7. Iepazīties ar **HailoRT dokumentāciju** (jāreģistrē konts Hailo Develoepr Zone): https://hailo.ai/developer-zone/documentation/hailort-v4-20-0/
