# Greaseweazle Rerouted

![GreaseWeazle Rerouted!](Images/Image1.jpeg)

This is my own rerouted version of the [Greaseweazle](https://github.com/keirf/greaseweazle) V4.1 PCB.

The idea is pretty simple: build my own version of the board, keep it compatible with the original Greaseweazle firmware, and see how cheaply I could manufacture it.

## Why?

I was convinced that I needed a Greaseweazle after watching this video:

**[Using the Greaseweazle as a powerful disk drive diagnostic tool](https://www.youtube.com/watch?v=nSxDOpwYLVM)**

When I decided to build one, I noticed that the PCB files available for manufacturing used a **4-layer board**.

And that's where the fun started.

I enjoy routing PCBs, so I decided to see if I could reroute the board using only **2 layers**, while keeping the hardware practical and compatible with the original V4.1 design.

At the same time, I wanted to push the manufacturing cost down as much as reasonably possible at JLCPCB.

For the component selection, I prioritized **JLCPCB Basic components** whenever a suitable part was available. This avoids the additional **$3 Extended component fee** and can make a noticeable difference when ordering a small batch.

So, basically, this project combines two things I enjoy:

- **Routing PCBs just for the fun of it**
- **Finding ways to build useful hardware as cheaply as possible**

And having another useful tool in the workshop is never a bad thing.

> **Note:** This is a personal hardware project based on the Greaseweazle design. The original project remains the reference for the firmware, software, and general documentation.

---

## Test Videos

The first assembled boards were tested successfully with the Greaseweazle firmware.

Here are two videos showing the board in operation:

- **[Test 1 — Greaseweazle Rerouted](https://youtu.be/uOIKqvD94VU)**
- **[Test 2 — Greaseweazle Rerouted](https://youtu.be/tnco4Asw6lE)**

These were the first tests of the assembled boards and helped validate the rerouted PCB.

---

## Before You Build

Please read the documentation **before ordering or assembling the board**.

The manufacturing, assembly, and firmware programming instructions contain important details that are easy to miss if you jump straight into the build.

If you find anything unclear, incorrect, missing, or simply think could be explained better, please **open an issue**.

Questions, corrections, and suggestions are welcome. They can help make the project easier for the next person who decides to build one.

---

## 1. Additional Parts

The PCB and PCBA can be manufactured and assembled by JLCPCB. A few components are intentionally left out of the automated assembly, either for cost reasons or because they are easier to install by hand.

These parts need to be purchased separately:

| Qty. | Part | Notes | Link |
|---:|---|---|---|
| 1 | 37-pin IDC connector | Right-angle version preferred | [AliExpress](https://www.aliexpress.com/item/1005005364262476.html) |
| 1 | Floppy drive power connector | — | [AliExpress](https://www.aliexpress.com/item/1005004647707706.html) |
| 1 | 2x6 double-row male header | 2.54 mm pitch | [AliExpress](https://www.aliexpress.com/item/1005006870659706.html) |
| 1 | 1x2 single-row male header | 2.54 mm pitch | [AliExpress](https://www.aliexpress.com/item/1005006181780843.html) |
| 2 | Jumper | Board configuration headers | [AliExpress](https://www.aliexpress.com/item/1005009884235864.html) |

### Headers

You don't need to buy headers in exactly these lengths.

If you can find **breakaway male header strips**, just cut them to the required length for the **2x6** and **1x2** positions.

This is usually cheaper and gives you a little more flexibility when sourcing the parts.

---

## 2. Order the PCB

The manufacturing files are available in the [`Hardware`](./Hardware/) folder:

The [`JLCPCB`](./JLCPCB/) folder contains a step-by-step guide for ordering the PCB and PCBA.

---

## 3. Assemble the Board

Once the PCB and components arrive, follow the assembly guide:

**[Assembly instructions](./Assembly/)**

It covers component identification, placement, and the parts that need to be installed manually.

---

## 4. Program the Firmware

This board is based on the **Greaseweazle V4.1** hardware and uses the original Greaseweazle firmware.

Follow the official instructions for V4 devices:

**[Programming V4 Devices via USB DFU](https://github.com/keirf/greaseweazle/wiki/Firmware-Programming#programming-v4-devices-via-usb-dfu)**

> **Important:** Follow the official power and programming instructions carefully.

---

## 5. Start Using It

Once assembled and programmed, the board can be used with the official Greaseweazle software.

For the latest firmware, host tools, and user documentation, refer to the original project:

**[Greaseweazle by Keir Fraser](https://github.com/keirf/greaseweazle)**

---

## Credits

This project is based on the open hardware work of **Keir Fraser** and the [Greaseweazle project](https://github.com/keirf/greaseweazle) and George R. Mezzomo.

My contribution is the **Greaseweazle Rerouted**.

---

## Disclaimer

This is a personal hardware project. Build and use it at your own risk.

Always inspect and verify the PCB, components, assembly, and electrical connections before applying power.
