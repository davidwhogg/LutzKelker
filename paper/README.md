# It is (almost) never appropriate to apply Lutz-Kelker corrections to your parallax measurements!

**Stephen Feeney** | *Flatiron*

**David W. Hogg** | *Flatiron* | *CCPP, NYU Physics* | *CDS, NYU* | *MPIA*

**Abstract:** An astrometric project (such as *Gaia*) produces noisy or uncertain parallax estimates for stars. The Lutz-Kelker correction is commonly applied to such measurements to correct for a bias which is related to the fact that there are (assumed to be) far more stars at small parallaxes (large distances) than there are at large parallaxes; low-parallax stars are more frequently scattered high than high-parallax stars are scattered low. In modern language, the Lutz-Kelker correction is related to the difference between the maximum of the likelihood and the maximum of the posterior under an improper prior. Here we criticize making this correction on a number of practical grounds: (1) The effective Lutz-Kelker distance prior is inappropriate for many stars in the age of *Gaia*. (2) The correction is only appropriate when the scientific goal is a single estimate of a single star's parallax; it is usually inappropriate when there is any other higher-level scientific goal, or if more than one star is involved in the scientific inference. (3) The correction delivers a point estimate of parallax, and does not deliver or represent the full parallax posterior. (4) The correction becomes undefined for (and requires the elimination of) parallax measurements at a signal-to-noise less than four. (5) Once the correction has been applied, the parallax measurement cannot be used straightforwardly in any further inference or hierarchical model without an undoing of the correction. We illustrate these points with simple examples. Because we can't stop ourselves, we provide a generalization of the Lutz-Kelker correction that could be used when *K* stars are used in concert to measure a distance, a color-magnitude diagram, or a period-luminosity relation; but we warn that this is only useful if the investigator seeks a point estimate, and not a full posterior pdf.

## The Lutz-Kelker correction

Here we give a contemporary account of the L-K correction.

(Call out the Hogg & Turner paper for using bad language and having some typos too.)

## Distance and parallax priors

Here we point out that we don't live in an infinite, homogeneous, non-evolving, non-expanding Universe of stars. This is point (1) in the abstract.

Use the example of MW Cepheids to hammer this home.

## Scientific goals

Here we point out that you never *actually* want the parallax for one star! This is point (2)

Give some examples of uses of *Gaia* DR1 papers.

## What is the goal of inference?

Here we point out that you want to deliver likelihood functions, not posterior pdfs. But even if you want the latter, you never want to deliver (as a data provider, anyway) a posterior point estimate. Ever. Maybe a likelihood point estimate? But never posterior. This encompasses points (3) and (5) in the abstract.

Give more examples of *Gaia* DR1 papers.

This section is a good place to highlight the difference between likelihood and posterior estimators. One difference is that posterior estimators change badly with re-parameterizations, whereas likelihood don't. Another is that data can be combined at the likelihood level, but not at the posterior level

## Parallaxes at low signal-to-noise

The correction dies at low signal-to-noise. What to do? Reject? This is point (4) in the abstract.

What are the issues with rejecting data on the basis of signal-to-noise. Fourth-moment shit!

## A K-star correction

The Feeney-Hogg correction is born here.

Don't ever use this correction for reasons (1), (3), and (5).

**Acknowledgements:** We thank Lauren Anderson (Flatiron) and Semyeong Oh (Princeton) for useful discussions.
