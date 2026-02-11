# micro:bit Bluetooth LE Projects

Explore creative projects that use **Bluetooth Low Energy** to wirelessly connect micro:bits with each other, smartphones, tablets, and laptops.

---

**Difficulty Levels:** `Beginner` | `Intermediate` | `Advanced`

**Tags:** `BLE Service` = Uses BLE GATT &nbsp;&bull;&nbsp; `Phone / Laptop` = Connects to companion app &nbsp;&bull;&nbsp; `Multi-device` = Multiple micro:bits

---

## What You Need

| Item | Notes |
|------|-------|
| **BBC micro:bit (V1 or V2)** | V2 recommended for improved BLE range and memory |
| **USB Cable & Battery Pack** | For programming and portable power |
| **Smartphone or Tablet** | iOS / Android with the micro:bit app |
| **Computer with Bluetooth** | For Web Bluetooth / laptop pairing projects |

---

## micro:bit &harr; Phone & Laptop

*Connect a single micro:bit to a smartphone or computer over Bluetooth Low Energy.*

### 1. BLE Remote Temperature Monitor

> **Difficulty:** Beginner
>
> Broadcast the micro:bit's on-board temperature sensor reading over the BLE Temperature Service. View live readings on your phone using the official micro:bit app or a generic BLE scanner.

| | |
|---|---|
| **BLE Services** | BLE Temperature Service |
| **Connects To** | Phone App |
| **Platform** | MakeCode / MicroPython |
| **Hardware** | 1 micro:bit |

---

### 2. Wireless Gamepad Controller

> **Difficulty:** Intermediate
>
> Turn the micro:bit into a Bluetooth HID gamepad. Map the accelerometer tilt and A/B buttons to controller inputs, then pair it with a phone or laptop to control games wirelessly.

| | |
|---|---|
| **BLE Services** | BLE HID Service |
| **Connects To** | Phone / Laptop |
| **Platform** | MicroPython / C++ |
| **Hardware** | 1 micro:bit |

---

### 3. Step Counter with Live Dashboard

> **Difficulty:** Intermediate
>
> Use the accelerometer as a pedometer and stream step-count data over the BLE Accelerometer Service. Build a simple Web Bluetooth dashboard in Chrome to chart your steps in real time.

| | |
|---|---|
| **BLE Services** | BLE Accelerometer Service |
| **Connects To** | Web Bluetooth |
| **Platform** | MakeCode + HTML/JS |
| **Hardware** | 1 micro:bit |

---

### 4. Bluetooth Keyboard Typer

> **Difficulty:** Intermediate
>
> Pair the micro:bit as a Bluetooth keyboard. Pressing button A types a pre-set message, and tilting the board cycles through characters. Great for accessibility experiments and quick-text shortcuts.

| | |
|---|---|
| **BLE Services** | BLE HID Keyboard |
| **Connects To** | Phone / Laptop |
| **Platform** | MicroPython / C++ |
| **Hardware** | 1 micro:bit |

---

### 5. Phone-Controlled LED Scroller

> **Difficulty:** Beginner
>
> Type a message on your phone and have it scroll across the micro:bit's 5x5 LED matrix in real time. Uses the BLE LED Service and UART Service through the official micro:bit app.

| | |
|---|---|
| **BLE Services** | BLE LED / UART Service |
| **Connects To** | Phone App |
| **Platform** | MakeCode |
| **Hardware** | 1 micro:bit |

---

### 6. Heart-Rate Style Alert Wristband

> **Difficulty:** Intermediate
>
> Strap the micro:bit to your wrist and push notification-style alerts from your phone via the BLE UART Service. The micro:bit vibrates (with a motor) or flashes an icon when a message arrives.

| | |
|---|---|
| **BLE Services** | BLE UART Service |
| **Connects To** | Phone App |
| **Platform** | MakeCode / MicroPython |
| **Hardware** | 1 micro:bit + motor |

---

## micro:bit &harr; micro:bit

*Use BLE radio messaging to connect two or more micro:bits wirelessly.*

### 7. Wireless Chat Messenger

> **Difficulty:** Beginner
>
> Build a two-way chat system between micro:bits. Each board sends short pre-set messages (mapped to buttons) over the radio and displays received messages on the LED grid.

| | |
|---|---|
| **BLE Services** | BLE Radio Group |
| **Devices** | 2 micro:bits |
| **Platform** | MakeCode |
| **Hardware** | 2 micro:bits |

---

### 8. Remote-Controlled Robot Car

> **Difficulty:** Intermediate
>
> One micro:bit acts as a tilt controller, sending accelerometer data over radio. The second micro:bit receives commands and drives motors on a simple chassis. Tilt to steer!

| | |
|---|---|
| **BLE Services** | BLE Radio |
| **Devices** | 2 micro:bits |
| **Platform** | MakeCode / MicroPython |
| **Hardware** | 2 micro:bits + motor driver |

---

### 9. Multiplayer Reaction Game

> **Difficulty:** Beginner
>
> A "host" micro:bit counts down and signals GO, then each player presses their button as fast as possible. The host collects timestamps via radio and crowns the fastest player on the LED display.

| | |
|---|---|
| **BLE Services** | BLE Radio Group |
| **Devices** | 2-5 micro:bits |
| **Platform** | MakeCode |
| **Hardware** | 2-5 micro:bits |

---

### 10. Proximity-Based Treasure Hunt

> **Difficulty:** Intermediate
>
> Hide micro:bits around a space, each broadcasting a unique BLE signal. A "seeker" micro:bit reads signal strength (RSSI) to display warmer/colder clues as the player gets closer to each hidden board.

