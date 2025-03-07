---
layout: page
title: SHRED
description: Shallow Recurrent Decoders for State Estimation in Nuclear Reactors
img: assets/img/publication_preview/shred.jpg
importance: 1
category: work
related_publications: true
---

[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue?logo=github&style=for-the-badge)](https://github.com/ERMETE-Lab/NuSHRED)

**SHRED** (Shallow REcurrent Decoder) is a cutting-edge neural network architecture designed to reconstruct high-dimensional spatio-temporal fields from sparse sensor data. By integrating a **Long Short-Term Memory (LSTM)** network to capture temporal dynamics and a **Shallow Decoder Network (SDN)** to map these dynamics back to the original high-dimensional space, SHRED provides a robust solution for scenarios with limited or randomly placed sensors {% cite riva2024robuststateestimationpartial %}.

---

## 🔑 Key Features

### ⚡ Efficient Sensor Utilization
SHRED can accurately reconstruct complex spatio-temporal dynamics using as few as three sensors, even if they are randomly positioned. This capability reduces the need for large-scale sensor networks and eliminates the need for complex sensor placement optimization.

### 💻 Computational Efficiency
Training SHRED on **compressed data** enables efficient computation, making it possible to run models on standard hardware without requiring extensive hyper-parameter tuning.

### 🌍 Versatility Across Domains
SHRED has been successfully applied in various fields, including **fluid dynamics** and **plasma physics**, proving its adaptability to different types of spatio-temporal data.

---

## 🚀 Recent Applications in Nuclear Reactor Monitoring

In collaboration with the **University of Washington**, we have extended SHRED for **nuclear reactor monitoring**. Using out-of-core **neutron flux measurements**, we demonstrated that SHRED can accurately reconstruct the full state vector of a reactor, including multiple coupled field variables. This advancement holds great potential for **real-time monitoring and control** in nuclear reactors, particularly in environments where in-core sensing is difficult.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/publication_preview/shred.jpg" title="SHRED Architecture" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    SHRED architecture applied to state estimation in nuclear reactors, particularly the **Molten Salt Fast Reactor** {% cite riva2024robuststateestimationpartial %}.
</div>

---

SHRED continues to evolve, offering promising solutions for efficient and accurate state estimation in complex systems with limited sensor data.

For a **visual overview** of SHRED's application in nuclear reactor monitoring, check out the [YouTube Video](https://www.youtube.com/watch?v=AUuGhojLiFk).

