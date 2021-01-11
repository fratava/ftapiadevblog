---
title: "MESAS Meets KINICH-PAKAL: Measure and Modeling Main Sequence Stellar Atmospheres"
date: 2021-01-11T10:16:25+06:00
hero: /posts/aas237/images/vir.jpg
description: Stellar atmospheres
menu:
  sidebar:
    name: AAS237
    identifier: mesas
    weight: 30s
math: true
---

{{< alert type="primary" >}} The dominant emission mechanisms at millimeter/submillimeter remain largely unknown for most spectral types other than Solar analogues. This is due in part to the lack of data to inform stellar atmosphere models. In this work, we present a new methodology to fit the observed and synthetic spectrum of main-sequence stars through semiempirical models. We use the Levenberg-Marquardt algorithm as a Nonlinear method, PakalMPI as the semiempirical model and the observations that are part of an ongoing observational campaign entitled Measuring the Emission of Stellar Atmospheres at Submillimeter/ Millimeter wavelengths. Our results show that we can use semiempirical models as an input model to reproduce and constrain the observed spectrum of main-sequence stars. In addition to a better understanding of stellar processes, these models are also essential for determining the stellar contribution to unresolved circumstellar disks at submillimeter/millimeter wavelengths. {{< /alert >}}

## MESAS: Measuring the Emission of Stellar Atmospheres at Submillimeter/millimeter Wavelengths

MESAS is an ongoing observational campaign that seeks to obtain a broad spectral submillimeter–centimeter coverage of a range of spectral types to build a more complete catalog of stellar emission, because the spectrum of stars in this range, remains poorly constrained due to a lack of data for most spectral types and the Stars with no known circumstellar material provide valuable information about the physical conditions of the atmosphere. This information is useful to characterize the emission and use it as a template for several studies in many areas such as: stellar atmospheres, debris disks, and space weather. But, MESAS also can be applied in a stellar evolution context or even for long term stellar variability studies[^3] [^5].

{{< img src="/posts/aas237/images/sirius.png" height="400" width="500" align="center"  title="A boat at the sea" >}}

{{< vs -2 >}}

{{< split 4 4 4 >}}

##### 

---

##### 

Spectrum obtained with Phoenix Models for Sirius A. (White et al. 2019).

---

##### 

{{< /split >}}

## KINICH-PAKAL (KP)

For the theoretical part, we have Kinich-Pakal that It’s a new methodology to fit the observed and synthetic spectrum of solar-like stars from the centimeter to infrared wavelengths through semiempirical models. Kinich-Pakal uses the Levenberg-Marquardt algorithm to minimize the differences between synthetic and observed spectrum by running PakalMPI[^1] to hydrostatically equilibrate the atmosphere and to compute their synthetic spectrum. Kinich-Pakal is capable of finding the physical conditions such as pressure, density and temperature in function of the altitude[^2].

{{< img src="/posts/aas237/images/KP_AAS_tp.png" height="700" width="500" align="center" >}}

{{< vs -4 >}}

{{< split 4 4 4 >}}

##### 

---

##### 

Top panel: Brightness temperature of KP models for Alpha Centauri A and the Sun. Bottom panel: Semiempirical models obtained for Alpha Centauri A. (Tapia-Vázquez & De la Luz, 2020).

---

##### 

{{< /split >}}

## MESAS & KINICH-PAKAL

In a broad stellar context, both MESAS and KINICH-PAKAL works as a complement. MESAS provides an observational framework that constrains the stellar emission, and KinichPakal uses this information to model the atmosphere. As a result, we have a methodology to characterize the stellar emission from the radio to Infrared wavelengths[^4].

{{< img src="/posts/aas237/images/gvir.png" height="400" width="500" align="center" >}}

{{< vs -1 >}}

{{< split 4 4 4 >}}

##### 

---

##### 

Brightness temperature of KP models for gamma Vir A/B and gamma Lep (White et al. 2020).

---

##### 

{{< /split >}}

## References

[^1]: De la Luz, V., Lara, A., Mendoza-Torres, J. E., et al. 2010, ApJS, 188, 437 [Doi](https://doi.org/10.1088/0067-0049/188/2/437)
[^2]: Tapia-Vázquez, F., & De la Luz, V. 2020, ApJS, 246, 5 [Doi](https://doi.org/10.3847/1538-4365/ab5f0a)
[^3]: White, J. A., Aufdenberg, J., Boley, A. C., et al. 2019, ApJ, 875, 55 [Doi](https://doi.org/10.3847/1538-4357/ab0e7f)
[^4]: White, J. A., Tapia-Vázquez, F., Hughes, A. G., et al. 2020, ApJ, 894, 76 [Doi](https://doi.org/10.3847/1538-4357/ab8467)
[^5]: White, J.A., Aufdenberg, J., Boley, A.C., 2018, ApJ,859(2), p.102. [Doi](https://doi.org/10.3847/1538-4357/aac103)