# **Pharmaceutical Tablet Manufacturing Simulation**

> **Built an end-to-end manufacturing simulation, visualizing a 6-stage production process for 200,000-tablet batches and identifying throughput bottlenecks by modeling single-batch stage constraints in AnyLogic.**

<img width="800" height="750" alt="image" src="https://github.com/user-attachments/assets/4e490024-9fe2-4ce6-91af-b89394e9ed88" />

---

## 📌 Project Overview
This AnyLogic model simulates the full tablet production workflow — from **dispensing to distribution** — ensuring process accuracy and detecting bottlenecks before scaling up production.  
- **Single-batch per stage:** Each stage handles **one batch at a time** — no parallel processing within a stage.  
- **Pipelined flow:** New batches can enter **Dispensing** as soon as that stage is free; batches move forward when the **next stage becomes available.**  
- **Interactive visualization</span>:** Follow production flow in real time.  

---

## 🚀 Key Features
- **Six production stages:**  
  - Dispensing – 15 minutes  
  - Blending – 30 minutes  
  - Granulating – 1 hour  
  - Drying – 2 hours  
  - Compression & Coating – 3 hours  
  - Packaging – 4 hours  
- **Batch size:** 200,000 tablets per cycle  
- **Throughput estimation** and **bottleneck detection**  
- **What-if analysis** — adjust batch size and timings to test scenarios  

---

## ⚙️ Technical Details
- **Simulation Type:** Discrete Event Simulation (DES)  
- **Tool:** AnyLogic (Professional)  
- **Inputs:** Fixed process times per stage, batch size = 200,000 tablets  
- **Outputs:** Process timelines, throughput, bottleneck identification  

---

## 🖥️ How to Run
1. Open the model in AnyLogic.  
2. Click **Run** to visualize the complete manufacturing process.  
3. Adjust parameters to explore alternative production scenarios.  

---

## 🔑 Key Takeaways
- **Each stage processes one batch at a time** — allowing pipelining but no parallel work within a stage.  
- **Packaging (4 hours) is the bottleneck** that governs steady-state throughput.  
