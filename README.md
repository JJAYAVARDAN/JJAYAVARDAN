<div align="center">

# Hi, I'm Jolapuram Jayavardan 👋
### Embedded Software Engineer · Bluetooth Stack Developer · ARM Cortex-M4 Specialist

**I build firmware and connectivity stacks that have to work — bare metal to RTOS, silicon to protocol.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jayavardan-j-120331218/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:j.jayavardan.r@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://jjayavardan.github.io/JJAYAVARDAN)
[![Resume](https://img.shields.io/badge/Resume-4285F4?style=for-the-badge&logo=googledocs&logoColor=white)](https://github.com/JJAYAVARDAN/JJAYAVARDAN/blob/main/resume.pdf)

</div>

---

## 🧑‍💻 About Me

I'm an Embedded Software Engineer specializing in **bare-metal ARM programming, RTOS architecture, and Bluetooth protocol stacks**. Currently a **Bluetooth Developer Intern at Harman International**, where I work on Android's Bluetooth stack — implementing and certifying HFP, A2DP, MAP, and PBAP profiles for automotive infotainment systems.

What sets my background apart: I don't just call embedded APIs — I've built a **custom UART bootloader from scratch** (flash erase, CRC verification, VTOR relocation) and a **bare-metal task scheduler with zero HAL/IDE dependency**, writing my own linker scripts, startup files, and manually manipulating Cortex-M4 stack frames. That's the kind of register-level fluency that's increasingly rare as more engineers stay in HAL/Arduino-land.

- 🎓 B.Tech, Electronics & Communication Engineering — CGPA 8.0/10, RGMCET, Nandyal
- 🔧 Comfortable across the stack: silicon registers → drivers → RTOS → application protocol
- 📡 Production exposure to Bluetooth certification workflows (PTS testing, OTA capture)
- 🎯 Targeting: **Embedded Software Engineer / Firmware Engineer / Bluetooth-Connectivity Developer** roles
- 🌱 Currently deepening Linux kernel-level Bluetooth internals and real-time systems design

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
`SPI` `I2C` `UART` `CAN` `HFP` `A2DP` `MAP` `PBAP` `OTA` `MQTT` `HTTP`

**Platforms**
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Android](https://img.shields.io/badge/Android_Bluetooth_Stack-3DDC84?style=flat-square&logo=android&logoColor=white)
`ROS (Basics)` `PCB Design`

**Tools & Debugging**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
`GCC ARM` `OpenOCD` `GDB` `Keil µVision` `STM32CubeIDE` `MPLAB X` `SEGGER SystemView` `ADB` `Logic Analyzer` `Cadence Virtuoso` `ESP-IDF`

---

## 🚀 Featured Projects

### 🔌 [Custom UART Bootloader — STM32F407VG](https://github.com/JJAYAVARDAN/REPO_LINK_HERE)
Built a production-style bootloader with no vendor middleware.
- Flash erase, memory write, and **CRC32 integrity verification** before application jump
- Custom **VTOR relocation**, linker scripts, and startup code to separate bootloader/app memory regions
- Companion **Python host tool** for firmware transfer and command handling over UART
- **Why it matters:** demonstrates the exact mechanism (safe, verifiable firmware updates) used in real OTA/field-update systems
- `Embedded C` `UART` `ARM Cortex-M4` `Python`

### ⏱️ [Bare-Metal Task Scheduler — STM32F407VG](https://github.com/JJAYAVARDAN/REPO_LINK_HERE)
A cooperative/round-robin task scheduler built entirely from the CLI — no HAL, no IDE.
- Hand-written linker scripts and startup files for precise memory layout control
- Manual **Cortex-M4 stack frame manipulation** via SysTick & PendSV for context switching
- Debugged at the register and stack-frame level using **GDB + OpenOCD**
- **Why it matters:** proves RTOS internals are understood, not just used
- `GCC ARM` `OpenOCD` `GDB`

### 🚗 [Real-Time Vehicle Data Acquisition System — FreeRTOS](https://github.com/JJAYAVARDAN/REPO_LINK_HERE)
Multi-sensor vehicle monitoring system on ARM7 LPC2129.
- FreeRTOS tasks coordinating concurrent **SPI, I2C, and UART** sensor reads
- Task-level profiling and RTOS trace visualization with **SEGGER SystemView**
- `ARM7 LPC2129` `FreeRTOS` `SEGGER SystemView`

### ➕ [32-bit Hybrid Ling/Ripple-Carry Adder — VLSI](https://github.com/JJAYAVARDAN/REPO_LINK_HERE)
Custom adder architecture combining Ling and Ripple Carry logic for optimized speed/area trade-off, designed in Cadence Virtuoso.
- `Cadence Virtuoso` `VLSI Design`

> 📌 Repo links are placeholders — push each project to its own repo (not buried in a single course-projects folder) so each one is independently star-able, forkable, and indexable by GitHub search.

---

## 🔭 What I'm Working On

- 📲 Shipping Bluetooth profile features (HFP/A2DP/MAP/PBAP) and running PTS certification cycles at Harman International
- 🐧 Going deeper into Linux BlueZ internals to connect my embedded background to the Android Bluetooth stack I work in daily
- 🧰 Migrating my project history out of a single repo into individually documented, pinned repositories (see recommendations below)

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

![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=JJAYAVARDAN&theme=react-dark&hide_border=true&bg_color=0d1117&color=58a6ff&line=58a6ff&point=c9d1d9)

</div>

> ⚠️ Note: stats widgets reflect *public commit activity*, which will look thin until projects are split into individual repos with real commit history (see below). This is normal for embedded portfolios and easy to fix.

---

## 💼 Experience Snapshot

| Role | Company | Focus |
|---|---|---|
| Bluetooth Developer Intern | Harman International | Android BT stack — HFP, A2DP, MAP, PBAP; PTS certification |
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
| 🔗 **LinkedIn** | [linkedin.com/in/YOUR_LINKEDIN_USERNAME](https://linkedin.com/in/YOUR_LINKEDIN_USERNAME) |
| 🌐 **Portfolio** | [YOUR_PORTFOLIO_URL.com](https://YOUR_PORTFOLIO_URL.com) |
| 📄 **Resume** | [View / Download](https://YOUR_RESUME_LINK.com) |
| 📍 **Location** | Bengaluru, Karnataka, India |

**Open to: Embedded Software Engineer · Firmware Developer · Bluetooth/Connectivity Engineer roles**

</div>

</div>
