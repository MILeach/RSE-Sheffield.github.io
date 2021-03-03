---
key: rumour_veracity
---

The Rumour Veracity project provides a [web-based platform]((https://tweetveracity.gate.ac.uk/)) for automatically identifying rumours in social media and assessing their veracity. The project features deep learning models for classification of veracity of a social media post and the stance of their replies. The project has resulted in the publication of the paper  [Journalist-in-the-Loop: Continuous Learning as a Service for Rumour Analysis](http://dx.doi.org/10.18653/v1/D19-3020). 

RSES is involved in the development of the entire service stack including the development of the web GUI and the server back-end for deploying the deep learning models. The service uses [Vue.js](https://vuejs.org/) for the user-side web interface and [Django](https://www.djangoproject.com/) to provide server-side application. We are currently working on a general framework for automatically retraining the DL models based on data collected on the website.
