#### HSACT | Neurocomputing 2025 | SSR from MSI to HSI
---
## HSACT: A Hierarchical Semantic-Aware CNN-Transformer for Remote Sensing Image Super-Resolution

***④	Chengle Zhou, Zhi He, Liwei Zou, Yunfei Li, and Antonio Plaza***

*[Neurocomputing](https://doi.org/10.1016/j.neucom.2025.129990), 2025, doi: 10.1016/j.neucom.2025.129990.*

---

![framework](https://github.com/chengle-zhou/MY-IMAGE/blob/57e18dd9c74f171f81a39f35704e571e17a07845/HSACT/Framework.png)

Fig. 1. Outline of the proposed HSACT method for SSR of remote sensing images.


## Abstract

Hyperspectral remote sensing technology has demonstrated its spectral diagnosis advantages in numerous remote sensing observation fields. However, hyperspectral imaging is expensive and less portable compared to RGB imaging. To recover the corresponding hyperspectral image (HSI) from a remote sensing RGB image, this paper proposes a new hierarchical semantic-aware convolutional neural network (CNN)-Transformer (HSACT) for remote sensing image spectral super-resolution (SSR). Particularly, this work aims to reconstruct HSIs from RGB images within the same field of view using a lightweight semantic embedding architecture. Our HSACT consists of the following steps. First, an initial spectrum estimation module (from the RGB image to the HSI) is designed to progressively consider spectral estimation between RGB wavelength-inner and wavelength-outer information. Then, an attention-driven semantic-aware CNN-Transformer is developed to reconstruct the spatial and spectral details of HSI. Specifically, a trainable polymorphic superpixel convolution (PSConv) is proposed to capture features efficiently in the above module. Next, we introduce an information-lossless hierarchical network architecture to link the above modules and achieve end-to-end RGB image SSR through weight sharing. Experimental results on several datasets demonstrated that our HSACT outperforms traditional and advanced SSR methods.


## Kind Reminder

***We are preparing the relevant code and will release it soon.***


## Citation Information
Please cite our new paper:

**Plain Text:**

Chengle Zhou, Zhi He, Liwei Zou, Yunfei Li, and Antonio Plaza. "[HSACT: A Hierarchical Semantic-Aware CNN-Transformer for Remote Sensing Image Super-Resolution](https://doi.org/10.1016/j.neucom.2025.129990)," ***Neurocomputing***, 2025, 636:129990, doi: 10.1016/j.neucom.2025.129990.

**BibTex:**

```latex
@article{Zhou2025,
  title = {HSACT: A hierarchical semantic-aware CNN-Transformer for remote sensing image spectral super-resolution},
  volume = {636},
  ISSN = {0925-2312},
  url = {http://dx.doi.org/10.1016/j.neucom.2025.129990},
  DOI = {10.1016/j.neucom.2025.129990},
  journal = {Neurocomputing},
  publisher = {Elsevier BV},
  author = {Zhou,  Chengle and He,  Zhi and Zou,  Liwei and Li,  Yunfei and Plaza,  Antonio},
  year = {2025},
  month = jul,
  pages = {129990}
}
```
