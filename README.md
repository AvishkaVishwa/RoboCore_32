
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
I have always had an urge to build my own product instead of relying only on ready-made boards. That passion led me to design RoboCore-32.

This board started as my testing platform — a way to learn PCB design, power routing, and motor driver integration while also creating something I could actually use in my robotics projects. Over time, it grew into more than just a test board: I see it as the foundation for a robotics learning kit fully built by me, where I can explore, experiment, and share what I learn with others.

RoboCore-32 is not just another ESP32 breakout; it’s a step toward creating my own ecosystem of boards, tools, and examples that help students and hobbyists dive into robotics with confidence.

---
## ✨ Highlights

- ESP32-WROOM-32 MCU (dual-core, Wi-Fi, BLE)
- TB6612FNG dual H-bridge motor driver for 2 DC motors
- Stable power management:
- LM2596S-5.0 buck (12 V → 5 V)
- AMS1117-3.3 LDO (5 V → 3.3 V)
- FT232RL USB-UART for flashing and debugging
- 12 V barrel jack input with auto-switching
- I²C JST header + GPIO breakout with clear silk labels
- User button (Boot/Reset)
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
</div>  This one is the first design i did and while testing I found some design errors. So I Redesign and ask From PCBWay Refabricate new design.

<div align="center">
<img src="Assets\board.jpg" width="400" alt="3D design" />
</div> 

<div align="center">
<img src="Assets\test1.jpg" width="400" alt="3D design" />
</div> 

<div align="center">
<img src="Assets\photo_2025-09-10_07-40-29.jpg" width="400" alt="3D design" />
</div> 

I'm Still developing this Car. In the future i need to add more functions to this robot.
<div align="center">
<img src="Assets\photo_2025-09-10_07-40-28.jpg" width="400" alt="3D design" />
</div> 


## 🎉 Special Thanks to PCBWay


<div align="center">
  <img src="Assets\board.jpg" width="500">
</div>

<p align="center">
    <a href="https://www.pcbway.com/" target="_blank">
    <img src="https://github.com/AvishkaVishwa/12V-DC-Motor-Speed-Controller-PCB-Design-using-KiCAD/blob/0191b6e02eeb30e176867d2a93ebec854536829a/Images/pcbwaylogo.jpg" alt="PCBWay" width="200"/>
  </a>

</p>

I would like to give a huge shoutout and sincere thanks to **[PCBWay](https://www.pcbway.com/)** for sponsoring the PCB fabrication of this project!

The **build quality, silkscreen clarity, via precision, and copper finish** exceeded expectations. PCBWay’s service was fast, professional, and extremely helpful throughout the production process.

This project wouldn’t have been possible without their generous support. If you’re looking to manufacture professional-grade PCBs at an affordable price, I highly recommend checking them out.

🔗 [Visit PCBWay →](https://www.pcbway.com/)

---
> © 2025 Avishka Vishwa   •   Made with ☕ & 🕑