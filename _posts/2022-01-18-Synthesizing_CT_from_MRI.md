---
layout: post
title:  "Synthesizing CT from MRI in Radiation Oncology"
author: Jess
categories: [ RadiationOncology ]
image: assets/images/image_name.png
featured: true
---

In a radiation oncology department, we use often photons, protons, or electrons to cure cancer. Medical imaging is crucial in this process and allows us to visualize the tumor and healthy organs of a patient of whom we are treating. The most common imaging used in radiation oncology is a computed tomography (CT) scan because it provides both anatomical information and a map of photon attenuation, which is necessary for calculating the dose delivered by the radiation. However, magnetic resonance imaging (MRI) is an exceptionally powerful imaging modality that can provide very helpful information like excellent soft tissue contrast and functional information about tumor behavior. Therefore, MRI is becoming a very popular imaging choice in radiation oncology clinics. ![MRI Introduction Slide](../assets/images/Jess_RadOnc_MRI.png)

The downside of using MRI in radiation oncology is that it does not provide a map of photon attenuation that is crucial for dose calculation. This can be explained by looking at examples of bone versus air. Bone is the densest of biological materials and will highly attenuate a beam of radiation. Air, on the other hand (like in the lungs), is not very dense and will minimally attenuate a beam of radiation. On a CT scan, bone is bright while air is dark. On MRI scans, both bone and air appear as dark (due to low proton density of air and bone and very short transverse relaxation time of bone). Because of this, oftentimes patients will receive both a CT scan (for photon attenuation information) and MRI (for anatomical visualization). ![MRI Introduction Slide](../assets/images/MRI-Introduction.png)

As most know from personal experience, getting imaged in a hospital isn’t a very fun experience. While medical images are important for our healthcare and can be cool to look at, they can also cause anxiety from being inside a scanner, additional radiation (in the case of a CT scan), more time in spent in the clinic, and are quite expensive. Provided that clinicians have the information they need to provide optimal care, most people agree that the fewer medical imaging procedures, the better! In radiation oncology specifically, we are attempting to achieve this by transitioning to an MRI-only workflow which removes the need for a CT scan. As I mentioned earlier, MRI is not able to provide a map of photon attenuation. Therefore, to map photon attenuation from MRI, many groups are looking into generating synthetic CT scans from MRI. In other words, instead of a patient requiring both CT and MRI scans, in this workflow a patient would receive only an MRI scan, with the MRI used for anatomical visualization and MRI-generated synthetic CT for dose calculation. ![MRI Introduction Slide](../assets/images/MRI-Introduction.png)

In our research group, we have used deep learning to synthesize CT scans from MRI. For example, Andrew Leynes demonstrated that zero-echo-time MRI can be used to generate synthetic CTs in the pelvis. As part of my PhD dissertation, I investigated synthesizing megavoltage CTs (instead of standard kilovoltage CTs) from MRI for the purposes of higher accuracy dose calculation and future utilization with combined MRI-linear accelerators. Some interesting challenges that we are working on including synthesizing 3D megavoltage CTs from the combination of 2D radiographs and 3D MRI, mitigating limitations caused by differences in MRIs acquired in a radiology department versus a radiation oncology department, and improving differentiation between bone and air using ultrashort echo time (UTE) and zero echo time (ZTE) MRI techniques.

Links

[Principles of MRI Recorded Lectures](https://www.youtube.com/playlist?list=PLjBt5Iq93BT9eXMsgevVTXKVv4BgVLB1X)

Graphics example - upload image in the assets/images/ folder

![MRI Introduction Slide](../assets/images/MRI-Introduction.png)
