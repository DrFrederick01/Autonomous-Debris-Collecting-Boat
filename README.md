# Autonomous-Debris-Collecting-Boat 🚤

This was a group engineering project to design, build, and test a **proof-of-concept ship** that collects floating debris (40mm table tennis balls) in a water tank. I was responsible for the **control system**, including Arduino wiring and code.

<br>
<img src="Screenshot 2025-07-16 160907.png" height="80%" width="80%" />
<br> 
##  Role & Responsibilities
- Connected and programmed the **Arduino IO3 Mini** with the **motor controller**.
- Used **Arduino IDE** to write and debug C++ control code.
- Ensured proper integration of movement and collection mechanisms.
- Supported testing and refinement in lab conditions.
- Built the ship using limited materials.

##  Scenario & Specs
- Target debris: 9 floating ping-pong balls (40mm diameter).
- Tank size: 1.2m x 1.2m, 250mm depth.
- Success = storing all debris without releasing it back.
- Time limit: 10 minutes per test.

## Project Highlights
- Designed to navigate water and trap debris in a central storage unit.
- Controlled speed and direction of motors for precise movement.
- Achieved successful trial run during timed challenge.

##  Tech Stack
- Arduino IO3 Mini
- Arduino IDE (C++)
- Motor Controller + Sensors

## 🧪 Prototype Journey: From Whiteboard to Water

This section documents the iterative engineering process behind the autonomous debris-collecting boat — from initial ideation to working prototypes and final testing in water.

---

### 🧠 Initial Design Concepts – Whiteboard Sketches

Our journey began with rough system-level brainstorming. I proposed an innovative dual-hull design: two separate ship hulls connected by a flexible net mechanism that could extend or retract. This configuration would allow for a wide collection sweep and easier containment of floating debris (table tennis balls) across the water surface.

The whiteboard sketches below illustrate early geometry planning, hull symmetry, and net reach calculations. These ideas laid the foundation for a modular structure that could adapt its width dynamically.

**Insert image about: Whiteboard drawings of the dual-hull design**

---

### 🧱 Physical Proof-of-Concept – No Electronics

The first physical prototype brought the sketch to life using **plexiglass hulls**, which I shaped myself using a blowtorch to soften and mold the material. At this stage, no electronics were involved — it was a purely mechanical mockup to test the feasibility of the form and floating behavior. The goal was to ensure structural balance and validate the visual model against our collection width assumptions.

This prototype helped us understand weight distribution, buoyancy, and how the net tension would behave between the hulls.

**Insert image about: Plexiglass physical prototype of dual hulls with net**

---

### ⚙️ Testing the Rack and Pinion Mechanism

To enable **expandable hulls**, I recommended a rack and pinion mechanism. One hull hosted a motor-driven pinion, while the rack bridged across to the second hull, allowing symmetric expansion. This design allowed for a controlled, gear-driven extension of the net collection area.

We prototyped the mechanism and programmed it using **Arduino and joystick control**, testing precise movement in lab conditions. This was a key milestone in demonstrating real mechanical motion.

**Insert GIF about: Rack and pinion extension test with joystick + Arduino**

---

### 🔋 Internal Layout & Component Integration

Next, we began integrating electronic components, starting with the internal placement of the **battery, motor driver, and control board**. We focused heavily on:

- **Weight distribution** to prevent capsizing
- **Sealing** the battery unit from water ingress
- **Propeller placement** for efficient thrust

This phase involved experimenting with mounting techniques, center-of-mass analysis, and planning wiring paths through the plexiglass frame.

**Insert image about: Internal component layout with battery and motor considerations**

---

### 🌊 Propeller Testing in Water

With electronics secured and propulsion added, we tested the **motor-driven propellers** in real water conditions. The goal was to assess maneuverability, directional control, and thrust under realistic drag forces. The prototype successfully navigated the tank, verifying motor performance and hull responsiveness.

This was the first time the boat moved autonomously, using the joystick-controlled Arduino system.

**Insert GIF about: Boat moving through water using propellers**

---

### 🚀 Final Prototype & Field Demonstration

The final prototype demonstrated our full design — dual hulls, expandable net mechanism, and functional motor control. While we had to **expose electronics** due to resource and time constraints, we successfully achieved the project objective: collecting debris autonomously in a constrained water environment.

The **rack and pinion system now doubled as the collection net**, marking a smart re-use of the actuation system. Despite the limitations (e.g. low-cost components, exposed wiring), the boat executed full-scale field tests with effective performance, validating both mechanical design and embedded control logic.

**Insert GIF about: Final prototype moving & collecting debris in water**




