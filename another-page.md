---
layout: default
---

## A big wide world...  

We hope for this site to serve as a useful reference. For example, here is a list of commonly used open data repositories in neuroscience and beyond. 

| Repository        | Description        | Citation | Discipline |
|:-------------|:------------------|:------|:------|
| CRCNS           | A result of a NSF/NIH sponsored collaborative research program, CRCNS is a public archive that shares experimental neuroscience data. | Teeters et al., 2008  | Neuroscience      |
| DANDI | The DANDI archive is a cloud-based repository for sharing and publishing electrophysiology data, including cellular and systems-level recordings. It aims to standardize data sharing and analysis, enabling researchers to easily access, contribute, and reuse complex neurophysiology datasets. | Gosh et al., 2023  |   Neuroscience    |
| NeMO           | The NeMO repository is the access point for genomic data from brain-related research projects. Serving as the primary repository the BRAIN initiative, in addition to a web portal providing searchable access to raw data, the NeMO Archive provides a number of tools: including a direct interface between data and cloud-computing resources, as well as a visualization and analysis platform for the data.     | https://nemoarchive.org   | Neuroscience | 
| OpenNeuro           | OpenNeuro is a free and open platform for sharing MRI, MEG, EEG, iEEG, and other neuroimaging datasets, organized according to the BIDS standard. It promotes open science by enabling researchers to easily publish and access neuroimaging data for collaborative research and analysis. | Markiewicz et al., 2021  | Neuroscience |
| DABI  | DABI is a data repository and portal for projects that collect human and animal intracranial recordings. Serving as a main repository for BRAIN Initiative data, it allows users to search, visualize, and analyze multimodal data from these projects. The data providers maintain full control of data sharing privileges and can organize and manage their data with a user-friendly and intuitive interface. | Ducan et al., 2023 | Neuroscience |
| EBRAINS| EBRAINS provides access to a free and open database of neuroscience data, computational models and software. | https://www.ebrains.eu | Neuroscience |
| Dryad| Dryad is a data publishing platform committed to the open availability and routine re-use of research data. Dryad curates all data and metadata and publishes exclusively under a Creative Commons Public Domain License.| https://datadryad.org/ | Multiple |
| Zenodo| Designed by researchers from the CERN data center, Zenodo’s original aim was for the long term preservation of digital objects for high-energy physics. Zenodo has since expanded into data storage for a number of disciplines. | https://zenodo.org/ | Multiple |
| Figshare| Figshare is a freely available data publishing platform where researchers can share and receive credit for multiple types of scholarly output. Support for larger datasets is also being incorporated.| https://figshare.com/ | Multiple |
| OSF | OSF is a free and open-source project management tool that supports researchers throughout their entire project lifecycle in open science best practices. In addition to manuscript hosting, OSF provides tools to host code and data as well. | https://osf.io/ | Multiple |
| Vivli | Vivli has developed a global data sharing and analytics platform. With a focus on sharing individual participant-level data from completed clinical trials, the non-profit aims to broadly serve the international research community. | https://vivli.org/ | Multiple |


| Format | Description | Citation | Modality(s) |
| :--- | :--- | :--- | :--- |
| **EDF, EDF+** | An early standardized data format used for sleep recordings (EEG, respiration, EMG, etc.). Files include a header record with subject info, time, and signal identification. | (Kemp et al., 1992; Kemp and Olivan 2003) | Electrophysiology |
| **MEF** | Open-source software for high-volume neural data. Features range encoding for compression, 128-bit encryption for patient security, and redundancy checks. | (Brinkmann et al., 2009) | Electrophysiology |
| **Orca** | Also known as BORG; developed by the Allen Institute for electrophysiology and optophysiology data. It is built upon the HDF5-based format. | (Godfrey, 2014; Friedsam, 2016) | Electrophysiology |
| **KWIK** | Part of the Klusta suite for spike sorting. These HDF5-based files store spike times, clusters, and associated metadata. | (Kadir et al., 2014) | Electrophysiology |
| **NEO** | Successor to Neuroshare API; provides a design specification for core neuroscience objects to decouple data representation from downstream analysis. | (Garcia et al., 2014) | Electrophysiology |
| **BRAINformat** | An open-source library defining application-independent design concepts using HDF5 to create a general framework for scientific data standardization. | (Rübel et al., 2016) | Electrophysiology |
| **ONE** | Developed by the IBL consortium for multi-lab sharing. Uses an `object.attribute.extension` naming scheme compatible across various file formats. | (IBL et al., 2023) | Electrophysiology, Imaging, Other |
| **NWB** | A common standard for sharing and archiving neurophysiology data, including intracellular/extracellular electrophysiology, optical physiology, and behavior. | (Teeters et al., 2015; Rubel et al., 2022) | Electrophysiology, Other |
| **DICOM** | The international standard for medical imaging (MRI, CT, X-ray). Defines formats for clinical data exchange and quality across radiology and cardiology. | (NEMA, 1993) | Imaging |
| **NIFTI** | Designed specifically for brain imaging; packages image data and metadata into a single file to simplify sharing and neuroimaging analysis. | (Cox et al., 2004) | Imaging |
| **NIX** | A hierarchical and extensible format designed to store diverse data including electrophysiology, imaging, and behavioral datasets. | (Martone 2014) | Imaging |
| **BIDS** | A standard for organizing and describing neuroimaging (and later EEG) data to promote reproducibility and interoperability across labs and tools. | (Gorgolewski et al., 2016) | Imaging |



