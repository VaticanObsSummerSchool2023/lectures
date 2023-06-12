
**Project 1 [Zeljko Ivezic, University of Washington/Rubin-LSST]:**

Summary: Test SDSS-based models for kinematics of stars in the Milky Way using Gaia proper motion measurements. Compare Gaia and SDSS distance estimates (for millions of stars).

Data Sources: Gaia and SDSS databases. 

Methods and Tools: cross-correlation of different catalogs (Gaia and SDSS); multi-dimensional regression, visualization, hypothesis testing.

Expected Outcome: introduction to stellar astrophysics and Milky Way structure studies. Practical experience with Gaia and SDSS data. 

**Project 2 [Zeljko Ivezic, University of Washington/Rubin-LSST]:**

Summary: Use ZTF light curves to estimate periods for periodic variable stars from the LINEAR survey.

Compare ZTF and LINEAR periods and look for stars that changed behavior (e.g. Blaszko effect).

Data Sources: ZTF data portal and built-in astroML catalog of LINEAR variables.

Methods and Tools: cross-correlation of different catalogs; time series analysis, Lomb-Scargle periodogram, multi-dimensional classification, statistical tests.

Expected Outcome: working knowledge of time series analysis. If we find any star (out of 7,000 stars in astroML/LINEAR sample) changed its behavior, it could be a journal paper. 

**Project 3 [Giorgio Calderone, INAF-OATs]:** 

Summary: Search for bright high-z QSOs in the SkyMapper/PAN-STARRS survey.

Data sources: SkyMapper, PAN-STARRS, Gaia, WISE surveys, QSO catalogs (pre-downloaded).

Methods and tools: The students will search for new, bright QSOs at z>2 in the SkyMapper/PAN-STARRS photometric survey, following a multi-disciplinary approach:

data collection: download data from photometric surveys and auxiliary databases ;
data preparation: cross-match the input catalogs, preliminary source classification and feature selection;
QSO candidate selection: train a machine learning model to predict a source classification and estimate its redshift (if the source is extragalactic);
Estimate the performances of the selection process and propose possible improvements.

Expected outcome: identify the most promising features and ML methods for classification and redshift estimates.  Improve upon currently available results, specifically on the redshift estimation (potential to be a journal publication).


**Project 4 [Francisco Navarro, Flatiron Institute/Princeton University]:** 

Summary: Investigate whether galaxy properties correlate with local underlying matter density field. 

Data sources: Galaxies from the CAMELS simulations. 

Methods and tools: Decision trees and/or neural networks combined with likelihood-free inference. If time allows, also usage of symbolic regression to obtain analytic equations. 

Expected outcome: Quantify the correlation between galaxy properties and dark matter density. First steps to apply it to real data. Potential to be a journal publication.


**Project 5 [Francisco Navarro, Flatiron Institute/Princeton University]:** 

Summary: Using deep learning tools to distinguish between different dark matter models (e.g. cold vs warm).

Data sources: Dark CAMELS simulations.

Methods and tools: Convolution neural networks, fully connected layers and depending on time, graph neural networks. 

Expected outcome: Develop AI tools to discriminate between different dark matter models. Potential to be a journal publication. 


**Project 6 [Zeljko Ivezic, University of Washington/Rubin-LSST]:**

Summary: Use photometric observations of Trojan asteroids (ZTF light curves) to estimate their rotation rates and compare to the rotation rate distribution for main-belt asteroids, which has a cutoff.

Data Sources: ZTF light curve database and data from the Minor Planet Center. 

Methods and Tools: multi-band Lomb-Scargle periodogram, Bayesian Blocks Algorithm, model probability analysis, hypothesis testing (comparison of distributions). 

Expected Outcome: working knowledge of time series analysis and selected topics from asteroid and Solar System science. This work would be part of a larger project and would likely result in coauthorship on a journal paper.

 
**Project 7: [Marc Huertas-Company, IAC]: Comparing simulations and observations of galaxies with contrastive modeling**

Summary: Use self-supervised learning to compare mock IFU observations of TNG galaxies and MaNGA galaxies. We will apply contrastive learning to obtain a robust representation of galaxies og both observed and simulated galaxies and compare to find agreements and disagreements.

Data Source: IFU data of nearby galaxies (MaNGA) and mock IFU data from TNG (MANGIA)

Methods: Contrastive learning, Foundation Models

Expected outcome: Familiarity with self-supervised learning and Foundation Models. IFU data. Galaxy formation.

**Project 8: [Marc Huertas-Company, IAC]: Diffusion models to denoise JWST images**

