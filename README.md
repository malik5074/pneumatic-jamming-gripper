# Pneumatic Jamming Gripper

This repository contains the mechanical and design files for a low-cost pneumatic granular jamming gripper developed for use with teleoperated collaborative robots. It includes 3D-printable CAD models, hardware schematics, and evaluation data.

## 🧠 Project Overview

The gripper uses a latex balloon filled with coffee grounds, vacuum-sealed using a small electric pump to provide adaptive grasping. The modular design supports easy integration with robotic arms such as the Niryo Ned2 and is suitable for educational or research purposes.

## 📦 Contents

pneumatic-jamming-gripper/
├── hardware_design/ # SolidWorks + STL files for gripper & mounts
├── electronics/ # Wiring diagram, BoM
├── control/ # Optional scripts for pneumatic actuation
├── evaluation/ # Gripper testing data (e.g., objects, cycles)
├── docs/ # Setup and usage instructions
└── README.md

markdown
Copy
Edit

## 🖨️ 3D Printing Instructions

- Print in **PLA** or **PETG**, 20% infill recommended
- Use support for overhangs in the gripper holder
- All parts designed in SolidWorks; STL files provided for direct printing

## 🛠️ Hardware Required

- 1x Latex balloon
- Ground coffee (filler)
- Mini vacuum pump (12V DC)
- Solenoid valve (optional)
- Pneumatic tubing (6mm)
- Inline air filter
- Niryo Ned2 compatible mounting plate

## 🧪 Gripper Performance

- Maximum object weight: ~100g
- Tested on 5 different object geometries
- Gripping success rate: 95%+
- Survived 50+ actuation cycles with no failure

## 📜 License

All designs and documentation in this repository are shared under the  
**Creative Commons Attribution 4.0 International (CC BY 4.0)** License.  
See the [LICENSE](LICENSE) file for details.

## ✍️ Author

Developed by **Khubaib Imran Malik** (khubaib.malik5074@gmail.com)
BEng (Hons) Mechanical Engineering, University of Greater Manchester 
Supervised by **Dr. Ma Mohin**
