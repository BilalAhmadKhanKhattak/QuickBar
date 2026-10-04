# QuickBar

> **Lightweight, high-performance menu bar utility for macOS.**

Built natively with **Swift** and **SwiftUI**, QuickBar gives you instant access to essential system metrics and a quick scratchpad directly from your macOS top bar.

<p align="center">
  <img width="306" alt="QuickBar Menu Preview" src="https://github.com/user-attachments/assets/b2aa927f-162c-4214-ae6c-d658804001ca" />
</p>

---

## Key Features

- **Real-time System Monitoring:** Instant visibility into Battery Level, Uptime, RAM Usage, and Thermal State.
- **Quick Scratchpad:** A minimal, friction-free space for instant temporary notes.
- **Native Performance:** Native macOS integration designed for minimal CPU footprint and low memory overhead.
- **Universal Binary:** Runs natively on both **Apple Silicon** (M1/M2/M3/M4) and **Intel Macs**.
- **Launch at Login:** Seamless automated startup support.

---

## Compatibility

- **macOS:** Requires macOS 14.6 (Sonoma) or newer.

---

## Installation Guide

Because QuickBar is currently distributed directly outside the Mac App Store:

1. Download and open `QuickBar.dmg`.
2. Drag **QuickBar** into your `Applications` folder.

<p align="center">
  <img width="700" alt="Drag QuickBar to Applications" src="https://github.com/user-attachments/assets/57cde346-71b1-42d5-8ab8-dd8565b680f8" />
</p>

3. Right-click (or Control-click) **QuickBar** in `Applications` and select **Open**.
4. Click **Open** again on the system prompt (required only once).

> **Note:** If macOS Gatekeeper blocks execution, navigate to **System Settings > Privacy & Security**, scroll down to the **Security** section, and click **Open Anyway**.

---

## Memory Metric Note

QuickBar and macOS Activity Monitor calculate "Used Memory" differently:

- **QuickBar:** Calculates raw hardware consumption by subtracting unallocated free RAM and pure file caches from your total physical memory.
- **Activity Monitor:** Uses Apple's proprietary composite metric, bundling compressed memory, wired kernel allocations, and system reserves to represent overall system pressure.

*Both representations are accurate—they simply evaluate memory pressure through different technical lenses.*

---

## Pricing & Download

<p align="center">
  <img width="500" alt="QuickBar Pricing Overview" src="https://github.com/user-attachments/assets/5e19df30-c2ac-4cf6-bb2b-29f6c9d3f768" />
</p>

- **Version:** v1.0
- **Pricing Model:** Pay-What-You-Want (PWYW) / Suggested Price: **$2.99**

👉 **[Download on Gumroad](https://mrbilred.gumroad.com/l/quickbar)**
