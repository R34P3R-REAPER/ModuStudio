# 🎥 ModuStudio: The IKEA of Studio Automation
**A high-effort, modular hardware ecosystem designed to eliminate 'setup friction' for solo creators.**

## 🚀 The Vision
In shared creative environments, setup friction is the enemy of consistency. ModuStudio automates the physical studio environment—allowing creators to transition from "Idea" to "Action" in under 60 seconds.

---

## 🛠️ Phase 1: Core Architecture (Day 1 - 5 Hour Sprint)
Today's deep-dive established the "Skeleton and Nervous System" of the ecosystem.

### 1. The Arc-Rail (Structural Backbone)
*   **The Chassis:** Optimized for a 1.5m overhead span using **Dual 750mm 2040 V-Slot Aluminum**. 
*   **The Logic:** Integrated **NEMA 17 Stepper Motors** with **TMC2208 Silent Drivers** in Onshape.
*   **Engineering Note:** Designed a modular "Rail Joiner" system to ensure global shippability (The IKEA Principle).

### 2. The Sentry (Distributed Intelligence)
*   **The Brain:** Powered by an **ESP32-C3** for a minimal footprint.
*   **Physical Firewall:** Configured a **12V Solenoid Bolt** (CAD finalized) and an OLED status display.
*   **Protocol:** Implemented **ESP-NOW** for sub-10ms wireless handshaking between the Rail Master and the Sentry Node.

### 3. The Integrated Gantry (Kinematics)
*   Finalized the **Carriage Plate** in Onshape (100mm x 120mm). 
*   Calculated a **60mm wheelbase** to ensure zero-torsion travel when carrying a full-frame DSLR.

---

## 🎨 Design Philosophy: "Concept-to-Casing"
I approach hardware through an architectural lens, prioritizing spatial integration. 
> *Current Design Language: Matte Black Aluminum + Dark Walnut Accents.*

![ModuStudio Hero Visualization](https://your-link-to-hero-render.png)

## 📅 Roadmap & Build Logs
- **March 22:** [Project Launch & Architecture Finalized] (Hour 1-5)
- **April:** Phase 2 - Motion Control & ESP-NOW Handshake (Hour 10-25)
- **May:** Phase 3 - Structural Assembly & Stress Testing (Hour 30-50)
- **June:** Final UX Polish & Haptic Console Integration (Hour 60)
- **July:** Final Prototype / Goal: Shenzhen Fellowship.

---
*Developed for the Hack Club Fallout '26 Program.*
