# Open Datasets in Electrophysiology

This is a list of openly available electrophysiological data, including EEG, MEG, ECoG/iEEG, and LFP data.

Datasets and resources listed here should all be openly-accessible for research purposes, requiring, at most, registration for access. Be sure to check the license and/or usage agreements for any datasets you access. 

To contribute a new link to a data source or resource, open an issue mentioning it, or a pull request with a link. 

## Table of Contents

- [Repositories](#repositories)
- [EEG](#eeg)
- [MEG](#meg)
- [ECoG](#ecog)
- [LFP](#lfp)

## General Repositories

There are several repositories, journals, and search engines that can be checked and searched for relevant datasets. 

#### General Purpose Data Repositories

There are a few general purpose repositories that you can search for data:
- [Zenodo](https://zenodo.org/) hosts datasets for individual studies. You can find available datasets by searching for 'eeg', 'meg', or similar, and selecting the 'Dataset' tag on the bottom left of the search page. 
- [Open Science Framework](https://osf.io/) is a platform for supporting open science, and includes, amongst other things, data hosting of open-datasets for specific studies. It doesn't seem to be easily searchable by data modality in particular, does does host relevant data, some of which are included in the listings below.
- [Figshare](https://figshare.com) is a general repository service for a broad range of materials, and includes datasets. You can search for a data type, or other specifier, and the select 'type' as 'Dataset' to see available datasets. 
- [Dryad](https://datadryad.org) is a repository service for scientific datasets, and includes data linked to specific papers, that is searchable, and includes some EEG/MEG/ECoG datasets.
- [Kaggle](https://www.kaggle.com) is a private company that hosts data analysis competition. These competitions typically release a dataset for us, and they also maintain a repository of [available datasets](https://www.kaggle.com/datasets).

#### Neuroscience Specific Data Repositories

- [OpenNeuro](https://openneuro.org/) is a free and open platform for analyzing and sharing neuroimaging data. It is currently more focused on MRI datasetes, but includes at least one EEG-fMRI dataset, and may expand to include more electrophysiology data. 

#### Data Journals

There are journals that specifically describe openly available datasets, and/or mandate that data be openly released, including:

- [Scientific Data](https://www.nature.com/sdata/)
    - A general purpose journal that publishes brief reports on openly available datasets
- [Data in Brief](https://www.journals.elsevier.com/data-in-brief)
    - A general purpose journal that publishes brief reports on openly available datasets
- [GigaScience](http://www.gigasciencejournal.com)
    - A general topic journal that publishes papers for which all associated data must be made available
    - Data is uploaded to their [GigaDB](http://gigadb.org) database, that is searchable 

#### Data Search Engines

Google has a new [dataset search](https://datasetsearch.research.google.com/) that can be used to search for datasets. 

## EEG

Openly available electroencephalography (EEG) datasets and large-scale projects with EEG data.

### ChildMind Institute

The [ChildMind Institute](https://childmind.org) is a non-profit that, amongst other things, is involved in large-scale research projects that release large datasets. 

#### Project: Healthy Brain Networks

A large project including rest and task EEG data across a large adult cohort (n~1000).

[Home Page](http://fcon_1000.projects.nitrc.org/indi/cmi_healthy_brain_network/index.html) - [Data Portal](http://fcon_1000.projects.nitrc.org/indi/cmi_healthy_brain_network/sharing_neuro.html#direct-downloads) - [Paper](https://dx.doi.org/10.1038/sdata.2017.181)

#### Project: Multimodal Resource for Studying Information Processing in the Developing Brain (MIPDB)

A project including rest and task EEG data across a young cohort, ages 6-44 (n=126).

[Home Page](http://fcon_1000.projects.nitrc.org/indi/cmi_eeg/index.html) - [Data Portal](http://fcon_1000.projects.nitrc.org/indi/cmi_eeg/eeg.html) - [Paper](https://doi.org/10.1038/sdata.2017.40)

### Physionet

Physionet is an archive of physiology data, and includes some EEG data under the 'neuroelectric' tag. 

[Home Page](https://physionet.org) - [Data Portal](https://physionet.org/physiobank/database/#neuro) - [Paper](https://doi.org/10.1161/01.CIR.101.23.e215)

Available datasets include:
- EEG Motor Movement / Imagery (n=109) [Data](https://www.physionet.org/pn4/eegmmidb/)

### Patient Repository for EEG Data + Computational Tools (PREDICT)

PREDICT is a repository for EEG data, focused on patient data (collected in research settings). 

[Home Page](http://predict.cs.unm.edu) - [Data Portal](http://predict.cs.unm.edu/downloads.php) - [Paper](https://doi.org/10.3389/fninf.2017.00067)

### Temple University Hospital (TUH) Corpus

A large collection of EEG recorded in clinical settings (hospital data). 

[Home Page](https://www.isip.piconepress.com/projects/tuh_eeg/) - [Data Portal](https://www.isip.piconepress.com/projects/tuh_eeg/html/request_access.php) - [Paper](https://doi.org/10.3389/fnins.2016.00196)

### EEGbase

EEGbase is a database for electrophysiological data. 

Note: the website has a 'Add to Cart' & 'Complete Order' workflow, but the datasets are free.

[Home Page](http://eegdatabase.kiv.zcu.cz/) - [Data Portal](http://eegdatabase.kiv.zcu.cz/L7ExSNbPC4sb6TPJDblCAjFENzhnNxd-qPG-ZJnFrBMnNke5sKkAFKtpliBHROBF3s3qpdiUIEwpYvha0jOAjZOeyglcMlt0e6guRuQwbtI/L7E59/jOA9b/BF3be) - [Paper](https://doi.org/10.14311/NNW.2012.22.016)

Available datasets include:
- ERP Dataset, Visual P300 Paradigm (n=20): [Paper](https://doi.org/10.1186/2047-217X-3-35)
  - Note that this data is also available on GigaDB
- ERP OddBall Design, Number Guessing Game  (n=250): [Paper](https://doi.org/10.1038/sdata.2016.121)
- ERP dataset on Developmental Coordination Disorder (n=32): [Paper](https://doi.org/10.1093/gigascience/gix002)
- EEG activity using a driving simulator (n=15): [Paper](https://doi.org/10.5220/0006249504410450)

### Neuroimaging Tools & Resource Collaboratory (NITRC)

NITRC is a general purpose repository community board for neuroimaging tools, resources, and datasets. In general, is has more tools than datasets listed, and there is nothing specific to EEG about it, but it does contain some available EEG datasets. 

[Home Page](https://www.nitrc.org/) - [Paper](https://doi.org/10.1016/j.neuroimage.2015.05.074)

Available datasets include:
- Visual Oddball Task (n=18): [Data](https://www.nitrc.org/projects/vep_eeg_raw) - [Paper](https://doi.org/10.1016/j.dib.2017.11.032)
- Categorization Task (n=14): [Data](https://www.nitrc.org/projects/eegdataanimal)
- Resting State fMRI/EEG (n=8): [Data](https://www.nitrc.org/projects/cwleegfmri_data)

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

### Individual EEG Datasets (Research Systems)

The following are datasets collected with research EEG systems:

- Motor Imagery BCI Data (n=52): [Data](http://gigadb.org/dataset/100295) - [Paper](https://doi.org/10.5524/100295)
- Simultaneous EEG & NIRS during cognitive tasks (n=26): [Data](https://depositonce.tu-berlin.de//handle/11303/6271.2) - [Paper](https://doi.org/10.1038/sdata.2018.3)
- EEG during grasp and lift (n=12): [Data](https://doi.org/10.6084/m9.figshare.988376) - [Paper](https://doi.org/10.1038/sdata.2014.47)
- EEG, MEG & fMRI data with perceptual task (n=19): [Data](https://openneuro.org/datasets/ds000117/versions/00004) - [Paper](https://doi.org/10.1038/sdata.2015.1)
- EEG data with TMS with visual perception task (n=16): [Data](https://datadryad.org/resource/doi:10.5061/dryad.1nr07) - [Paper](https://doi.org/10.1038/sdata.2016.65)
- EEG with Motion Capture during treadmill walking (n=8): [Data](https://doi.org/10.6084/m9.figshare.c.3894013.v1) - 
[Paper](https://doi.org/10.1038/sdata.2018.74)
- EEG data with a visual spatial attention task (n=45): [Data](https://osf.io/bwzfj) - [Paper](https://doi.org/10.1152/jn.00860.2015)
- EEG data with a visual working memory task, ERP design (n=104): [Data](https://osf.io/a65xz/ ) - [Paper](https://doi.org/10.1093/cercor/bhx336)
- EEG data with a visual working memory task, CDA design (n=76): [Data](https://osf.io/8xuk3) - [Paper](https://doi.org/10.1162/jocn_a_01233)
- EEG data with a covert visual spatial attention task (n=50): [Data](https://osf.io/m64ue) - [Paper](https://doi.org/10.1177/0956797617699167)
- OpenMIIR: EEG data during music perception and imagination (n=10): [Home Page](http://www.owenlab.uwo.ca/research/the_openmiir_dataset.html) - [Data](http://www.ling.uni-potsdam.de/mlcog/OpenMIIR-RawEEG_v1/)
- EEG data from subjects napping after a working memory task (n=22) [Data](https://osf.io/chav7/) - [Paper](https://doi.org/10.1016/j.compbiomed.2017.08.030)
- DEAP: Database for Emotion Analysis, EEG data + video recording, while watching videos (n=32) [Data](http://www.eecs.qmul.ac.uk/mmv/datasets/deap/) - [Paper](https://doi.org/10.1109/T-AFFC.2011.15)
- A collection of EEG tasks with speech studies (n=84, split across 5 tasks) [Data](https://doi.org/10.5061/dryad.070jc) -  [Paper](https://doi.org/10.1016/j.cub.2018.01.080)

### Individual EEG Datasets (Consumer Systems)

The following are avaialable datasets collected with consumer EEG systems:

- MNIST of Brain Data from MindBigData (n=1 with 1.2 million trials): [Data](http://mindbigdata.com/opendb/index.html)
- ImageNet of the Brain from MindBigData (n=1 with 70,000 trials): [Data](http://mindbigdata.com/opendb/imagenet.html)

### Other lists of EEG Data

There are some other lists of available EEG data, including:
- A publicly [curated list](https://github.com/meagmohit/EEG-Datasets) list of EEG data
- The [SCCN list](https://sccn.ucsd.edu/~arno/fam2data/publicly_available_EEG_data.html) of public EEG data

## MEG

Openly available magnetoencephalography (MEG) datasets and large-scale projects with MEG data.

### Open MEG Archive (OMEGA)

OMEGA is a open-access repository for MEG data, in which individual researchers can deposit their data. 

[Home Page](https://www.mcgill.ca/bic/resources/omega) - [Paper](https://doi.org/10.1016/j.neuroimage.2015.04.028)

### Human Connectome Project (HCP)

The Human-Connectome Project is a large, multi-site project, mostly focused on MRI, but includes a subset of MEG data.

[Home Page](https://www.humanconnectome.org/study/hcp-young-adult)

### Cambridge Center for Ageing Neuroscience (CAMCAN)

CAMCAN includes task & rest data from a large cohort, balanced in age from age 18-88 (n=652). 

[Home Page](https://camcan-archive.mrc-cbu.cam.ac.uk/)

### Miscellaneous Individual MEG Datasets

- Classification of Multimodal Stimulus Presentation - Visual & Auditory (n=52): [Data](https://osf.io/m25n4/) - 
[Paper](https://doi.org/10.1371/journal.pcbi.1005938)
- Multi-subject, multimodal face processing: face processing dataset including fMRI, MEG, EEG (n=16): [Data](https://openneuro.org/datasets/ds000117/versions/1.0.0) - [Paper](https://doi.org/10.1038/sdata.2015.1)

## ECoG

Openly available electrocorticograpgy (ECoG) datasets and large-scale projects with ECoG data, including and sometimes also referred to as intracranial EEG (iEEG) or stereo-electroencephalography (sEEG). 

### MNI Open iEEG Atlas

The MNI Open iEEG atlas is a repository of iEEG data from a multi-center collection project (n=106). 

[Home Page](https://mni-open-ieegatlas.research.mcgill.ca)

### iEEG.org

iEEG.org is an NIH supported repository of intracranial EEG data. 

[Home Page](https://www.ieeg.org)

### University of Pennsylvania Computational Memory Lab

Electrophysiological data

[Home Page](http://memory.psych.upenn.edu/Electrophysiological_Data)

RAM project

[Home Page](http://memory.psych.upenn.edu/RAM)

### Stanford Collection of ECoG Data

A collection a 16 tasks across a group of ECoG patients (n=250). 

[Home Page](https://purl.stanford.edu/zk881ps0522) - [Paper](https://doi.org/10.1152/jn.00113.2017)

### NeuroTycho

NeuroTycho is as collection of mostly monkey ECoG data. 

[Home Page](http://neurotycho.org)

## LFP 

Openly available local field potential (LFP) datasets and large-scale projects with LFP data.

### Collaborative Research in Computational Neuroscience (CRCNS)

A collection of data, mostly animal models, including extra-cellular recordings, and some animal model ECoG & iEEG. 

[Home Page](https://crcns.org) - [Data Portal](https://crcns.org/data-sets/) - [Paper](https://doi.org/10.1007/s12021-008-9009-y)

### Buzsáki Lab Webshare

This contains electrophysiological datasets collected from rodents in the Buzsáki lab.

[Home Page](https://buzsakilab.nyumc.org/datasets/) - [Buzsáki lab website](http://buzsakilab.com/wp/)
