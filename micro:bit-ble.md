# Bluetooth Low Energy (BLE) & the micro:bit — A Beginner's Guide

## What is Bluetooth Low Energy (BLE)?

Bluetooth Low Energy is a way for devices to talk to each other **wirelessly** without needing wires or cables. You probably know about regular Bluetooth—like what connects wireless headphones to a phone. BLE is a **power-friendly version** that uses a lot less battery power, which is perfect for small devices like the micro:bit.

## How Does It Work?

Think of it like this: your micro:bit becomes a little radio broadcaster. When you enable Bluetooth on your micro:bit, it sends out a signal that says "I'm here!" Other devices nearby (like a phone, tablet, or another micro:bit) can "hear" this signal and ask to connect. Once connected, they can share information back and forth.

**Important:** Before any device can use your micro:bit's Bluetooth connection, the two devices have to "pair" first—kind of like a handshake agreement where they say "yes, I trust you."

## Why Use BLE?

- **Wireless freedom** — No cables needed; your micro:bit can control things from across a room
- **Low power** — Uses very little battery, so it can run for a long time
- **Easy to use** — You can pair your phone or tablet to your micro:bit and send/receive data
- **Common** — Lots of devices use BLE (fitness trackers, smartwatches, game controllers)

## In Your Code

When you add Bluetooth to your micro:bit code, you're basically telling it: "Let other devices connect to you and do certain things." The video referenced at the end shows you how to actually set this up!

---

## 10 Quick BLE Projects to Try

### **10–15 Minute Projects**

#### 1. **Simple Message Display**
- Set up Bluetooth pairing between your phone and micro:bit
- Send text messages from your phone that appear on the LED display
- **What you'll learn:** How to receive data over Bluetooth
- **Difficulty:** Easy

#### 2. **Wireless Button**
- Make one micro:bit a wireless button that sends a signal
- When you press it, something happens on your phone or another micro:bit
- **What you'll learn:** How to send simple signals over BLE
- **Difficulty:** Easy

#### 3. **Light Remote**
- Use your phone to send commands to control the micro:bit's LED brightness
- Send "bright", "dim", or "off" commands
- **What you'll learn:** Receiving and responding to wireless commands
- **Difficulty:** Easy

---

### **20–30 Minute Projects**

#### 4. **Two micro:bits Talking**
- Connect two micro:bits over Bluetooth
- Press a button on one to make the other display something
- Build a simple two-way communication system
- **What you'll learn:** Peer-to-peer Bluetooth communication
- **Difficulty:** Medium

#### 5. **Sensor Data Streamer**
- Have your micro:bit send temperature or light sensor readings to your phone
- Watch the data update in real-time as the environment changes
- **What you'll learn:** Continuous data streaming and real-time updates
- **Difficulty:** Medium

#### 6. **Game Score Keeper**
- Create a game on your micro:bit
- Use your phone to score points wirelessly
- Display the score on the LED matrix
- **What you'll learn:** Two-way communication for interactive apps
- **Difficulty:** Medium

---

### **30–60 Minute Projects**

#### 7. **Motion Alarm System**
- Use the micro:bit's accelerometer (motion sensor)
- When the micro:bit shakes or moves, it sends an alert to your phone
- Your phone (or another device) receives the alert and triggers a sound/notification
- **What you'll learn:** Sensor data + wireless alerts
- **Difficulty:** Medium

#### 8. **Remote-Controlled Robot or Game**
- Build or control something physical (robot, car) with Bluetooth commands from your phone
- Send "forward," "backward," "left," "right" commands
- Watch it move based on your input
- **What you'll learn:** Wireless real-time control of physical objects
- **Difficulty:** Hard (if building the physical component)

#### 9. **Weather Station Dashboard**
- Have your micro:bit measure temperature, light, and motion
- Stream all this data to a phone app or web page
- Create a small "dashboard" that shows all the sensor readings
- **What you'll learn:** Multi-sensor data streaming + data visualization
- **Difficulty:** Hard

#### 10. **Fitness Tracker Simulation**
- Count steps or movements using the accelerometer
- Send "activity" data (steps taken, intensity) to your phone
- Track your activity over time wirelessly
- **What you'll learn:** Data collection, processing, and wireless transmission
- **Difficulty:** Hard

---

## Tips for Getting Started

1. **Start simple.** Try projects 1–3 first to get comfortable with sending/receiving data.
2. **Use MakeCode.** The MakeCode editor has built-in Bluetooth blocks that make this easier than coding from scratch.
3. **Pair first.** Always remember to pair your micro:bit with your phone before trying to communicate.
4. **Check the tutorial.** [This video](https://youtu.be/iTAOhJXVAvA?si=MHZTPjWBkF9vwKbY) shows how to add Bluetooth code to your micro:bit.
5. **Experiment!** BLE opens up tons of possibilities—try combining it with sensors, lights, and sound.

---

## Learn More

- [BBC micro:bit Bluetooth Overview](https://tech.microbit.org/bluetooth/)
- [About Bluetooth (MakeCode)](https://makecode.microbit.org/reference/bluetooth/about-bluetooth)
- [Bluetooth Low Energy Guide](https://kitronik.co.uk/blogs/resources/bbc-microbit-bluetooth-low-energy)
- [MicroPython BLE Documentation](https://microbit-micropython.readthedocs.io/en/latest/ble.html)
