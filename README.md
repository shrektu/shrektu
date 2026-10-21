<div align="center">

<img src="assets/neofetch.svg" width="100%" alt="sebastian@cracow — neofetch: embedded, backend and frontend developer from Cracow, Poland" />

</div>

### ❯ whoami

Embedded & full-stack developer from Cracow, Poland. I build connected devices end to end, from the firmware on the board to the screen people tap:

- **Firmware**: Zephyr and FreeRTOS on nRF and STM32, bare-metal C on AVR
- **Edge**: Linux services running on the device, in Python (FastAPI, NATS, I²C/GPIO peripherals)
- **Cloud**: Python and Node.js microservices, NATS messaging, PostgreSQL, Docker
- **Frontend**: React + TypeScript, from kiosk touchscreen UIs to web dashboards

I work agent-first, with Claude Code, Codex and Antigravity wired into a test-first, multi-agent review workflow I set up myself. After hours I hack on side projects.

### ❯ ls ~/stack

<p align="center">
  <img src="https://img.shields.io/badge/STM32-1a1b26?style=for-the-badge&logo=stmicroelectronics&logoColor=7aa2f7" alt="STM32" />
  <img src="https://img.shields.io/badge/nRF-1a1b26?style=for-the-badge&logo=nordicsemiconductor&logoColor=7dcfff" alt="nRF" />
  <img src="https://img.shields.io/badge/ESP32-1a1b26?style=for-the-badge&logo=espressif&logoColor=f7768e" alt="ESP32" />
  <img src="https://img.shields.io/badge/AVR-1a1b26?style=for-the-badge" alt="AVR" />
  <img src="https://img.shields.io/badge/Zephyr-1a1b26?style=for-the-badge" alt="Zephyr RTOS" />
  <img src="https://img.shields.io/badge/FreeRTOS-1a1b26?style=for-the-badge" alt="FreeRTOS" />
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=c,cpp,rust,py,ts,js,cmake,arduino,raspberrypi&theme=dark" alt="C, C++, Rust, Python, TypeScript, JavaScript, CMake, Arduino, Raspberry Pi" />
  <br />
  <img src="https://skillicons.dev/icons?i=react,redux,vite,tailwind,nodejs,fastapi,postgres,docker,nginx&theme=dark" alt="React, Redux, Vite, Tailwind CSS, Node.js, FastAPI, PostgreSQL, Docker, Nginx" />
  <br />
  <img src="https://skillicons.dev/icons?i=git,github,bash,vscode,postman,linux,ubuntu,apple,windows&theme=dark" alt="Git, GitHub, Bash, VS Code, Postman, Linux, Ubuntu, macOS, Windows" />
</p>

### ❯ ls ~/projects

| Project | What it does | Stack |
| --- | --- | --- |
| [**cnc-dispenser**](https://github.com/shrektu/cnc-dispenser) <sub>engineering thesis</sub> | Syringe-pump liquid dispenser firmware: stepper-driven dosing by volume, rotary encoder and a 128×64 graphic LCD (u8g2) menu, endstops, RTC and a Bluetooth command protocol over UART. Bare-metal C on ATmega2560 with a CMake + avr-gcc build. | <kbd>C</kbd> <kbd>AVR</kbd> |
| [**robot-project**](https://github.com/shrektu/robot-project) <sub>course project</sub> | Wi‑Fi controlled mobile robot: an ESP32 access point serves the control page and relays commands over UART to an ATmega328p that drives the motors (PWM), LCD and ultrasonic sensor. The AVR firmware is fully interrupt-driven. | <kbd>C</kbd> <kbd>ESP32</kbd> <kbd>AVR</kbd> |
| **EasyPCR** <sub>private</sub> | Portable PCR instrument: control firmware on STM32F4 with FreeRTOS. | <kbd>C</kbd> <kbd>STM32</kbd> <kbd>FreeRTOS</kbd> |
| **Robotics Scratch** <sub>MSc thesis · private</sub> | Browser-based visual programming for industrial robots: Blockly programs compiled to URScript, RAPID and KRL. FastAPI + PostgreSQL backend, React + TypeScript frontend, Docker deployment. | <kbd>Python</kbd> <kbd>TypeScript</kbd> |

### ❯ git log --stat

<p align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=shrektu&show_icons=true&count_private=true&include_all_commits=true&hide=issues,contribs&card_width=380&rank_icon=github&theme=tokyonight&bg_color=1a1b26&hide_border=true&border_radius=10&cache_seconds=86400" alt="GitHub stats" />
  <img height="150" src="https://streak-stats.demolab.com?user=shrektu&theme=tokyonight&background=1A1B26&hide_border=true&border_radius=10" alt="Contribution streak" />
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/shrektu/shrektu/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/shrektu/shrektu/output/snake-light.svg" />
  <img width="100%" src="https://raw.githubusercontent.com/shrektu/shrektu/output/snake-dark.svg" alt="Snake eating the contribution graph" />
</picture>
