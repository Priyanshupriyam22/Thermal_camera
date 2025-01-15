# Thermal_Camera

A Raspberry Pi-based project utilizing the **Waveshare Thermal Camera HAT** to capture, process, and analyze thermal images. This repository contains the necessary scripts and documentation to get started with your thermal imaging project.

---

## 📖 Overview

This project integrates the Waveshare Thermal Camera HAT with the Raspberry Pi to deliver real-time thermal imaging capabilities. Whether you're using it for temperature monitoring, heat mapping, or other applications, this repository provides you with all the tools to start.

---

## 🛠 Features

- **Real-time thermal imaging**: Capture and display thermal data.
- **Customizable scripts**: Modify for your specific use case.
- **Data visualization**: Options for processing and displaying thermal data.

---

## 🚀 Getting Started

### Prerequisites
1. **Hardware**:
   - Raspberry Pi (Recommended: Raspberry Pi 4)
   - Waveshare Thermal Camera HAT
   - Necessary cables and power supply

2. **Software**:
   - Raspberry Pi OS (with Python 3 installed)
   - wget https://files.waveshare.com/wiki/Thermal-Camera-HAT/Thermal_camera_code.zip 
   - unzip Thermal_camera_code.zip
   - cd pysenxor-master/
   - sudo apt update
   - sudo pip uninstall numpy(If you are prompted that there is no library, proceed to the next step, and if there is one, uninstall the library: pip uninstall numpy)
   - sudo pip install numpy
   - sudo pip install smbus
   - sudo pip install crcmod
   - sudo pip install matplotlib
   - sudo pip install imutils
   - wget https://www.piwheels.org/simple/opencv-python/opencv_python-4.6.0.66-cp39-cp39-linux_armv7l.whl#sha256=c1360e46e5ebd47a92e00c1f75c7d293d6ffd00d7f9ff06666f9af05eff2094f
   - pip install opencv_python-4.6.0.66-cp39-cp39-linux_armv7l.whl
   - pip install cmapy 
   - sudo python setup.py install
   - cd pysenxor-master/example
   - sudo python stream_spi.py
---

### Setup
1. **Hardware Connection**:
   - Connect the Thermal Camera HAT to your Raspberry Pi following the guide provided in the [Waveshare documentation](https://www.waveshare.com/wiki/Thermal_Camera_HAT).

2. **Software Installation**:
   - Clone this repository:
     ```bash
     git clone https://github.com/Priyanshupriyam22/Thermal_camera.git
     cd Thermal_Camera
     ```

3. **Run the Example**:
   - Execute the thermal imaging script:
     ```bash
     python thermal_camera.py
     ```

---

## 📦 Dependencies

The project requires the following Python libraries:
- `numpy`
- `opencv-python`
- `matplotlib`

Install them using the following command:
```bash
pip install numpy opencv-python matplotlib





📚 Documentation
For detailed information on the Waveshare Thermal Camera HAT, refer to the official Waveshare documentation https://www.waveshare.com/wiki/Thermal_Camera_HAT.




🤝 Contributing
We welcome contributions to this project! Please fork the repository and submit a pull request with your improvements.
