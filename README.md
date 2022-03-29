# Open Datasets in Electrophysiology

This is a list of openly available electrophysiological data, including EEG, MEG, ECoG/iEEG, and LFP data.

Datasets and resources listed here should all be openly-accessible for research purposes, requiring, at most, registration for access. Be sure to check the license and/or usage agreements for any datasets you access.

To contribute a new link to a data source or resource, open an issue mentioning it, or a pull request with a link.

## Table of Contents

- [Data Formats](#data-formats)
- [Repositories](#repositories)
- [EEG Data](#eeg-data)
- [MEG Data](#meg-data)
- [Human Intracranial Data](#human-intracranial-data)
- [Animal LFP Data](#animal-lfp-data)
- [Behavioral Data](#behavioral-data)

## Data Formats

The datasets listed here are not guaranteed to be in any particular format. Whenever possible, using standardized data formats can help make datasets more inter-operable.

Standardized data formats for neurophysiological data include:
- [Neurodata Without Borders](https://www.nwb.org), or NWB, is a general data standard for neurophysiology, with the goal of promoting a common standard for storing, sharing, and archiving data. The NWB project also maintains a list of publicly available [NWB datasets](https://www.nwb.org/example-datasets/).
- [Brain Imaging Data Structure](https://bids.neuroimaging.io/), or BIDS, is a set of data standards for imaging data, including
[MRI](https://www.nature.com/articles/sdata201644),
[EEG](https://www.nature.com/articles/s41597-019-0104-8),
[MEG](https://www.nature.com/articles/sdata2018110), and
[iEEG](https://www.nature.com/articles/s41597-019-0105-7).

## Repositories

There are several repositories, journals, and search engines that can be checked and searched for relevant datasets.

#### Neuroscience Specific Data Repositories

- [OpenNeuro](https://openneuro.org/) is a platform for analyzing and sharing neuroimaging data. Originally focused on MRI datasets, it now includes other modalities, including some electrophysiological data. Data on OpenNeuro is generally organized in BIDS formats.
- The [DANDI](https://gui.dandiarchive.org/#/) archive ('distributed archives for neurophysiological data integration') is a platform for sharing and processing neurophysiological data. It includes a list of [public datasets](https://gui.dandiarchive.org/#/dandiset). Data on DANDI is generally organized in NWB format.
- The [DABI](https://dabi.loni.usc.edu/home) repository ('data archive BRAIN initiative') is a platform for storing and processing invasive neurophysiological data, in particular for the BRAIN initiative.
- The [EBrains](https://ebrains.eu/) platform for the European Union's 'Human Brain Project' includes a data portal with available data, including some extra- and intra-cranial human recordings

#### General Purpose Data Repositories

There are a few general purpose repositories that you can search for data:
- [Zenodo](https://zenodo.org/) hosts datasets for individual studies. You can find available datasets by searching for 'eeg', 'meg', or similar, and selecting the 'Dataset' tag on the bottom left of the search page.
- [Open Science Framework](https://osf.io/) is a platform for supporting open science, and includes data hosting of open-datasets for specific studies. It doesn't seem to be easily searchable by data modality in particular, but does host relevant datasets, some of which are included in the listings below.
- [Figshare](https://figshare.com) is a general repository service for a broad range of materials, and includes datasets. You can search for resources, and select 'type' as 'Dataset' to see available datasets.
- [Dryad](https://datadryad.org) is a repository service for scientific datasets, and includes data linked to specific papers, including some EEG/MEG/ECoG datasets. There is a search function.
- [G-Node Open Data](https://doi.gin.g-node.org) is a repository service for scientific datasets, by G-Node (the German Neuroinformatics Node), built on the [G-Node data infrastructure services](https://gin.g-node.org).
- [Harvard Dataverse](https://dataverse.harvard.edu/) is a general-purpose repository for research data, that includes some neuroscience data
- [Science Data Bank](https://www.scidb.cn/en) is a general-purpose repository for research data, that includes some neuroscience data
- [Kaggle](https://www.kaggle.com) is a private company that hosts data analysis competitions. These competitions typically include a dataset, and they also maintain a repository of [available datasets](https://www.kaggle.com/datasets).

#### Data Journals

There are journals that specifically describe openly available datasets, and/or mandate that data be openly released, including:

- [Scientific Data](https://www.nature.com/sdata/)
    - A general purpose journal that publishes brief reports on openly available datasets
- [Data in Brief](https://www.journals.elsevier.com/data-in-brief)
    - A general purpose journal that publishes brief reports on openly available datasets
- [GigaScience](https://academic.oup.com/gigascience)
    - A general topic journal that publishes papers for which all associated data must be made available
    - Data is uploaded to their [GigaDB](https://gigadb.org/) database, that is searchable

#### Data Search Engines

Google has a [dataset search](https://datasetsearch.research.google.com/) tool that can be used to search for datasets.

## EEG Data

Openly available electroencephalography (EEG) datasets and large-scale projects with EEG data.

### ChildMind Institute

The [ChildMind Institute](https://childmind.org) is a non-profit that, amongst other things, is involved in large-scale research projects that release large datasets.

#### HBN - Healthy Brain Networks

A large project including rest and task EEG data across a large adult cohort (n=~1000).

[Home Page](https://fcon_1000.projects.nitrc.org/indi/cmi_healthy_brain_network/index.html) -
[Data Portal](https://fcon_1000.projects.nitrc.org/indi/cmi_healthy_brain_network/sharing_neuro.html#direct-downloads) -
[Paper](https://dx.doi.org/10.1038/sdata.2017.181)

#### MIPDB - Multimodal Resource for Studying Information Processing in the Developing Brain

A project including rest and task EEG data across a young cohort, ages 6-44 (n=126).

[Home Page](https://fcon_1000.projects.nitrc.org/indi/cmi_eeg/index.html) -
[Data Portal](https://fcon_1000.projects.nitrc.org/indi/cmi_eeg/eeg.html) -
[Paper](https://doi.org/10.1038/sdata.2017.40)

### Physionet

Physionet is an archive of physiology data, and includes some EEG data under the 'neuroelectric' tag.

[Home Page](https://physionet.org) -
[Data Portal](https://physionet.org/physiobank/database/#neuro) -
[Paper](https://doi.org/10.1161/01.CIR.101.23.e215)

Available datasets include:
- EEG Motor Movement / Imagery (n=109):
[Data](https://www.physionet.org/pn4/eegmmidb/)

### PREDICT - Patient Repository for EEG Data + Computational Tools

PREDICT is a repository for EEG data, focused on patient data (collected in research settings).

[Home Page](http://predict.cs.unm.edu) -
[Data Portal](http://predict.cs.unm.edu/downloads.php) -
[Paper](https://doi.org/10.3389/fninf.2017.00067)

### TUH - Temple University Hospital Corpus

A large collection of EEG recorded in clinical settings (hospital data).

[Home Page](https://www.isip.piconepress.com/projects/tuh_eeg/) -
[Data Portal](https://www.isip.piconepress.com/projects/tuh_eeg/html/request_access.php) -
[Paper](https://doi.org/10.3389/fnins.2016.00196)

### EEGbase

EEGbase is a database for electrophysiological data.

[Home Page](https://eegdatabase.kiv.zcu.cz/) -
[Paper](https://doi.org/10.14311/NNW.2012.22.016)

Note: you need to register, and the website has a 'Add to Cart' & 'Complete Order' workflow, but the datasets are free.

Available datasets include:
- ERP Dataset, Visual P300 Paradigm (n=20):
[Paper](https://doi.org/10.1186/2047-217X-3-35)
  - Note that this data is also available on GigaDB
- ERP OddBall Design, Number Guessing Game  (n=250):
[Paper](https://doi.org/10.1038/sdata.2016.121)
- ERP dataset on Developmental Coordination Disorder (n=32):
[Paper](https://doi.org/10.1093/gigascience/gix002)
- EEG activity using a driving simulator (n=15):
[Paper](https://doi.org/10.5220/0006249504410450)

### NITRC - Neuroimaging Tools & Resource Collaboratory

NITRC is a general purpose repository community board for neuroimaging tools, resources, and datasets. It is generally more focused on tools than datasets, but it does contain some available EEG datasets.

[Home Page](https://www.nitrc.org/) -
[Paper](https://doi.org/10.1016/j.neuroimage.2015.05.074)

Available datasets include:
- Visual Oddball Task (n=18):
[Data](https://www.nitrc.org/projects/vep_eeg_raw) -
[Paper](https://doi.org/10.1016/j.dib.2017.11.032)
- Categorization Task (n=14):
[Data](https://www.nitrc.org/projects/eegdataanimal)
- Resting State fMRI/EEG (n=8):
[Data](https://www.nitrc.org/projects/cwleegfmri_data)

### ERP-CORE

ERP-CORE (Compendium of Open Resources and Experiments) is a resource with experiment paradigms and scripts, example data & example processing scripts for ERPs, including the N170, mismatch negativity (MMN), N2pc, N400, P300, lateralized readiness potential (LRP), and error-related negativity (ERN).

[Data](https://osf.io/thsqg/) -
[Paper](https://doi.org/10.31234/osf.io/4azqm)

### BNCI Horizon 2020

A collection of BCI related EEG datasets.

[Home Page](http://bnci-horizon-2020.eu/database/data-sets)

### MASS - Montreal Archive of Sleep Studies

MASS is a collection of whole night sleep recordings from approximately 200 participants, from hospital based sleep laboratories.

[Home Page](https://massdb.herokuapp.com/en/) -
[Data Portal](https://massdb.herokuapp.com/en/get-access/) -
[Paper](https://doi.org/10.1111/jsr.12169)

### NSRR - National Sleep Research Resource

NSRR is a resource offering large collections of physiological signals, including polysomnography recordings with EEG from research studies and clinical collections.

[Home Page](https://sleepdata.org/) -
[Data Portal](https://sleepdata.org/datasets) -
[Paper](https://doi.org/10.5665/sleep.5774)

### The Cuban Human Brain Mapping Project

The CHBMP is an open dataset from 282 young and middle age healthy participants, including resting state EEG, and during hyperventilation.

[Data](https://www.synapse.org/#!Synapse:syn22324937) -
[Paper](https://doi.org/10.1038/s41597-021-00829-7)

### LEMON - Leipzig Study for Mind-Body-Emotion Interactions

A large multimodal dataset (n=228), with cross-sectional sampling of young and old participants, and including MRI, EEG, physiological, clinical and cognitive measures.

[Homepage](https://doi.org/10.15387/fcp_indi.mpi_lemon) -
[Data](http://fcon_1000.projects.nitrc.org/indi/retro/MPI_LEMON/downloads/download_EEG.html) -
[Paper](https://doi.org/10.1038/sdata.2018.308)

### Lab-Specific Data Collections

The following labs are collections of datasets from particular labs:
- Narayanan lab: predominantly EEG datasets collected from humans, including Parkinson's patients:
[Datasets](https://narayanan.lab.uiowa.edu/article/datasets) -
[Lab website](https://narayanan.lab.uiowa.edu/)

### Individual EEG Datasets (Research Systems)

The following are datasets collected with research EEG systems:
- Motor Imagery BCI Data (n=52):
[Data](http://gigadb.org/dataset/100295) -
[Paper](https://doi.org/10.5524/100295)
- Simultaneous EEG & NIRS during cognitive tasks (n=26):
[Data](https://depositonce.tu-berlin.de//handle/11303/6271.2) -
[Paper](https://doi.org/10.1038/sdata.2018.3)
- EEG during grasp and lift (n=12):
[Data](https://doi.org/10.6084/m9.figshare.988376) -
[Paper](https://doi.org/10.1038/sdata.2014.47)
- EEG, MEG & fMRI data with perceptual task (n=19):
[Data](https://openneuro.org/datasets/ds000117/versions/00004) -
[Paper](https://doi.org/10.1038/sdata.2015.1)
- EEG data with TMS with visual perception task (n=16):
[Data](https://datadryad.org/resource/doi:10.5061/dryad.1nr07) -
[Paper](https://doi.org/10.1038/sdata.2016.65)
- EEG with Motion Capture during treadmill walking (n=8):
[Data](https://doi.org/10.6084/m9.figshare.c.3894013.v1) -
[Paper](https://doi.org/10.1038/sdata.2018.74)
- EEG data with a visual spatial attention task (n=45):
[Data](https://osf.io/bwzfj) -
[Paper](https://doi.org/10.1152/jn.00860.2015)
- EEG data with a visual working memory task, ERP design (n=104):
[Data](https://osf.io/a65xz/ ) -
[Paper](https://doi.org/10.1093/cercor/bhx336)
- EEG data with a visual working memory task, CDA design (n=76):
[Data](https://osf.io/8xuk3) -
[Paper](https://doi.org/10.1162/jocn_a_01233)
- EEG data with a covert visual spatial attention task (n=50):
[Data](https://osf.io/m64ue) -
[Paper](https://doi.org/10.1177/0956797617699167)
- OpenMIIR: EEG data during music perception and imagination (n=10):
[Home Page](http://www.owenlab.uwo.ca/research/the_openmiir_dataset.html) -
[Data](http://www.ling.uni-potsdam.de/mlcog/OpenMIIR-RawEEG_v1/)
- EEG data from subjects napping after a working memory task (n=22):
[Data](https://osf.io/chav7/) -
[Paper](https://doi.org/10.1016/j.compbiomed.2017.08.030)
- DEAP: Database for Emotion Analysis, EEG data + video recording, while watching videos (n=32):
[Data](http://www.eecs.qmul.ac.uk/mmv/datasets/deap/) -
[Paper](https://doi.org/10.1109/T-AFFC.2011.15)
- A collection of EEG tasks with speech studies (n=84, split across 5 tasks):
[Data](https://doi.org/10.5061/dryad.070jc) -
[Paper](https://doi.org/10.1016/j.cub.2018.01.080)
- EEG recordings with concurrent EMG while doing everyday tasks (n=27):
[Data](http://researchdata.gla.ac.uk/676/)
- Multi-modal (EEG, EMG, EOG) recordings during movement tasks (n=25):
[Data](http://dx.doi.org/10.5524/100788) -
[Paper](https://doi.org/10.1093/gigascience/giaa098)
- EEG BCI recordings during mental imagery, across sessions & interaction paradigms (n=13):
[Data](https://doi.org/10.6084/m9.figshare.c.3917698.v1) -
[Paper](https://doi.org/10.1038/sdata.2018.211)
- EEG resting state data, with MRI anatomical scans (n=12):
[Data](https://doi.org/10.5061/dryad.v9f16) -
[Paper]( https://doi.org/10.1371/journal.pone.0146845)
- Multi-day, multi band SSVEP dataset for BCI applications (n=30):
[Data](https://doi.org/10.5524/100660) -
[Paper](https://doi.org/10.1093/gigascience/giz133)
- Multi-day, dataset from sleep (naps) recorded after visual working memory task (n=22):
[Data](https://osf.io/chav7/) -
[Paper](https://doi.org/10.1016/j.dib.2018.04.073)
- EEG dataset from subjects viewing images (n=24):
[Data](https://doi.org/10.12751/g-node.bcccab) -
[Paper](https://doi.org/10.1016/j.dib.2019.103857)
- EEG data with resting state and visual working memory task (n=43):
[Dataset1](https://openneuro.org/datasets/ds003420/versions/1.0.2) -
[Dataset2](https://openneuro.org/datasets/ds003421/versions/1.0.2) -
[Paper](https://doi.org/10.1038/s41597-021-00821-1)
- EEG from participants playing an 8-bit style video game (n=17):
[Data](https://openneuro.org/datasets/ds003517/versions/1.1.0) -
[Paper](https://www.sciencedirect.com/science/article/abs/pii/S1053811916001932?via%3Dihub)
- An EEG/BCI dataset across multiple paradigms and recording sessions (n=54):
[Data](http://dx.doi.org/10.5524/100542) -
[Paper](https://doi.org/10.1093/gigascience/giz002)
- A large EEG dataset with a simple gambling task (n=500):
[Data](https://osf.io/65x4v/) -
[Paper](https://doi.org/10.1111/psyp.13722)
- A dataset comparing different EEG systems, including 3 sessions per participant (n=14):
[Data](https://www.cs.colostate.edu/eeg/main/data/2011-12_BCI_at_CSU)
- An EEG/BCI dataset for inner speech recognition (n=10):
[Data](https://openneuro.org/datasets/ds003626/versions/1.0.1) -
[Paper](https://www.biorxiv.org/content/10.1101/2021.04.19.440473v1)
- An EEG/BCI sensorimotor dataset, with longitudinal data (n=62):
[Data](https://doi.org/10.6084/m9.figshare.13123148) -
[Paper](https://www.nature.com/articles/s41597-021-00883-1)
- An EEG dataset of with rapid serial visual presentation (n=50):
[Data](https://doi.org/10.18112/openneuro.ds003825.v1.1.0) -
[Paper](https://doi.org/10.1038/s41597-021-01102-7)
- A dataset of hdEEG during transcranial electrical stimulation (n=20):
[Data](https://zenodo.org/record/4456079) -
[Paper](https://doi.org/10.1038/s41597-021-01046-y)
- Mobile BCI dataset of scalp and ear EEG with ERP and SSVEP paradigms while standing and moving (n=24):
[Data](https://doi.org/10.17605/OSF.IO/R7S9Bhttps) -
[Paper](https://doi.org/10.1038/s41597-021-01094-4)
- Polysomnography dataset, including 3 EEG channels, for sleep apnea studies (n=212):
[Data](https://doi.org/10.11922/sciencedb.00345) -
[Paper](https://doi.org/10.1038/s41597-021-00977-w)
- EEG and EMG data during perturbed walking and standing (n=30):
[Data](https://doi.org/10.1016/j.dib.2021.107635) -
[Paper](https://doi.org/10.1016/j.dib.2021.107635)
- EEG data in subjects with claustrophobia, and controls, resting state in different sized rooms (n=22):
[Data](https://doi.org/10.1016/j.dib.2021.107733) -
[Paper](https://doi.org/10.1016/j.dib.2021.107733)
- A dataset of arm motion in healthy and post-stroke subjects, with some EEG data (n=45 with EEG):
[Data](https://doi.org/10.7910/DVN/FU3QZ9) -
[Paper](https://doi.org/10.1093/gigascience/giab043)
- A dataset of EEG and behavioral data with a visual working memory task in virtual reality (n=47):
[Data](https://osf.io/s9xmu/) -
[Paper](https://doi.org/10.1016/j.dib.2022.107827)

### Individual EEG Datasets (Consumer Systems)

The following are available datasets collected with consumer EEG systems:
- MNIST of Brain Data from MindBigData (n=1 with 1.2 million trials):
[Data](http://mindbigdata.com/opendb/index.html)
- ImageNet of the Brain from MindBigData (n=1 with 70,000 trials):
[Data](http://mindbigdata.com/opendb/imagenet.html)

### Other lists of EEG Data

There are some other lists of available EEG data, including:
- A publicly [curated list](https://github.com/meagmohit/EEG-Datasets) list of EEG data
- The [SCCN list](https://sccn.ucsd.edu/~arno/fam2data/publicly_available_EEG_data.html) of public EEG data

## MEG Data

Openly available magnetoencephalography (MEG) datasets and large-scale projects with MEG data.

### OMEGA - Open MEG Archive

OMEGA is a open-access repository for MEG data, in which individual researchers can deposit their data.

[Home Page](https://www.mcgill.ca/bic/resources/omega) -
[Paper](https://doi.org/10.1016/j.neuroimage.2015.04.028)

### HCP - Human Connectome Project

The Human-Connectome Project is a large, multi-site project, mostly focused on MRI, that also includes a subset of MEG data.

[Home Page](https://www.humanconnectome.org/study/hcp-young-adult)

### CAMCAN - Cambridge Center for Ageing Neuroscience

CAMCAN includes task & rest MEG data from a large cohort, balanced in age from age 18-88 (n=652).

[Home Page](https://camcan-archive.mrc-cbu.cam.ac.uk/)

### Individual MEG Datasets

The following are openly available datasets with MEG data:
- 'Mother of unification studies' (MOUS) dataset, resting state and language task (n=204):
[Data](https://data.donders.ru.nl/collections/di/dccn/DSC_3011020.09_236?0) -
[Paper](https://www.nature.com/articles/s41597-019-0020-y)
- Classification of Multimodal Stimulus Presentation - Visual & Auditory (n=52):
[Data](https://osf.io/m25n4/) -
[Paper](https://doi.org/10.1371/journal.pcbi.1005938)
- Multi-subject, multimodal face processing dataset including fMRI, MEG, EEG (n=16):
[Data](https://openneuro.org/datasets/ds000117/versions/1.0.0) -
[Paper](https://doi.org/10.1038/sdata.2015.1)
- Decaf dataset, movie clip watching (n=30):
[Data](http://mhug.disi.unitn.it/wp-content/DECAF/DECAF.html)
- MEG data during four mental imagery tasks, for BCI analyses (n=17):
[Data](https://doi.org/10.6084/m9.figshare.c.5101544) -
[Paper](https://doi.org/10.1038/s41597-021-00899-7)

## Human Intracranial Data

This section contains intracranial EEG (iEEG) data from humans participants (collected in clinical contexts), including electrocorticography (ECoG) and stereo-EEG (sEEG) recordings, as well as any available human single unit data.

### MNI Open iEEG Atlas

The MNI Open iEEG atlas is a multi-center repository of curated iEEG data, including resting state (n=106) and sleep (n=91) data.

[Home Page](https://mni-open-ieegatlas.research.mcgill.ca) -
[Paper (rest data)](https://doi.org/10.1093/brain/awy035) -
[Paper (sleep data)](https://doi.org/10.1002/ana.25651)

### iEEG.org

iEEG.org is an NIH supported repository of intracranial EEG data.

[Home Page](https://www.ieeg.org)

### University of Pennsylvania Computational Memory Lab

The cognitive electrophysiology data portal has a list of publications that have available electrophysiological data.

[Home Page](https://memory.psych.upenn.edu/Electrophysiological_Data)

The 'Restoring Active Memory' project is coordinate collection of ECoG data, with memory tasks (n=251).

[Home Page](https://memory.psych.upenn.edu/RAM)

### Kai Miller's Collection of ECoG Data

A collection of ECoG recordings, including 204 sessions from across 16 different tasks (n=34).

[Home Page](https://purl.stanford.edu/zk881ps0522) -
[Paper](https://doi.org/10.1152/jn.00113.2017)

### Individual ECoG Datasets

The following are openly available datasets with human intracranial data:
- Multicenter resting state and sleep ECoG data, annotated for artifacts (n=39):
[Data](https://doi.org/10.6084/m9.figshare.c.4681208.v1) -
[Paper](https://doi.org/10.1038/s41597-020-0532-5)
- ECoG data from a study looking at sensorimotor alpha and beta activity (n=3):
[Data](https://osf.io/z4hfm/) -
[Paper](https://doi.org/10.7554/eLife.48065)
- A multimodal dataset of iEEG with fMRI, with audio-visual stimuli (n=51):
[Data](https://openneuro.org/datasets/ds003688) -
[Paper](https://www.biorxiv.org/content/10.1101/2021.06.09.447733v1)
- A dataset of long-term iEEG recordings of naturalistic data & pose estimation (n=12):
[Data](https://gui.dandiarchive.org/#/dandiset/000055/) -
[Paper](https://www.biorxiv.org/content/10.1101/2021.07.26.453884v1.abstract)
- Data from subjects with simultaneous EEG recordings and intracranial electrical stimulation (n=7):
[Data](https://doi.org/10.25493/NXN2-05W) -
[Paper](https://doi.org/10.1038/s41597-020-0467-x)
- Intracranial data during visual scene recognition of famous landmarks (n=50):
[Data](https://dabi.loni.usc.edu/dsi/1U01NS098981) -
[Paper](https://doi.org/10.1038/s41597-022-01125-8)
- Intracranial data during memory tasks with pupillometry (n=10):
[Data](https://doi.org/10.25493/GKNT-T3X) -
[Paper](https://www.nature.com/articles/s41597-021-01099-z)
- Intracranial data investigating responses to single-pulse stimulation (n=52):
[Data](https://dabi.loni.usc.edu/dsi/W4SNQ7HR49RL) - 
[Paper](https://doi.org/10.1016/j.brs.2022.02.017)

### Human Single Unit Data

Available datasets with single unit data from humans:
- Human single units with a declarative memory task (n=59):
[Data](https://osf.io/hv7ja/) -
[Paper](https://doi.org/10.1038/s41597-020-0415-9) -
[Associated Code](https://github.com/rutishauserlab/recogmem-release-NWB)
- Human single units with a verbal working memory task, also including iEEG data (n=9):
[Data](https://gin.g-node.org/USZ_NCH/Human_MTL_units_scalp_EEG_and_iEEG_verbal_WM) -
[Paper](https://www.nature.com/articles/s41597-020-0364-3)
- Human single units from the amygdala, with visual presentation of neutral and aversive stimuli (n=9):
[Data](https://doi.gin.g-node.org/10.12751/g-node.270z59/) -
[Paper](https://doi.org/10.1038/s41597-020-00790-x)
- Single unit data from neuropixel probes in human cortex (n=3):
[Data](https://doi.org/10.5061/dryad.d2547d840) -
[Paper](https://doi.org/10.1101/2021.06.20.449152)

## Animal LFP Data

Openly available animal datasets with local field potential (LFP) data, including multi-electrode arrays, animal ECoG, single-units, or similar recordings.

### NeuroTycho

NeuroTycho is as collection of mostly monkey ECoG data.

[Home Page](http://neurotycho.org)

### Collaborative Research in Computational Neuroscience (CRCNS)

A collection of data, including extra-cellular recordings, and some ECoG & iEEG, from various species.

[Home Page](https://crcns.org) -
[Data Portal](https://crcns.org/data-sets/) -
[Paper](https://doi.org/10.1007/s12021-008-9009-y)

### Lab-Specific Data Collections

The following labs are collections of datasets from particular labs:

- Buzsáki lab: electrophysiological datasets collected from rodents:
[Datasets](https://buzsakilab.nyumc.org/datasets/) -
[Lab website](https://buzsakilab.com/wp/)
- Giocomo Lab: neural data recorded from rodents:
[Datasets](https://giocomolab.weebly.com/data.html) -
[Lab website](https://giocomolab.weebly.com/)

### Individual Datasets

The following are available individual LFP and related datasets:

- LFP during during delayed reach-to-grasp task (macaque monkey, n=2):
[Data](https://gin.g-node.org/INT/multielectrode_grasp) -
[Paper](https://doi.org/10.1038/sdata.2018.55)
- Raw LFP recordings and spiking data during anesthesia (rats, n=20):
[Data](https://gin.g-node.org/UlbertLab/High_Resolution_Cortical_Spikes) -
[Paper](https://doi.org/10.1038/s41597-021-00970-3)
- Whole-cell intracellular recordings from somatosensory cortex (mouse, n=195):
[Data](https://doi.org/10.5524/100535) -
[Paper](https://doi.org/10.1093/gigascience/giy147)
- High channel count (1024) Utah array recordings in macaque V1 and V4 from resting state (n=2):
[Data](https://doi.gin.g-node.org/10.12751/g-node.i20kyh/) -
[Paper](https://doi.org/10.1038/s41597-022-01180-1)

## Behavioral Data

This list does not currently track behaviour-only data.

See this [list of available behavioral data](https://nivlab.github.io/opendata/).

