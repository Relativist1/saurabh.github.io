---
layout: single
classes:
    - wide
    - landing
    - dark-theme
    title: Gallifray - Geometric Modelling and Parameter Estimation Framework for Black hole Images including VLBI.
author_profile: true

header:
  overlay_image: /assets/images/banner.png
  image_description: "A simulation of Sgr A* as seen by the EHT at 230 GHz" 
  overlay_color: "#000"
  overlay_filter: "0.5"

gallery0:
  - url: /assets/images/eht_banner.jpg
    image_path: /assets/images/eht_banner.jpg
    alt: "M87 in 2017"
    title: "The first resolved images of a black hole taken by the EHT in 2017"

gallery1:
  - url: /assets/images/EHT.jpg
    image_path: /assets/images/EHT_small.jpg
    alt: "EHT 2017"
    title: "The stations of the Event Horizon Telescope"

gallery2:
  - url: /assets/images/sim_and_reconstruct.png
    image_path: /assets/images/sim_and_reconstruct.png
    alt: "Simulated EHT image of M87 and reconstruction with eht-imaging."
    title: "(Left) an image of M87 at 230 GHz from one of my simulations. (Right) the image reconstructed with eht-imaging from realistic simulated data similar to the EHT's observations in 2017. The circle at the lower right represents the EHT's effective resolution"

gallery3:
  - url: /assets/images/hltau.png
    image_path: /assets/images/hltau.png
    alt: "Reconstruction of an ALMA image of HL Tau using traditional CLEAN vs eht-imaging."
    title: "(Left) an image of the protoplanetary disk in HL Tau from Band 7, 0.87 mm ALMA observations using the traditional CLEAN algorithm. (Right) the image reconstructed from the same data with eht-imaging using an imaging algorithm robust to errors in amplitude and phase calibration (Chael+ 2018)."

---
{% include gallery id="gallery0" caption="The first resolved images of a black hole taken by the EHT in 2017 ([Paper IV](https://iopscience.iop.org/article/10.3847/2041-8213/ab0e85), Fig. 15)" %}{: .text-center}
{: .align-right}

{% include gallery id="gallery1" caption="The stations of the Event Horizon Telescope" %}{: .align-right}
