# SequentialTest_EXXA5
Sequential Test

This test is for the projects that rely on sequential data that may need to be generated by the participant. This applies to EXXA3, EXXA4, and EXXA5, i.e., those that deal with spectra

Overview

One of the most successful methods to detect exoplanets is using light curves. Several thousand planets have been discovered this way. The basic idea is that exoplanets crossing in front of their host stars will obscure part of the star, which decreases the amount of light that we see from that star. By carefully measuring the brightness over time, planets can be identified by the periodic dimming. The extent of the dimming depends on the specific parameters of the stellar system. For a basic introduction, see this blog.

Task

Using these concepts, create a simulated dataset of transit curves. Include as many physical and system parameters that you think are necessary. PyTransit is a good example package. Participants can use it, any other package they find, or make their own. Feel free to supplement the synthetic data with observational data. Use this data to train a classifier that determines whether or not a given transit curve shows the presence of a planet. 


Metrics

Quantitative:
ROC curves and calculated AUC
Testing data will include real observations so take into account that noisy data will be used to judge

