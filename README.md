#  Al Cringe Vacuum Line Follower

<img width="1004" height="1280" alt="photo_2026-10-03_12-21-54" src="https://github.com/user-attachments/assets/9178511c-dc4b-4f79-bf8d-02abb2b8012f" />


**Vacuum Wall-Climbing Line Following Robot**

**ESP32-WROOM • PID Control • Custom PCB • Custom Tires**

</p>

---

## 🚀 About the Project

This is a custom **line-following robot developed on our Al Cringe platform**.

The robot uses a **vacuum adhesion system**, allowing it to follow lines on normal surfaces and move on vertical walls.

The project includes the complete development process, from **PCB and mechanical CAD design to custom tire manufacturing, assembly and testing**.

---

## ✨ Main Features

- 🧠 **ESP32-WROOM**
- ⚙️ **TB6612FNG motor driver**
- 🔋 **Step-down converter**
- 🖥️ **OLED display**
- 👁️ **9-line bumper sensor**
- 📡 **I2C flash sensor**
- 🧠 **PID line-following**
- 🔘 **2 buttons for Kp / Ki / Kd tuning**
- 🧲 **Vacuum wall-climbing system**
- 🛞 **Custom tires**
- 🧪 **Custom silicone tire mold**
- 📐 Complete robot CAD model
- 🔌 Custom PCB design

---

# 📐 CAD & Mechanical Design

The project includes a **complete CAD model of the robot**, including its mechanical structure and assembly.

### Full Robot CAD

![Full Robot CAD](CAD/full-robot-model.png)

### Exploded View

![Exploded View](CAD/robot-exploded-view.png)

### Robot Assembly

![Robot Assembly](CAD/robot-assembly.png)

### Chassis

![Chassis](CAD/chassis.png)

---

# 🔌 PCB Design

A custom PCB was designed specifically for the robot.

The repository contains:

- PCB schematic
- PCB layout
- PCB 3D model
- Real manufactured PCB
- Front and back views

### Schematic

<img width="1286" height="735" alt="Снимок экрана 2026-10-03 121224" src="https://github.com/user-attachments/assets/8ff461e5-7843-4a96-a139-4234f5478749" />


### PCB 3D Model

<img width="1001" height="715" alt="Снимок экрана 2026-10-03 121304" src="https://github.com/user-attachments/assets/e98f09cc-0eca-4b93-ad57-cd1bfce1e007" />


### Real PCB

<img width="640" height="601" alt="unnamed" src="https://github.com/user-attachments/assets/c48bde0b-ea6f-4206-8116-aa5f87ae5afa" />


---

# 🛞 Custom Tire & Silicone Mold

One of the most important mechanical parts of the project is the **custom-designed tire**.

The tire was designed specifically for the robot, and a **custom silicone mold** was also designed and produced for manufacturing the tires.

### Tire CAD

![Tire CAD](Tire/tire-cad.png)

### Tire Drawing

![Tire Drawing](Tire/tire-drawing.png)

### Silicone Mold CAD

![Mold CAD](Tire/silicone-mold-cad.png)

### Silicone Mold Drawing

![Mold Drawing](Tire/silicone-mold-drawing.png)

### Real Tire

![Custom Tire](Tire/custom-tire.jpg)

### Real Mold

![Silicone Mold](Tire/silicone-mold.jpg)

---

# 🧠 PID Control & Tuning

The robot uses a **PID algorithm** for line following.

The main parameters are:

```text
Kp
Ki
Kd
```

Instead of uploading new code every time we change the PID values, the robot can be configured directly using **two buttons** and the OLED display.

This makes PID tuning faster during testing and competition preparation.

---

# 🖥️ OLED Interface

The OLED display shows the selected settings and PID values during configuration.

![OLED](Electronics/oled.jpg)

---

# 🧲 Vacuum Wall Climbing

The robot uses a vacuum system to maintain contact with vertical surfaces.

This required careful mechanical design and testing of:

- Robot weight distribution
- Tire contact
- Vacuum sealing
- Stability
- Grip

![Wall Climbing](Robot/wall-climbing.jpg)

---

# ⚡ Electronics

| Component | Purpose |
|---|---|
| **ESP32-WROOM** | Main controller |
| **TB6612FNG** | Motor control |
| **Step-Down Converter** | Voltage regulation |
| **OLED Display** | Settings and information |
| **9-Line Bumper** | Line detection |
| **I2C Flash Sensor** | Additional sensing |
| **2 Buttons** | PID configuration |

---

# 🔧 Development Process

```text
💡 Concept
   ↓
📐 Full Robot CAD
   ↓
🔌 PCB Design
   ↓
🛞 Tire Design
   ↓
🧪 Silicone Mold Design
   ↓
⚙️ Electronics Assembly
   ↓
🤖 Robot Assembly
   ↓
🧠 PID Tuning
   ↓
🧲 Wall Testing
   ↓
🚀 Final Robot
```

---

# 🧪 Testing

The robot was tested for:

- Line following
- PID tuning
- Sensor performance
- Motor control
- Vacuum adhesion
- Wall climbing
- Tire grip
- Overall stability

---

# 🎥 Videos

Practice and testing videos are available in:
### Vacuum practice
[(https://www.youtube.com/shorts/87kwGJLpC5M)]
### Line practice
[(https://www.youtube.com/shorts/C6_rVJTeaqk)]
The collection includes line-following tests and wall-climbing demonstrations.

---

# 🧠 Skills Developed

- 🤖 Line-following robotics
- 🧠 PID control
- ⚡ ESP32 electronics
- 🔌 PCB design
- 📐 Full robot CAD modeling
- 🛞 Custom tire design
- 🧪 Silicone mold design
- 🧲 Vacuum adhesion systems
- 🔩 Mechanical assembly
- 🧪 Testing and tuning

---

# 📊 Project Summary

| Category | Details |
|---|---|
| 🤖 Robot | **Al Cringe Vacuum Line Follower** |
| 🧠 Controller | **ESP32-WROOM** |
| ⚙️ Motor Driver | **TB6612FNG** |
| 🖥️ Display | **OLED** |
| 👁️ Sensors | **9-Line Bumper + I2C Flash Sensor** |
| 🧠 Control | **PID** |
| 🔘 Tuning | **2 Buttons — Kp / Ki / Kd** |
| 🧲 Special Feature | **Vacuum Wall Climbing** |
| 🛞 Tire | **Custom Designed** |
| 🧪 Mold | **Custom Silicone Mold** |
| 🔌 PCB | **Custom Designed** |
| 📐 CAD | **Complete Robot CAD Model** |

---

# 🚀 Final Result

This project combines **robotics, PCB design, CAD, PID control, custom tire manufacturing and vacuum wall climbing** into one complete system.

The repository documents the project from **schematic and CAD design to custom manufacturing, assembly and real-world testing**.

<p align="center">

## 🤖 Designed • Built • Tuned • Tested

**Al Cringe Vacuum Line Follower**

</p>
