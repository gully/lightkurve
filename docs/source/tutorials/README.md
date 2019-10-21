# `lightkurve` Jupyter Notebook Tutorials

## Table of contents


Note from 10/21/2019--- Let's make science *themes*:
- Stellar activity
- asteroseismology
- Exoplanets
- Eclipsing binaries
- Clusters and young stars
- Extragalactic
  - (AGN)
- Classic variables
  - RR Lyrae,
- Interacting binaries
  - Heartbeat stars
  - CVs
- Solar system science


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
- AGN demo-- OJ287
- Eclipsing binaries (with Starry or otherwise)
- Stellar flares demo, and fitting multi-term sine waves in light curves
- White dwarf short cadence demo

### Extracting lightcurves

- [How to perform aperture photometry with custom apertures?](03-making-custom-apertures.ipynb)
- [How to perform PRF photometry?](03-how-to-use-prf-photometry.ipynb)
- [How to cut out Target Pixel Files from Kepler Superstamps or TESS FFIs?](03-cutting-out-tpfs-from-tess-ffis.ipynb)
- [How to save a LightCurve in FITS format?](03-making-fits-files.ipynb)
- [How to combine lightcurves from different Kepler quarters](03-appending-lightcurves.ipynb) *TODO: Update with HAT-P-11*
- Stitching TESS sectors
- Combining sparse ground-based photometry with Kepler/TESS
- Working with bright/saturated stars
- Global/local view pre-processing for AstroNet

### Systematics correction

- [Interactively inspecting Target Pixel Files and Lightcurves](04-interact-with-lightcurves-and-tpf.ipynb) [:tv:](https://youtu.be/89_sz-oG4VI) *TODO: save/apply custom aperture mask*
- [How to remove common systematics using basis vectors (CBVs)](04-removing-cbvs.ipynb)
- [How to remove K2 motion systematics with SFF?](04-how-to-detrend.ipynb)
- [How does the SFF method work?](04-replicate-vanderburg-2014-k2sff.ipynb) [:tv:](https://youtu.be/3Vs9uWW-E84)
- [Replicating Vanderburg & Johnson 2014 using lightkurve](04-replicate-vanderburg-2014-lightkurve.ipynb)  [:tv:](https://youtu.be/kYRqZwz2VPU)
- [How to identify time-variable background noise (“rolling bands”)?](04-identify-rolling-band.ipynb)
- Nearest neighbors for systematics inspection
- Pixel Level Decorrelation
- PSD of systematics: towards an "artifact kernel"
- Space craft telemetry demo
- K2SC tutorial

### Lightkurve tips & tricks, and experimental features
- Stitching *adjacent* TPFs (2018oh / M67 C5, C16, C18)
- lightkurve "gotchas" / troubleshooting
- Installing lightkurve (conda and optional dependencies, etc)
- Iterating analysis for many lightcurves
- Advanced search patterns: radius, future-proofing, etc
- Timing precision with Kepler/K2/TESS, O-C diagrams
- Exploring and visualizing quality flags
- Chromatic effects: Integrating the Kepler/TESS passbands
- Customizing your lightkurve plots with matplotlib

### Interfacing lightkurve with community software
- lightkurve for likelihood based inference and emcee
- Starry for stellar rotation
- Gaussian processes for stellar rotation
- Overplotting a theoretical celerite PSD on Periodogram
- Absolute photometry with FFIs
- Exoplanet framework demo
- TPF level injection with scope
- Comaparison of lightkurve vs astropy timeseries vs stingray