| | |
|---|---|
| **BLE Services** | BLE RSSI |
| **Devices** | 3+ micro:bits |
| **Platform** | MicroPython |
| **Hardware** | 3+ micro:bits |

---

### 11. Wireless Voting & Polling System

> **Difficulty:** Beginner
>
> Each micro:bit is a voting handset -- press A or B to cast a vote. A central micro:bit tallies all received votes over the radio group and displays a live bar chart on its LED grid.

| | |
|---|---|
| **BLE Services** | BLE Radio Group |
| **Devices** | 3+ micro:bits |
| **Platform** | MakeCode |
| **Hardware** | 3+ micro:bits |

---

### 12. Synchronized LED Light Show

> **Difficulty:** Intermediate
>
> One conductor micro:bit sends timed pattern instructions over radio. All other micro:bits listen and display coordinated LED animations in unison, creating a crowd light show.

| | |
|---|---|
| **BLE Services** | BLE Radio |
| **Devices** | 4+ micro:bits |
| **Platform** | MakeCode / MicroPython |
| **Hardware** | 4+ micro:bits |

---

## Advanced & Hybrid Projects

*Combine multi-device radio networks with phone/laptop connectivity for more complex systems.*

### 13. BLE Sensor Network Dashboard

> **Difficulty:** Advanced
>
> Deploy multiple micro:bits as wireless sensor nodes (temperature, light, motion). A gateway micro:bit collects their data via radio and relays it over BLE to a Web Bluetooth dashboard on your laptop.

| | |
|---|---|
| **BLE Services** | BLE UART + Radio |
| **Connects To** | Web Bluetooth |
| **Devices** | 3+ micro:bits |
| **Platform** | MicroPython + HTML/JS |
| **Hardware** | 3+ micro:bits + laptop |

---

### 14. Phone-to-micro:bit Mesh Relay

> **Difficulty:** Advanced
>
> Send a text message from your phone via BLE to a nearby micro:bit. That board relays it over radio through a chain of micro:bits until it reaches the destination, which scrolls the message on its LEDs.

| | |
|---|---|
| **BLE Services** | BLE UART + Radio Mesh |
| **Connects To** | Phone App |
| **Devices** | 3+ micro:bits |
| **Platform** | MicroPython |
| **Hardware** | 3+ micro:bits + phone |

---

### 15. Wireless Intruder Alarm System

> **Difficulty:** Advanced
>
> Place sensor micro:bits at doors and windows. When motion or a magnetic switch triggers, the node sends an alert via radio to a hub micro:bit that pushes a BLE notification to your phone instantly.

| | |
|---|---|
| **BLE Services** | BLE Event Service + Radio |
| **Connects To** | Phone Notification |
| **Devices** | 2+ micro:bits |
| **Platform** | MicroPython / C++ |
| **Hardware** | 2+ micro:bits + sensors |

---

### 16. BLE MIDI Music Controller

> **Difficulty:** Advanced
>
> Turn the micro:bit into a wireless MIDI controller. Map touch pins, tilt, and buttons to MIDI note and CC messages, then pair over BLE MIDI to a music app like GarageBand on your phone or laptop.

| | |
|---|---|
| **BLE Services** | BLE MIDI Service |
| **Connects To** | Phone / Laptop DAW |
| **Platform** | C++ / MicroPython |
| **Hardware** | 1 micro:bit |

---

### 17. Real-Time GPS Tracker Relay

> **Difficulty:** Advanced
>
> Attach a GPS module to one micro:bit and radio its coordinates to a second micro:bit connected via BLE to a laptop. Display the live position on a web map using Web Bluetooth and Leaflet.js.

| | |
|---|---|
| **BLE Services** | BLE UART + Radio |
| **Connects To** | Web Bluetooth |
| **Devices** | 2 micro:bits |
| **Platform** | MicroPython + HTML/JS |
| **Hardware** | 2 micro:bits + GPS module |

---

### 18. Distributed Weather Station

> **Difficulty:** Advanced
>
> Place micro:bits outdoors with environmental sensors (BME280). Each node radios readings to a hub, which bridges data over BLE to your phone. Log and graph temperature, humidity, and pressure over time.

| | |
|---|---|
| **BLE Services** | BLE UART + Radio |
| **Connects To** | Phone App |
| **Devices** | 2+ micro:bits |
| **Platform** | MicroPython |
| **Hardware** | 2+ micro:bits + BME280 |

---

## Bluetooth Tips & Troubleshooting

- Always **pair** your micro:bit before connecting -- hold A+B and press reset to enter pairing mode.
- On micro:bit V1, enabling BLE services consumes significant memory. Disable unused services in your MakeCode project settings.
- micro:bit V2 has a more powerful nRF52833 chip with better BLE range, throughput, and memory for running multiple services simultaneously.
- The **micro:bit radio** (used in micro:bit-to-micro:bit projects) operates on the same 2.4 GHz band as BLE but uses a simpler proprietary protocol -- it cannot talk directly to phones.
- For phone projects, download the official **micro:bit app** (iOS / Android) or use **Web Bluetooth** in Chrome.
- Web Bluetooth requires HTTPS. Use `localhost` or a service like GitHub Pages for testing your dashboards.
- If a connection drops, try moving closer -- the micro:bit's BLE range is typically 10-20 m indoors.
- When combining radio + BLE on the same micro:bit (gateway pattern), test thoroughly -- both share the 2.4 GHz radio hardware.

---

*micro:bit is a trademark of the Micro:bit Educational Foundation. Projects are for educational purposes.*

*Built with care for makers, educators, and students.*
