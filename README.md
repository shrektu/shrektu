# Sebastian Smolik

**Embedded systems & backend developer** · Kraków, Poland · remote-friendly

I write firmware for STM32 and nRF microcontrollers (AVR and ESP32 along the way) and the Python services
behind them. Right now I work on wireless IoT devices and I am finishing an MSc thesis on visual programming
for industrial robots.

## What I work with

| Area | Stack |
| --- | --- |
| Microcontrollers | STM32, nRF, ESP32, AVR |
| Firmware | C, C++, FreeRTOS, bare-metal and interrupt-driven designs, peripheral drivers (UART, SPI, I²C), wireless connectivity (Wi‑Fi, BLE), CMake |
| Backend | Python, FastAPI, PostgreSQL, Alembic, Docker, Nginx |
| Everyday tools | Git, CLion, VS Code, Postman, Raspberry Pi |

## Selected projects

| Project | What it does | Stack |
| --- | --- | --- |
| [cnc-dispenser](https://github.com/shrektu/cnc-dispenser) | Multi-channel liquid dispenser firmware: stepper-driven dosing by volume, rotary encoder and OLED (u8g2) interface, endstops, RTC and a UART command protocol. Bare-metal C with a CMake/avr-gcc build. | C, AVR |
| [robot-project](https://github.com/shrektu/robot-project) | Wi‑Fi controlled mobile robot: an ESP32 access point serves the control page and relays commands over UART to an ATmega328p that drives the motors (PWM), LCD and ultrasonic sensor. The AVR firmware is fully interrupt-driven. | C, ESP32, AVR |
| EasyPCR *(private)* | Portable PCR instrument: control firmware on STM32F4 with FreeRTOS. | C, STM32, FreeRTOS |
| Robotics Scratch *(MSc thesis, private)* | Browser-based visual programming for industrial robots: Blockly programs compiled to URScript, RAPID and KRL. FastAPI + PostgreSQL backend, React + TypeScript frontend, Docker deployment. | Python, TypeScript |

## Activity

<p align="left">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=shrektu&show_icons=true&hide_border=true&theme=transparent" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs?username=shrektu&layout=compact&hide_border=true&theme=transparent" alt="Top languages" />
</p>

Off the keyboard: gym, FPV drones, games.
