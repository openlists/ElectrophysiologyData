# Open Datasets in Electrophysiology

This is a list of openly available electrophysiological data, including EEG, MEG, ECoG/iEEG, and LFP data.

Datasets and resources listed here should all be openly-accessible for research purposes, requiring, at most, registration for access. Be sure to check the license and/or usage agreements for any datasets you access.

To contribute a new link to a data source or resource, open an issue mentioning it, or a pull request with a link.

## Table of Contents

- [Repositories](#repositories)
- [EEG Data](#eeg-data)
- [MEG Data](#meg-data)
- [Human Intracranial Data](#human-intracranial-data)
- [Animal LFP Data](#animal-lfp-data)

## Repositories

There are several repositories, journals, and search engines that can be checked and searched for relevant datasets.

#### General Purpose Data Repositories

There are a few general purpose repositories that you can search for data:
- [Zenodo](https://zenodo.org/) hosts datasets for individual studies. You can find available datasets by searching for 'eeg', 'meg', or similar, and selecting the 'Dataset' tag on the bottom left of the search page.
- [Open Science Framework](https://osf.io/) is a platform for supporting open science, and includes data hosting of open-datasets for specific studies. It doesn't seem to be easily searchable by data modality in particular, but does host relevant datasets, some of which are included in the listings below.
- [Figshare](https://figshare.com) is a general repository service for a broad range of materials, and includes datasets. You can search for resources, and select 'type' as 'Dataset' to see available datasets.
- [Dryad](https://datadryad.org) is a repository service for scientific datasets, and includes data linked to specific papers, including some EEG/MEG/ECoG datasets. There is a search function. 
- [G-Node Open Data](https://doi.gin.g-node.org) is a repository service for scientific datasets, by G-Node (the German Neuroinformatics Node), built on the [G-Node data infrastructure services](https://gin.g-node.org).
- [Kaggle](https://www.kaggle.com) is a private company that hosts data analysis competition. These competitions typically release a dataset for us, and they also maintain a repository of [available datasets](https://www.kaggle.com/datasets).

#### Neuroscience Specific Data Repositories

- [OpenNeuro](https://openneuro.org/) is a free and open platform for analyzing and sharing neuroimaging data. It was originally focused on MRI datasets, but now includes other modalities, including some electrophysiological data.
- [Neurodata Without Borders](https://www.nwb.org), or NWB, is a data standard for neurophysiology, to promote a common standard for storing, sharing, and archiving data. Though not exactly a general repository, they do also maintain a list of publicly released [NWB datasets](https://www.nwb.org/example-datasets/).

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

#### Project: Healthy Brain Networks

A large project including rest and task EEG data across a large adult cohort (n=~1000).

[Home Page](https://fcon_1000.projects.nitrc.org/indi/cmi_healthy_brain_network/index.html) -
[Data Portal](https://fcon_1000.projects.nitrc.org/indi/cmi_healthy_brain_network/sharing_neuro.html#direct-downloads) -
[Paper](https://dx.doi.org/10.1038/sdata.2017.181)

#### Project: Multimodal Resource for Studying Information Processing in the Developing Brain (MIPDB)

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

### Patient Repository for EEG Data + Computational Tools (PREDICT)

PREDICT is a repository for EEG data, focused on patient data (collected in research settings).

[Home Page](http://predict.cs.unm.edu) -
[Data Portal](http://predict.cs.unm.edu/downloads.php) -
[Paper](https://doi.org/10.3389/fninf.2017.00067)

### Temple University Hospital (TUH) Corpus

A large collection of EEG recorded in clinical settings (hospital data).

[Home Page](https://www.isip.piconepress.com/projects/tuh_eeg/) -
[Data Portal](https://www.isip.piconepress.com/projects/tuh_eeg/html/request_access.php) -
[Paper](https://doi.org/10.3389/fnins.2016.00196)

### EEGbase

EEGbase is a database for electrophysiological data.

Note: you first need to register, and then the website has a 'Add to Cart' & 'Complete Order' workflow, but the datasets are free.

[Home Page](https://eegdatabase.kiv.zcu.cz/) -
[Paper](https://doi.org/10.14311/NNW.2012.22.016)

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

### Neuroimaging Tools & Resource Collaboratory (NITRC)

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

ERP-CORE (Compendium of Open Resources and Experiments) is a resource with experiment paradigms and scripts, example data & example processing scripts for ERPs, including the N170, mismatch negativity (MMN), N2pc, N400, P3, lateralized readiness potential (LRP), and error-related negativity (ERN).

[Data](https://osf.io/thsqg/) -
[Paper](https://doi.org/10.31234/osf.io/4azqm)

### BNCI Horizon 2020

A collection of BCI related EEG datasets.

[Home Page](http://bnci-horizon-2020.eu/database/data-sets)

### Montreal Archive of Sleep Studies (MASS)

MASS is a collection of whole night sleep recordings from approximately 200 participants, from hospital based sleep laboratories.

[Home Page](https://massdb.herokuapp.com/en/) -
[Data Portal](https://massdb.herokuapp.com/en/get-access/) -
[Paper](https://doi.org/10.1111/jsr.12169)

### National Sleep Research Resource

NSRR is a resource offering large collections of physiological signals, including polysomnography recordings with EEG from research studies and clinical collections.

[Home Page](https://sleepdata.org/) -
[Data Portal](https://sleepdata.org/datasets) -
[Paper](https://doi.org/10.5665/sleep.5774)

### The Cuban Human Brain Mapping Project

The CHBMP is an open dataset from 282 young and middle age healthy participants, including resting state EEG, and during hyperventilation.

[Data](https://www.synapse.org/#!Synapse:syn22324937) - 
[Paper](https://doi.org/10.6084/m9.figshare.13277348)

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
- EEG resting state data, with MRI anatomical scans (n=12)
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
- An EEG BCI dataset from multiple subjects across multiple paradigms and recording sessions (n=54):
[Data](http://dx.doi.org/10.5524/100542) - 
[Paper](https://doi.org/10.1093/gigascience/giz002)
- A large EEG dataset with a simple gambling task (n=500)
[Data](https://osf.io/65x4v/) - 
[Paper](https://doi.org/10.1111/psyp.13722)
- A large dataset of cross-sectional young and old participants (n=228)
[Homepage](http://fcon_1000.projects.nitrc.org/indi/retro/MPI_LEMON.html) - 
[Data](http://fcon_1000.projects.nitrc.org/indi/retro/MPI_LEMON/downloads/download_EEG.html)
- A dataset comparing different EEG systems, including 3 sessions per participant (n=14)
[Data](https://www.cs.colostate.edu/eeg/main/data/2011-12_BCI_at_CSU)

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

### Open MEG Archive (OMEGA)

OMEGA is a open-access repository for MEG data, in which individual researchers can deposit their data.

[Home Page](https://www.mcgill.ca/bic/resources/omega) - 
[Paper](https://doi.org/10.1016/j.neuroimage.2015.04.028)

### Human Connectome Project (HCP)

The Human-Connectome Project is a large, multi-site project, mostly focused on MRI, but includes a subset of MEG data.

[Home Page](https://www.humanconnectome.org/study/hcp-young-adult)

### Cambridge Center for Ageing Neuroscience (CAMCAN)

CAMCAN includes task & rest data from a large cohort, balanced in age from age 18-88 (n=652).

[Home Page](https://camcan-archive.mrc-cbu.cam.ac.uk/)

### Individual MEG Datasets

- Classification of Multimodal Stimulus Presentation - Visual & Auditory (n=52): 
[Data](https://osf.io/m25n4/) -
[Paper](https://doi.org/10.1371/journal.pcbi.1005938)
- Multi-subject, multimodal face processing dataset including fMRI, MEG, EEG (n=16): 
[Data](https://openneuro.org/datasets/ds000117/versions/1.0.0) - 
[Paper](https://doi.org/10.1038/sdata.2015.1)
- Decaf dataset, movie clip watching (n=30):
[Data](http://mhug.disi.unitn.it/wp-content/DECAF/DECAF.html)

## Human Intracranial Data

This section contains intracranal data from humans participants (only ever collected in clinical contexts), including electrocorticography (ECoG) datasets which is sometimes also referred to as intracranial EEG (iEEG) or stereo-electroencephalography (sEEG), as well as any available human single unit data.

### MNI Open iEEG Atlas

The MNI Open iEEG atlas is a repository of iEEG data from a multi-center collection project (n=106).

[Home Page](https://mni-open-ieegatlas.research.mcgill.ca)

### iEEG.org

iEEG.org is an NIH supported repository of intracranial EEG data.

[Home Page](https://www.ieeg.org)

### University of Pennsylvania Computational Memory Lab

The cognitive electrophysiology data portal has a list of publications that have available electrophysiological data.

[Home Page](https://memory.psych.upenn.edu/Electrophysiological_Data)

The 'Restoring Active Memory' project is coordinate collection of ECoG data, with memory tasks (n=251).

[Home Page](https://memory.psych.upenn.edu/RAM)

### Stanford Collection of ECoG Data

A collection a 16 tasks across a group of ECoG patients (n=250).

[Home Page](https://purl.stanford.edu/zk881ps0522) - 
[Paper](https://doi.org/10.1152/jn.00113.2017)

### Individual ECoG Datasets

- Multicenter resting state and sleep ECoG data:
[Data](https://doi.org/10.6084/m9.figshare.c.4681208.v1) - 
[Paper](https://doi.org/10.1038/s41597-020-0532-5)
- ECoG data from a study looking at sensorimotor alpha and beta activity (n=3):
[Data](https://osf.io/z4hfm/) - 
[Paper](https://doi.org/10.7554/eLife.48065)

### Human Single Unit Data

Available datasets with single unit data from humans:
- Human single units with a declarative memory task (n=59):
[Data](https://osf.io/hv7ja/) - 
[Paper](https://doi.org/10.1038/s41597-020-0415-9) - 
[Associated Code](https://github.com/rutishauserlab/recogmem-release-NWB)
- Human single units with a verbal working memory task, also including iEEG data (n=9):
[Data](https://gin.g-node.org/USZ_NCH/Human_MTL_units_scalp_EEG_and_iEEG_verbal_WM) -
[Paper](https://www.nature.com/articles/s41597-020-0364-3)
- Human single units from the amygdala, with visual presentation of neutral and aversize stimuli (n=9):
[Data](https://doi.gin.g-node.org/10.12751/g-node.270z59/) - 
[Paper](https://doi.org/10.1038/s41597-020-00790-x)

## Animal LFP Data

Openly available animal datasets with local field potential (LFP) data, include multi-electrode arrays, animal ECoG, single-units, or similar recordings. 

### NeuroTycho

NeuroTycho is as collection of mostly monkey ECoG data.

[Home Page](http://neurotycho.org)

### Collaborative Research in Computational Neuroscience (CRCNS)

A collection of data, mostly animal models, including extra-cellular recordings, and some animal model ECoG & iEEG.

[Home Page](https://crcns.org) - 
[Data Portal](https://crcns.org/data-sets/) - 
[Paper](https://doi.org/10.1007/s12021-008-9009-y)

### Buzsáki Lab Webshare

This contains electrophysiological datasets collected from rodents in the Buzsáki lab.

[Home Page](https://buzsakilab.nyumc.org/datasets/) - 
[Buzsáki lab website](https://buzsakilab.com/wp/)

### Individual LFP Datasets

The following are available individual LFP datasets:

- LFP during during delayed reach-to-grasp task (macaque monkey, n=2):
[Data](https://gin.g-node.org/INT/multielectrode_grasp) - 
[Paper](https://doi.org/10.1038/sdata.2018.55)
