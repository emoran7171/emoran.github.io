---
title:          "Deep Learning Improves Photometric Redshifts in All Regions of Color Space"
date:           2026-01-13 00:01:00 +0800
selected:       true
pub:            "The Astrophysical Journal"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2026"

abstract: >-
  Photometric redshifts (photo-z's) are crucial for the cosmology, galaxy evolution, and transient science drivers of next-generation imaging facilities like the Euclid Mission, the Vera C. Rubin Observatory, and the Nancy Grace Roman Space Telescope. Previous work has shown that image-based deep learning photo-z methods produce smaller scatter than photometry-based classical machine learning (ML) methods on the Sloan Digital Sky Survey (SDSS. Main Galaxy Sample, a test bed photo-z dataset. However, global assessments can obscure local trends. To explore this possibility, we used a self-organizing map (SOM) to cluster SDSS galaxies based on their ugriz colors. Deep learning methods achieve lower photo-z scatter than classical ML methods for all SOM cells. The fractional reduction in scatter is roughly constant across most of color space with the exception of the most bulge-dominated and reddest cells where it is smaller in magnitude. Interestingly, classical ML photo-z's suffer from a significant color-dependent attenuation bias, where photo-z's for galaxies within an SOM cell are systematically biased towards the cell's mean spectroscopic redshift and away from extreme values, which is not readily apparent when all objects are considered. In contrast, deep learning photo-z's suffer from very little color-dependent attenuation bias. The increased attenuation bias for classical ML photo-z methods is the primary reason why they exhibit larger scatter than deep learning methods. This difference can be explained by the deep learning methods weighting redshift information from the individual pixels of a galaxy image more optimally than integrated photometry.
# cover:          /assets/images/covers/cover3.jpg
authors:
  - Emma Moran
  - Brett Andrews
  - Jeffrey Newman
  - Biprateep Dey
# links:
  # Code: https://github.com/luost26/bubble-visual-hash
  # Demo: https://luost26.github.io/bubble-visual-hash
---
