---
layout: page
title: Shallow Recurrent Decoders
description: for State Estimation in Nuclear Reactors
img: assets/img/publication_preview/shred.jpg
importance: 1
category: work
related_publications: true
---

The SHallow REcurrent Decoder (SHRED) is an innovative neural network architecture designed to reconstruct high-dimensional spatio-temporal fields from limited sensor measurements. By integrating a Long Short-Term Memory (LSTM) network to capture temporal dynamics and a Shallow Decoder Network (SDN) to map these dynamics back to the original high-dimensional space, SHRED offers a robust solution for scenarios where sensor data is sparse or randomly placed {% cite riva2024robuststateestimationpartial %}.

**Key Features of SHRED:**

- **Efficient Sensor Utilization:** SHRED can accurately reconstruct complex spatio-temporal dynamics using as few as three sensors, even when they are randomly positioned. This capability reduces the need for extensive sensor networks and complex sensor placement strategies.

- **Computational Efficiency:** Training SHRED on compressed data enables efficient computations, making it feasible to train models on standard computing resources without extensive hyper-parameter tuning.

- **Versatility Across Domains:** The architecture has been successfully applied to various fields, including fluid dynamics and plasma physics, demonstrating its adaptability to different types of spatio-temporal data.

**Recent Applications in Nuclear Reactor Monitoring:**

In collaboration with the University of Washington, our team has extended the SHRED architecture to the field of nuclear reactor monitoring. By utilizing out-of-core neutron flux measurements, we have demonstrated that SHRED can reconstruct the full state vector of a reactor, encompassing multiple coupled field variables. This advancement holds significant potential for real-time monitoring and control in nuclear reactors, particularly in environments where in-core sensing is challenging.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/publication_preview/shred.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    SHRED architecture for state estimation in nuclear reactors, applied to the Molten Salt Fast Reactor {% cite riva2024robuststateestimationpartial %}.
</div>

The SHRED architecture continues to evolve, offering promising solutions for efficient and accurate state estimation in complex systems with limited sensor data.

For a visual overview of SHRED's application in nuclear reactor monitoring, you can watch the following video on [YouTube](https://www.youtube.com/watch?v=AUuGhojLiFk).
