# Aramco Hackathon — 3× First Place (Advanced Sensing, IoT & Robotics)

This repository is a **photo + media archive** of our team’s **first-place wins** in the Saudi Aramco (Upstream Digital) Hackathon track **“Advanced Sensing, IoT, and Robotics”** across **three consecutive editions (2024–2026)**.

> ✅ Purpose of this repo: preserve **winning photos**, **demo snapshots**, and a **high-level, non-confidential** summary of the problems we solved.  
> ⚠️ No proprietary Aramco data, credentials, or internal code is included here.

---

## Highlights (What we built)

Across the three editions, our work centered on **autonomous robotics pipelines** involving:
- **Mission planning** and **coverage optimization**
- **Autonomous navigation & landing**
- **Terrain / map filtering** using constraints (vegetation, structures, slope limits, etc.)
- **Swarm coordination** (collision avoidance, energy/battery constraints, recharge logistics)
- **Mechanism design + control systems** for real-world deployment

---

## Hackathon Editions & Problem Statements

### 1) Field Delivery with Drones (1st win)
**Theme:** Advanced Sensing, IoT & Robotics  
**Challenge:** “Field Delivery with Drones”  
**Core idea:** plan and execute drone-based delivery missions under real-world constraints (navigation, autonomy, operational reliability).

---

### 2) Mission Planning for a Swarm of Seismic Drones (2nd win)
**Theme:** Advanced Sensing, IoT & Robotics  
**Challenge:** **Fully autonomous seismic survey pipeline**:
- Identify valid survey points from **terrain data**
- Filter out **vegetation**, **urban structures**, and **slopes > 15°**
- A **drone swarm** autonomously:
  - lands on selected points
  - listens for seismic waves from a source truck
  - moves to the next targets
- Must satisfy constraints such as:
  - **collision avoidance**
  - **battery life**
  - efficient use of **battery recharge stations**
  - effective scanning / coverage of the area

---

### 3) Drone–Crawler NDT System for Nonmetallic Pipelines “Muaaniq” (3rd win)
**Theme:** Advanced Sensing, IoT & Robotics  
**Challenge:** Non-destructive testing (NDT) for **nonmetallic pipelines** without scaffolding/manual inspection.

**Concept:** a drone-deployed crawler device **“Muaaniq”** inspired by **inchworm locomotion**:
- Traverses **vertical and horizontal** pipes (diameters **6–10 inches**)
- Handles **vertical/horizontal elbows**
- Includes:
  - crawler **mechanical design**
  - drone mechanism to **release and recapture** the crawler
  - integrated **control system** for safe operation by engineers on the ground

---

## My Primary Contributions (Short + Technical)
- **Autonomy / planning:** mission planning + constraint-based filtering and coverage logic (terrain + operational constraints).  
- **Robotics & control:** control architecture for robust behaviors and safe execution (swarm constraints, landing, transitions).  
- **Mechanism design (Muaaniq):** mechanical crawler concept + deployment mechanism + control considerations for traction/stability on nonmetallic pipes.
