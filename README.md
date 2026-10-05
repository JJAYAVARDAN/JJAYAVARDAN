<div align="center">

# Hi, I'm Jolapuram Jayavardan 👋
### Embedded Software Engineer · Bluetooth Middleware & Controller Firmware · ARM Cortex-M4

**I build firmware and connectivity stacks that have to work — bare metal to RTOS, silicon to protocol.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jayavardan-j-120331218/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:j.jayavardan.r@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://jjayavardan.github.io/JJAYAVARDAN)
[![Resume](https://img.shields.io/badge/Resume-4285F4?style=for-the-badge&logo=googledocs&logoColor=white)](https://github.com/JJAYAVARDAN/JJAYAVARDAN/blob/main/resume.pdf)

</div>

---

## 🧑‍💻 About Me

I'm an Embedded Software Engineer specializing in **bare-metal ARM programming, RTOS architecture, and Bluetooth stacks from middleware to controller**. I'm an **Associate Software Engineer at Harman International**, working on the Android Bluetooth stack (HFP, A2DP, AVRCP, MAP, PBAP, Classic and BLE), HCI and sniffer-based debugging, firmware loading, and PTS certification.

What sets my background apart: I've built a **register-level C++ peripheral driver library from scratch** (GPIO, RCC, EXTI, NVIC, SysTick, USART, SPI, I2C, no HAL/LL), a **custom UART bootloader** (flash erase, CRC verification, VTOR relocation), and a **bare-metal task scheduler with zero HAL/IDE dependency**, writing my own linker scripts, startup files, and manipulating Cortex-M4 stack frames by hand.

- 🎓 B.Tech, Electronics & Communication Engineering — CGPA 8.0/10, RGMCET, Nandyal
- 🔧 Comfortable across the stack: silicon registers → drivers → RTOS → middleware → application protocol
- 📡 Production exposure to Bluetooth certification (PTS), OTA log capture, HCI snoop and Ellisys analysis, and RCA against the Bluetooth SIG core spec
- 🎯 Targeting: **Bluetooth Middleware / Controller Firmware / Embedded Software Engineer** roles
- 🌱 Currently deepening Linux kernel-level Bluetooth (BlueZ) and real-time systems design

---

## 🛠️ Tech Stack

**Languages**
![C](https://img.shields.io/badge/Embedded_C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Assembly](https://img.shields.io/badge/ARM_Assembly-444444?style=flat-square&logo=assemblyscript&logoColor=white)

**Microcontrollers & Boards**
![STM32](https://img.shields.io/badge/STM32F407VG-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![ARM7](https://img.shields.io/badge/ARM7_LPC2129-0091BD?style=flat-square)
![PIC](https://img.shields.io/badge/PIC16F877A-CC0000?style=flat-square)
![RaspberryPi](https://img.shields.io/badge/Raspberry_Pi_4-A22846?style=flat-square&logo=raspberry-pi&logoColor=white)

**RTOS & Bare-Metal**
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-262626?style=flat-square)
`Custom Bootloaders` `Linker Scripts` `Startup Code` `NVIC` `SysTick` `PendSV` `DMA` `Interrupts`

**Protocols**
`Bluetooth Classic & BLE` `HFP` `A2DP` `AVRCP` `MAP` `PBAP` `HCI` `OTA` `SPI` `I2C` `UART` `CAN` `MQTT` `HTTP`

**Platforms**
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Android](https://img.shields.io/badge/Android_Bluetooth_Stack-3DDC84?style=flat-square&logo=android&logoColor=white)
`ROS (Basics)` `PCB Design`

**Tools & Debugging**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
`ADB` `Perfetto` `Ellisys` `HCI Snoop` `Logic Analyzer` `GCC ARM` `OpenOCD` `GDB` `Keil µVision` `STM32CubeIDE` `MPLAB X` `SEGGER SystemView` `ESP-IDF`

---

## 🚀 Featured Projects

### 🧩 [STM32F407 Bare-Metal C++ Driver Library](https://github.com/JJAYAVARDAN/stm32f407-baremetal-cpp-drivers)
A from-scratch, register-level peripheral driver library for the STM32F407VG Discovery board — no HAL, no LL.
- Drivers built directly against the reference manual: **GPIO, RCC, EXTI, NVIC, SysTick, USART, SPI, I2C**
- Clean object-oriented C++ API — GPIO owns an RCC instance, EXTI takes port+pin, static NVIC methods
- Documented with **PlantUML class and architecture diagrams**, per-peripheral theory, and example applications
- `Embedded C++` `STM32F407` `Register Programming` `PlantUML`

### 🔌 [Custom UART Bootloader — STM32F407VG](https://github.com/JJAYAVARDAN/REPO_LINK_HERE)
A production-style bootloader with no vendor middleware.
- Flash erase, memory write, and **CRC32 integrity verification** before application jump
- Custom **VTOR relocation**, linker scripts, and startup code separating bootloader and app regions
- Companion **Python host tool** for firmware transfer and command handling over UART
- `Embedded C` `UART` `ARM Cortex-M4` `Python`

### ⏱️ [Bare-Metal Task Scheduler — STM32F407VG](https://github.com/JJAYAVARDAN/REPO_LINK_HERE)
A cooperative/round-robin scheduler built entirely from the CLI — no HAL, no IDE.
- Hand-written linker scripts and startup files for precise memory layout
- Manual **Cortex-M4 stack frame manipulation** via SysTick & PendSV for context switching
- Debugged at register and stack-frame level with **GDB + OpenOCD**
- `GCC ARM` `OpenOCD` `GDB`

### 🚗 [Real-Time Vehicle Data Acquisition System — FreeRTOS](https://github.com/JJAYAVARDAN/REPO_LINK_HERE)
Multi-sensor vehicle monitoring on ARM7 LPC2129.
- FreeRTOS tasks coordinating concurrent **SPI, I2C, and UART** sensor reads
- Task profiling and trace visualization with **SEGGER SystemView**
- `ARM7 LPC2129` `FreeRTOS` `SEGGER SystemView`

### ➕ [32-bit Hybrid Ling/Ripple-Carry Adder — VLSI](https://github.com/JJAYAVARDAN/REPO_LINK_HERE)
Custom adder combining Ling and Ripple Carry logic for a speed/area trade-off, designed in Cadence Virtuoso.
- `Cadence Virtuoso` `VLSI Design`

---

## 🔭 What I'm Working On

- 📲 Developing Bluetooth middleware features and supporting controller firmware at Harman International
- 🔍 Root cause analysis using HCI snoop, Ellisys captures, OTA logs, and the Bluetooth SIG core spec
- 🐧 Going deeper into Linux BlueZ internals to connect my embedded background to the Android Bluetooth stack
- 🧰 Moving project history into individually documented, pinned repositories

## 📚 Currently Learning

- Linux kernel-level Bluetooth (BlueZ) architecture
- Advanced RTOS scheduling and real-time systems design
- Secure OTA update design (signed firmware, rollback protection)

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=JJAYAVARDAN&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9)
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=JJAYAVARDAN&theme=dark&hide_border=true&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=JJAYAVARDAN&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8)

</div>

---

## 💼 Experience Snapshot

| Role | Company | Focus |
|---|---|---|
| Associate Software Engineer (`[Mon YYYY]` – Present) | Harman International | Bluetooth middleware and controller support: AOSP stack, HCI/Ellisys analysis, firmware loading via UART, RCA, PTS |
| Bluetooth Developer Intern (Jan 2026 – `[Mon YYYY]`) | Harman International | Android BT stack — HFP, A2DP, MAP, PBAP; PTS certification |
| Embedded Software Trainee | Vector India | Interrupt-driven drivers (SPI/I2C/UART/CAN), FreeRTOS, Linux |
| ARM Cortex-M4 Bare-Metal Program | Argyan Tech | Cortex-M4 architecture, custom scheduler, AAPCS |
| PIC Microcontroller Course | Argyan Tech | Register-level Embedded C on PIC16F877A |

## 📜 Certifications

`Embedded Systems — Eduskills & Microchip` · `ARM Cortex / STM32 MCU1 & MCU2 — FastBit Embedded Brain Academy` · `Cloud Computing — NPTEL` · `Introduction to IoT — NPTEL` · `Git & GitHub — GeeksforGeeks`

## 🏆 Achievements

🥈 2nd Place, Circuit Debugging — Ripple 2K24 &nbsp;|&nbsp; 🎖️ Appreciation Award, Chatbot Development — AIMERS Society

---

## 📬 Contact

<div align="center">

| | |
|---|---|
| 📧 **Email** | j.jayavardan.r@gmail.com |
| 🔗 **LinkedIn** | [linkedin.com/in/jayavardan-j-120331218](https://www.linkedin.com/in/jayavardan-j-120331218/) |
| 🌐 **Portfolio** | [jjayavardan.github.io/JJAYAVARDAN](https://jjayavardan.github.io/JJAYAVARDAN/) |
| 📄 **Resume** | [View / Download](https://github.com/JJAYAVARDAN/JJAYAVARDAN/blob/main/resume.pdf) |
| 📍 **Location** | Bengaluru, Karnataka, India |

**Open to: Bluetooth Middleware · Controller Firmware · Embedded Software Engineer roles**

</div>
