---
layout: page
title: pyforce
description: Python Framework for data-driven model Order Reduction of multi-physiCs problEms
img: assets/img/publication_preview/immy_pyforce2.png
importance: 2
category: work
related_publications: true
---

[![GitHub](https://img.shields.io/badge/GitHub-Repo-blue?logo=github)](https://github.com/ERMETE-Lab/ROSE-pyforce)

The **ROSE-pyforce** project is a Python framework developed to implement Data-Driven Reduced Order Modeling (DDROM) techniques, specifically targeting multi-physics problems prevalent in nuclear engineering. Built upon the FEniCSx project, ROSE-pyforce leverages the `dolfinx` package for tasks such as mesh generation, integral calculations, and function storage {% cite pyforce2024 %}.

**Key Features of ROSE-pyforce:**

- **Data-Driven Reduced Order Modeling (DDROM):** The framework focuses on reducing the computational complexity of multi-physics models by integrating real measurements, thereby enhancing the understanding of physical systems {% cite RIVA2024243 %}

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/publication_preview/tie_frighter.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Scheme of Data-Driven Reduced Order Modelling methodologies {% cite RIVA2024243 %}.
</div>

- **Sensor Placement Optimization:** ROSE-pyforce includes algorithms designed to determine optimal sensor positions, which is crucial for accurate data assimilation and model calibration in complex systems {% cite DDMOR_CFR %}

- **Open-Source Availability:** The ROSE-pyforce framework is openly accessible on GitHub, encouraging collaboration and further development within the scientific community.

The ROSE-pyforce project represents a significant advancement in the application of data-driven techniques to model order reduction in multi-physics problems, offering a valuable tool for researchers and engineers in the field.

