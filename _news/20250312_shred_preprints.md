---
layout: post
title: PrePrints Available - SHRED for Molten Salt Reactor and DYNASTY Facility
date: 2025-03-12 16:11:00-0400
inline: false
related_posts: false
---

I am pleased to announce the release of two new preprints, expanding upon our previous work with the Shallow Recurrent Decoder (SHRED) method for nuclear reactor applications.

Supporting code is openly available on [GitHub](https://github.com/ERMETE-Lab/NuSHRED).

**Title**: Towards Efficient Parametric State Estimation in Circulating Fuel Reactors with Shallow Recurrent Decoder Networks
**Authors**: Stefano Riva, Carolina Introini, J. Nathan Kutz, Antonio Cammi

---

*Abstract*
> The recent developments in data-driven methods have paved the way to new methodologies to provide accurate state reconstruction of engineering systems; nuclear reactors represent particularly challenging applications for this task due to the complexity of the strongly coupled physics involved and the extremely harsh and hostile environments, especially for new technologies such as Generation-IV reactors. Data-driven techniques can combine different sources of information, including computational proxy models and local noisy measurements on the system, to robustly estimate the state. This work leverages the novel Shallow Recurrent Decoder architecture to infer the entire state vector (including neutron fluxes, precursors concentrations, temperature, pressure and velocity) of a reactor from three out-of-core time-series neutron flux measurements alone. In particular, this work extends the standard architecture to treat parametric time-series data, ensuring the possibility of investigating different accidental scenarios and showing the capabilities of this approach to provide an accurate state estimation in various operating conditions. This paper considers as a test case the Molten Salt Fast Reactor (MSFR), a Generation-IV reactor concept, characterised by strong coupling between the neutronics and the thermal hydraulics due to the liquid nature of the fuel. The promising results of this work are further strengthened by the possibility of quantifying the uncertainty associated with the state estimation, due to the considerably low training cost. The accurate reconstruction of every characteristic field in real-time makes this approach suitable for monitoring and control purposes in the framework of a reactor digital twin.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        <img src="{{ '/assets/img/publication_preview/ParametricMSFR_SHRED/T.gif' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Parametric MSFR SHRED - T">
    </div>
</div>
<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        <img src="{{ '/assets/img/publication_preview/ParametricMSFR_SHRED/U.gif' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Parametric MSFR SHRED - U">
    </div>
</div>

---

**Title**: From Models To Experiments: Shallow Recurrent Decoder Networks on the DYNASTY Experimental Facility
**Authors**: Carolina Introini, Stefano Riva, J. Nathan Kutz, Antonio Cammi

*Abstract*
> The Shallow Recurrent Decoder networks are a novel paradigm recently introduced for state estimation, combining sparse observations with high-dimensional model data. This architecture features important advantages compared to standard data-driven methods including: the ability to use only three sensors (even randomly selected) for reconstructing the entire dynamics of a physical system; the ability to train on compressed data spanned by a reduced basis; the ability to measure a single field variable (easy to measure) and reconstruct coupled spatio-temporal fields that are not observable and minimal hyper-parameter tuning. This approach has been verified on different test cases within different fields including nuclear reactors, even though an application to a real experimental facility, adopting the employment of in-situ observed quantities, is missing. This work aims to fill this gap by applying the Shallow Recurrent Decoder architecture to the DYNASTY facility, built at Politecnico di Milano, which studies the natural circulation established by internally heated fluids for Generation IV applications, especially in the case of Circulating Fuel reactors. The RELAP5 code is used to generate the high-fidelity data, and temperature measurements extracted by the facility are used as input for the state estimation. The results of this work will provide a validation of the Shallow Recurrent Decoder architecture to engineering systems, showing the capabilities of this approach to provide and accurate state estimation.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        <img src="{{ '/assets/img/publication_preview/DYNASTYParametricValidation.gif' | relative_url }}" class="img-fluid rounded z-depth-1" alt="DYNASTY Parametric Validation">
    </div>
</div>
