# `lightkurve` Jupyter Notebook Tutorials

## Table of contents

:tv: *denotes a narrated screencast is available on the [Kepler/K2 Guest Observer Office YouTube Channel](https://www.youtube.com/channel/UCJx_ls4mg5ms9q4Mv_2mYqg).*

### Introduction to lightkurve

- [What are TargetPixelFile objects?](01-target-pixel-files.ipynb)  [:tv:](https://youtu.be/ebw4diF-2NY)
- [What are LightCurve objects?](01-what-are-lightcurves.ipynb)  [:tv:](https://youtu.be/xBesCFlkjIw)
- [What are LightCurveFile objects?](01-lightcurve-files.ipynb)  [:tv:](https://youtu.be/rh7kSNlsqGM)
- [What is the Periodogram class?](01-using-the-periodogram-class.ipynb) [:tv:](https://youtu.be/dYk2gjZGK7k)

### Science with lightkurve

- [How to recover a known planet in Kepler data?](02-recover-a-planet.ipynb)
- [How to recover the first TESS planet candidate with Lightkurve?](02-how-to-recover-the-first-tess-candidate.ipynb)
- [How to use lightkurve for asteroseismology](02-how-to-use-lightkurve-for-asteroseismology.ipynb)
- [How to make a supernova lightcurve?](02-how-to-make-a-supernova-lightcurve.ipynb)

### Extracting lightcurves

- [How to perform aperture photometry with custom apertures?](03-making-custom-apertures.ipynb)
- [How to perform PRF photometry?](03-how-to-use-prf-photometry.ipynb)
- [How to cut out Target Pixel Files from Kepler Superstamps or TESS FFIs?](03-cutting-out-tpfs-from-tess-ffis.ipynb)
- [How to save a LightCurve in FITS format?](03-making-fits-files.ipynb)
- [How to combine lightcurves from different Kepler quarters](03-appending-lightcurves.ipynb)

### Systematics correction

- [Interactively inspecting Target Pixel Files and Lightcurves](04-interact-with-lightcurves-and-tpf.ipynb) [:tv:](https://youtu.be/89_sz-oG4VI)
- [How to remove common systematics using basis vectors (CBVs)](04-removing-cbvs.ipynb)
- [How to remove K2 motion systematics with SFF?](04-how-to-detrend.ipynb)
- [How does the SFF method work?](04-replicate-vanderburg-2014-k2sff.ipynb) [:tv:](https://youtu.be/3Vs9uWW-E84)
- [Replicating Vanderburg & Johnson 2014 using lightkurve](04-replicate-vanderburg-2014-lightkurve.ipynb)  [:tv:](https://youtu.be/kYRqZwz2VPU)
- [How to identify time-variable background noise (“rolling bands”)?](04-identify-rolling-band.ipynb)


### Candidates for future Tutorials

- Nearest neighbors for systematics inspection
- Making and applying a custom aperture mask with interact
- Pixel Level Decorrelation
- TESS and K2 data for the same object
- Working with K2 M67 data from campaigns 5, 16, 18 
- Combining sparse ground-based photometry with Kepler/TESS
- Iterating analysis for many lightcurves
- Comaparison of lightkurve vs astropy timeseries vs stingray
- Stitching TESS sectors
- Advanced search patterns: radius, etc.
- Stitching *adjacent* TPFs (2018oh / M67)
- Gaussian processes for stellar rotation
- AGN demo-- OJ287
- Working with bright/saturated stars
- Starry for stellar rotation
- Eclipsing binaries (with Starry or otherwise)
- PSD of systematics: towards an "artifact kernel"
- Installing lightkurve (conda and optional dependencies, etc)
- lightkurve "gotchas" / troubleshooting
- Overplotting a theoretical celerite PSD on Periodogram
- Absolute photometry with FFIs
- Future proofing your lk.search code
- Period04 -like functionality for fitting sine waves in light curves
- Timing precision with Kepler/K2/TESS, O-C diagrams
- White dwarf short cadence demo
- Space craft telemetry demo
- TLSE demo (starry synthetic data)
- Stellar flares demo
- Exploring and visualizing quality flags
- Exoplanet framework demo
- K2SC tutorial
- Exploring background subtraction tradeoffs in TESS
- Chromatic effects: Integrating the Kepler/TESS passbands
- TPF level injection with scope
- lightkurve for likelihood based inference
- Transit ingress/egress duration timing, limb darkening
- Global/local view pre-processing for AstroNet
- Customizing your lightkurve plots with matplotlib
- lightkurve tips: kwargs and chaining