| | Package | Description | Citation | Language |
| :--- | :--- | :--- | :--- | :--- |
| 1 | **[Pynapple](https://github.com/PeyracheLab/pynapple)** | A lightweight python package designed to process a broad range of time-resolved data in systems neuroscience, which facilitates analysis through data objects and methods that have the potential to simplify data analysis for neural and behavioral data types. | (Viejo et al. 2023) | Python |
| 2 | **[Spyglass](https://github.com/LorenFrankLab/spyglass)** | An open-source, python based data analysis framework that facilitates the storage, analysis, visualization, and sharing of neuroscience data towards more reproducible research | (Lee and Denovellis et al. 2024) | Python |
| 3 | **[Neurodsp](https://github.com/neurodsp-tools/neurodsp)** | A python-based software package specifically designed to be used for analyzing neural time series data and their time-varying properties | (Cole et al., 2019) | Python |
| 4 | **[GhostiPy](https://github.com/kemerelab/ghostipy)** | A python-based open source software toolbox with implementations of various signal processing and spectral analyses, and prioritizes performance and efficiency through the use of parallelized algorithms | (Chu & Kemere. 2021) | Python |
| 5 | **[bctpy](https://github.com/aestrivex/bctpy)** | Implements many graph theoretical measures to analyze brain activity | (LaPlante, 2013) | Python |
| 6 | **[natverse](https://natverse.org/)** | An R-based suite of toolboxes to perform popular analysis of neuroanatomical data | (Bates et al., 2020) | R |
| 7 | **[NetworkToolbox](https://cran.r-project.org/web/packages/NetworkToolbox/index.html)** | Implements network analysis and graph theory measures used in neuroscience, cognitive science, and psychology. | (Alexander 2018) | R |
| 8 | **[LZeroSpikeInference](https://cran.r-project.org/web/packages/LZeroSpikeInference/index.html)** | A collection of algorithms to determine the exact time at which a neuron spikes on the basis of its fluorescence trace using an L0 penalty. | (Jewell & Witten 2017) | R |
| 9 | **[Brain Connectivity Toolbox](https://sites.google.com/site/bctnet/)** | A popular toolbox used for complex brain-network analysis. | (Rubinov M, Sporns O 2010) | MATLAB |
| 10 | **[Syntropy](https://github.com/thosvarley/syntropy)** | A python library for multivariate information theoretic analysis of discrete and continuous data | (Varley 2025) | Python |
| 11 | **[Cascade](https://github.com/HelmchenLabSoftware/Cascade)** | Cascade translates calcium imaging ΔF/F traces into spiking probabilities or discrete spikes using deep networks | (Rupprecht et al., 2021) | Python |
| 12 | **[BSD](https://github.com/jertubiana/BSD)** | Blind Sparse Deconvolution for inferring spike trains from fluorescence recordings. | (Tubiana et al., 2020) | MATLAB |
| 13 | **[Chronux](http://chronux.org/)** | Open-source software package for the analysis of neural data for both point process and continuous data, ranging from preprocessing, exploratory and confirmatory analysis | (Mitra & Bokil, 2008) | MATLAB |



[back](./)
