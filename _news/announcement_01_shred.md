---
layout: post
title: PrePrint - SHRED for Nuclear Reactors
date: 2024-09-28 16:11:00-0400
inline: false
related_posts: false
---

First PrePrint of the SHRED paper on Nuclear Reactors is out! Check it out [here](https://arxiv.org/abs/2409.12550).

The code is openly available on [GitHub](https://github.com/ERMETE-Lab/NuSHRED).

---

*Abstract*
> Reliable, real-time state estimation in nuclear reactors is of critical importance for monitoring, control and safety. It further empowers the development of digital twins that are sufficiently accurate for real-world deployment. As nuclear engineering systems are typically characterised by extreme environments, their in-core sensing is a challenging task, even more so in Generation-IV reactor concepts, which feature molten salt or liquid metals as thermal carriers. The emergence of data-driven methods allows for new techniques for accurate and robust estimation of the full state space vector characterising the reactor (mainly composed by neutron fluxes and the thermal-hydraulics fields). These techniques can combine different sources of information, including computational proxy models and local noisy measurements on the system, in order to robustly estimate the state. This work leverages the Shallow Recurrent Decoder (SHRED) architecture to estimate the entire state vector of a reactor from three, out-of-core time-series neutron flux measurements alone. Specifically, the Molten Salt Fast Reactor, in the EVOL geometry (Evaluation and Viability of Liquid Fuel Fast Reactor System project), is demonstrated as a test case, with neutron flux measurements alone allowing for reconstruction of the 20 coupled field variables of the dynamics. This approach can further quantify the uncertainty associated with the state estimation due to its considerably low training cost on compressed data. The accurate reconstruction of every characteristic field in real-time makes this approach suitable for monitoring and control purposes in the framework of a reactor digital twin.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/shred.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

---

Have a look at the videos below to see the SHRED architecture in action:

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://www.youtube.com/watch?v=76r6WmOehDM&list=PLSH6dleR9E1C1u2qHTxDDqLlc-q5iN_Z7&index=5" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://www.youtube.com/watch?v=2YdmzPTotww&list=PLSH6dleR9E1C1u2qHTxDDqLlc-q5iN_Z7&index=15" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://www.youtube.com/watch?v=JYmub3FmssM&list=PLSH6dleR9E1C1u2qHTxDDqLlc-q5iN_Z7&index=4" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
