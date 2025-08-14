# Pharmaceutical-Tablet-Manufacturing-Simulation
Built an end-to-end manufacturing simulation, visualizing a 6-stage production process for 200,000-tablet batches and identifying bottlenecks by modeling time-dependent processes in AnyLogic with batch constraints.

<img width="1897" height="1000" alt="image" src="https://github.com/user-attachments/assets/a9af87b6-1c4b-4029-ad44-57a681f13f34" />

## Project Overview

This AnyLogic model simulates the full tablet production workflow — from dispensing to distribution — ensuring process accuracy and detecting potential bottlenecks before scaling up production. The model enforces a sequential batch policy: no new batch begins until the compression and coating stage is complete.

### Key Features
Six production stages:
| Six production stages|
|:-----|:--------:|------:|
| Dispensing   | 15 minutes |
| Blending    |  30 minutes |
| Granulating   | 1 hour |
| Drying   | 2 hours |
| Compression & Coating   | 3 hours |
| Packaging   | 4 hours |
Six production stages:

Dispensing – 15 minutes

Blending – 30 minutes

Granulating – 1 hour

Drying – 2 hours

Compression & Coating – 3 hours

Packaging – 4 hours

Sequential batch logic: 200,000-tablet batches with strict blocking until compression/coating is finished.

Interactive visualization: Track production progress in real time.

Performance insights: Quickly identify time-intensive stages impacting throughput.

Technical Details

Simulation Type: Discrete Event Simulation (DES)

Tool: AnyLogic (Professional)

Inputs: Fixed process times per stage, batch size = 200,000 tablets

Outputs: Process timelines, bottleneck analysis, throughput estimation

How to Use

Open the model in AnyLogic.

Run the simulation to visualize the complete manufacturing process.

Adjust parameters (batch size, stage durations) to explore “what-if” scenarios.
