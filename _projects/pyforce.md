---
layout: page
title: ROSE-pyforce
description: A Python Framework for Data-Driven Model Order Reduction in Multi-Physics Problems
img: assets/img/publication_preview/immy_pyforce2.png
importance: 2
category: work
related_publications: true
---

[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue?logo=github&style=for-the-badge)](https://github.com/ERMETE-Lab/ROSE-pyforce)

**ROSE-pyforce** is an open-source Python framework designed for **Data-Driven Reduced Order Modeling (DDROM)**, particularly in the context of **multi-physics problems** in nuclear engineering. Built upon the **FEniCSx** project, ROSE-pyforce utilizes the `dolfinx` package for key computational tasks, including mesh generation, integral calculations, and function storage {% cite pyforce2024 %}.

---

## 🔑 Key Features

### 🚀 Data-Driven Reduced Order Modeling (DDROM)
ROSE-pyforce reduces the computational complexity of multi-physics simulations by integrating real measurement data, improving the accuracy and efficiency of surrogate models {% cite RIVA2024243 %}.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/publication_preview/tie_frighter.png" title="Example Image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Illustration of Data-Driven Reduced Order Modeling methodologies {% cite RIVA2024243 %}.
</div>

### 🎯 Sensor Placement Optimization
ROSE-pyforce includes algorithms that optimize sensor placement, crucial for accurate data assimilation and model calibration in complex physical systems {% cite DDMOR_CFR %}.

### 🔓 Open-Source Accessibility
The framework is openly available on **GitHub**, encouraging collaboration and further development in the scientific community.

---

ROSE-pyforce represents a significant advancement in the use of **data-driven techniques for model order reduction**, offering an innovative and computationally efficient approach for multi-physics problems. 🚀