Summary: Exploratory work to assess if score based generative models can learn an accurate prior of galaxy morphology and be applied for super resolution and denoising. We will try to apply them to JWST images of deep fields.

Data Source: Mock images of numerical simulations (TNG), JWST images (CEERS)

Methods: Score based generative models

Expected outcome: Knowledge of state-of-the art generative modeling, imaging, galaxy morphology. 

**Project 9: [Maria Elena Monzani, SLAC/Stanford]: Pulsar analysis with Fermi-LAT** 

Summary: Browse public datasets and analysis software from Fermi-LAT. Download data from a given source (e.g. Vela or Crab pulsar) and browse ephemerides. Apply algorithms for source localization. Find gamma pulsations and phase wrt radio ephemerides.   

Data Source: Public photon data from Fermi-LAT, public pulsar ephemerides.

Methods: Apply known algorithms for source localization and pulsation finding.

Expected outcome: Acquire familiarity with Fermi-LAT datasets and analysis tools. Useful for students who are interested in multi-wavelength (gamma+optical) studies.

**Project 10: [Maria Elena Monzani, SLAC/Stanford]: Source classification with Fermi-LAT**

Summary: Download Fermi-LAT source catalog. Inspect the spectral properties of known sources (galactic vs. extra galactic). Train a simple ML model (classification tree or similar) on known sources and rank probable classifications for unassociated sources. Verify likely classification by comparing with galactic coordinates.

Data Source: Fermi-LAT source catalog(s).

Methods: Simple ML model (boosted decision tree or similar).

Expected outcome: Ranking of unassociated sources in the Fermi-LAT catalog as likely galactic or extragalactic objects, based on their spectral properties.

**Project 11 [Dalya Baron, Carnegie Observatories]:**

Summary: Apply dimensionality reduction and/or clustering algorithms to MUSE IFU observations of ~20 galaxies observed as part of PHANGS. 

Data Sources: the students can choose whether they want to start with the MUSE spectral cubes or with a table with derived properties from the MUSE cubes. All data is publicly available in the PHANGS website.

Methods and Tools: data cleaning and preparation, dimensionality reduction algorithms (e.g., tSNE/UMAP), and clustering algorithms. 

Expected Outcome: working knowledge of optical IFU spectra, working knowledge on local galaxy properties on scales of ~100 pc [the scale of giant molecular gas clouds], seeing how machine learning can be used for hypothesis generation. If some new class/relation will be found, this may result in a journal paper. 

**Project 12 [Dalya Baron, Carnegie Observatories]:**

Summary: Using Self Organizing Maps to map a spectral IFU cube.

Data Sources: MUSE spectral cube from the PHANGS survey. All the data is publicly-available in the PHANGS website.

Methods and Tools: data cleaning and preparation, SOM algorithm, mapping back to spatial coordinates 

Expected Outcome: working knowledge of optical IFU spectra, working knowledge on local galaxy properties on scales of ~100 pc [the scale of giant molecular gas clouds], using machine learning to have an efficient exploration of a large dataset. This project may be part of a long-term project that is aimed at developing a tool to explore IFU cubes in a fast and efficient way.

**Project 13 [Dalya Baron, Carnegie Observatories]:**

Summary: Apply dimensionality reduction of white dwarf spectra from SDSS.

Data Sources: SDSS database and a table to identified white dwarfs.

Methods and Tools: data cleaning and preparation, dimensionality reduction algorithms (e.g., tSNE/UMAP), and clustering algorithms. 

Expected Outcome: working knowledge of white dwarf spectra, practical experience with SDSS databases and spectral analysis. If some new class/relation will be found, this may result in a journal paper. 

**Project 14: [Marc Huertas-Company, IAC]:  Finding outliers in JWST imaging data**

Summary: Use outlier detection methods to look for peculiar galaxies in deep JWST public fields. We will explore both catalog data (bulge/disc decompositions) and direct imaging and use different outlier detection methods.

Data Source: JWST images and catalogs (CEERS)

Methods and tools: Anomaly detection algorithms, generative modeling (e.g. diffusion)

Expected outcome: Familiarity with outlier detection with machine learnihng. Possible publication if some interesting objects are found.

**Project 15: [Marc Huertas-Company, IAC]:  Finding rings and bars in JWST images**

Summary: Explore Foundation models for identifying detailed morphological features in JWST images such as bars and rings.

Data Source: JWST images and catalogs (CEERS)

Methods and tools: Supervised classification, transfer learning, fine-tuning, Foundation Models

Expected outcome: Morphological classification of galaxies. If successful: catalog of bars and rings in JWST. Possible publication.
