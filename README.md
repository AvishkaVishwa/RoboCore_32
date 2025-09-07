
<div align="center">
   <img src="https://img.shields.io/badge/ESP32-WROOM-blue?logo=espressif" />
   <img src="https://img.shields.io/badge/Robotics-Learning-green?logo=robot" />
</div>

# 🤖 **RoboCore-32**
### *An ESP32-Powered Robot Controller Board*

<div align="center">
   <img src="Assets/Block Diagrm.PNG" width="400" alt="Block Diagram" />
</div>

---


## ✨ **Why RoboCore-32?**
RoboCore-32 is a custom PCB for **robotics learning, prototyping, and IoT projects**. It features:

- 🟦 **ESP32-WROOM-32** (Wi-Fi + BLE microcontroller)
- ⚡ **TB6612FNG Dual H-Bridge Driver** – control up to **2 DC motors**
- 🔋 **Onboard Power Management**
   - LM2596S-5 → 5V buck regulator (up to ~3A)
   - AMS1117-3.3 → 3.3V LDO regulator
- 🖥️ **USB Programming & Debugging** via FT232RL USB–UART
- 🔌 **Barrel Jack Power Input** with auto switching
- 🧩 **Expansion Headers**
   - I²C JST header for sensors/displays
   - GPIO pin headers (1×02, 1×03, 1×04)
- 🔘 **User Input Button** (Reset/Boot/User configurable)

---

## 🛠️ **Applications**
- 🤖 2-Wheel Robots (line follower, obstacle avoidance)
- 🌐 IoT-enabled robotic platforms (Wi-Fi/BLE control)
- 🎓 Educational robotics & embedded systems
- ⚡ Rapid prototyping for automation

---


## 🧩 **Hardware Overview**

| Section           | Components                         |
|-------------------|------------------------------------|
| **MCU**           | ESP32-WROOM-32                     |
| **Motor Driver**  | TB6612FNG (dual channel, H-Bridge) |
| **Power**         | LM2596S-5 (5V), AMS1117-3.3 (3.3V) |
| **Connectivity**  | USB Micro-B (FT232RL), JST I²C     |
| **Inputs/Outputs**| Multiple GPIO headers, push button |

---

## 📸 **Images**
<!-- Add PCB renders or real board photos here -->
- Top View
<div align="center">
<img src="Assets\Front_Layer.PNG" width="400" alt="Front_Layer" />
</div>
- Bottom View
<div align="center">
<img src="Assets\Back_Layer.PNG" width="400" alt="Back_Layer" />
</div>
- 3D View
<div align="center">
<img src="Assets\3D design.PNG" width="400" alt="3D design" />
</div>


## 📸 Images

<div align="center">
<img src="Assets\First_design.jpg" width="400" alt="3D design" />
</div>  This one is the first design i did and while testing I found some design errors. So I ask From PCBWay Refabricate new design.


- Top View  
- Bottom View  
- Assembled Prototype  

---

## 🎉 Special Thanks to PCBWay


<div align="center">
  <img src="--" width="260">   <img src="--" width="260"> 
</div>

<p align="center">
  <a href="https://www.pcbway.com/" target="_blank">
    <img src="--- alt="PCBWay" width="200"/>
  </a>

</p>

I would like to give a huge shoutout and sincere thanks to **[PCBWay](https://www.pcbway.com/)** for sponsoring the PCB fabrication of this project!

The **build quality, silkscreen clarity, via precision, and copper finish** exceeded expectations. PCBWay’s service was fast, professional, and extremely helpful throughout the production process.

This project wouldn’t have been possible without their generous support. If you’re looking to manufacture professional-grade PCBs at an affordable price, I highly recommend checking them out.

🔗 [Visit PCBWay →](https://www.pcbway.com/)

---
> © 2025 Avishka Vishwa   •   Made with ☕ & 🕑