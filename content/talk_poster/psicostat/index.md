---
abstract: Multi-subject functional Magnetic Resonance Image (fMRI) studies are critical to test the validity of findings across subjects. However, the anatomical and functional structure varies across subjects, hence the image alignment is a fundamental step. One anatomical alignment is the Talairach Atlas, thus, it doesn't account for functional topography. For that, Haxby et al. (2011) developed a functional approach called Hyperalignment, using sequential Procrustes orthogonal transformations. The inter-subject classification of functional response improved. However, any constraint isn't imposed on the transformation, losing results interpretability. In this contribution, we tackle the functional alignment with a statistical perspective. A probabilistic model for the data generating process is defined. The maximum likelihood estimates of the rotation parameters result to be the Generalized Procrustes Problem (GPA), which improves the Hyperalignment in terms of residuals sum of squares. The statistical framework allows assuming a prior distribution of the orthogonal transformation parameter, as the matrix Fisher Von Mises distribution. It embeds the anatomical information in the estimation of the parameters, i.e. penalizing the combination of spatially distant voxels. The application to several datasets shows that the proposed method improves the classification accuracy of task-related images with respect to the anatomical alignment and the Hyperalignment methods.
address:
  city: Padua
  country: Italy
  postcode: ""
all_day: false
authors: []
date: "April 11 2019"
date_end: ""
event: Psicostat 3.0
event_url: http://ip146179.psy.unipd.it/psicostat/web/psicostat3.html
featured: false
image:
  caption: ''
  focal_point: Right
location: Padua, Italy
math: true
projects:
- internal-project
publishDate: "2019-04-11T00:00:00Z"
slides: 
summary: Psicostat 3.0
tags: []
title: A Statistical approach to the alignment of fMRI data
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---


