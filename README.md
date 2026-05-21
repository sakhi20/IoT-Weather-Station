# 🌦️ IoT Weather Station

A real-time IoT-based weather monitoring system built using **Raspberry Pi**, sensors, and a custom **HTML web interface**. It measures temperature, humidity, and light intensity and displays the data on a local web dashboard.

---

## 🎯 Project Aim

To design a **cost-effective**, easy-to-use IoT system that allows real-time monitoring of weather parameters through a web interface—ideal for smart homes, classrooms, or research projects.

*Note: This repository is forked from a collaborative undergraduate project at PDEU. Original work by Prerana Somani, Sakhi Patel, and team.*

---

## 📦 Components Used

- 🧠 **Raspberry Pi** – Central controller
- 🌡 **DHT11 / DHT22 Sensor** – For temperature and humidity
- 💡 **Light Cup Module** – For ambient light detection
- 🔌 Breadboard, jumper wires, 10kΩ resistor (for DHT), 5V power supply

---

## 💻 Technologies Used

- **Python** – Sensor data acquisition  
- **HTML/CSS** – Custom web interface  
- **Flask (optional)** – To serve the HTML dashboard locally  
- **GPIO libraries** – For interfacing with sensors on Raspberry Pi

---

## 🛠 Features

- Reads data from sensors in real time  
- Displays current weather conditions on a live dashboard  
- Responsive and lightweight local HTML interface  
- Scalable and customizable

---

## 🚀 How to Run

1. Connect sensors to Raspberry Pi GPIO pins
2. Clone this repository and navigate to the folder
3. Run the Python script to start collecting data
    ```bash
    python weather_station.py
    ```
4. Open `index.html` or go to `http://<raspberrypi-ip>:5000` if using Flask
---

## 🌱 Future Improvements

- Add logging and graph history
- Deploy web interface publicly using a cloud server  
- Include rainfall or pressure sensors

---

## 🙏 Acknowledgments

Thanks to all mentors and peers who supported the idea and implementation of this project!

---

> “Bringing smart weather tracking to your fingertips.” 🌤️
