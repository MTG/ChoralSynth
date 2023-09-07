# Dataset
CPDL is a synthesized dataset of 20 choral songs curated by carefully listening and analyzing a set of synthetic choral songs obtained from VoiceMod. The resulting dataset can be used for the task of source separation or other musicological research. 
The dataset curation was carried out in the following steps:

(1) Automatic Filtering: The initial step involved the automatic filtering of scores using predefined musicological criteria, as identified by a musician.\
(2) Manual Verification: Subsequently, manually listening and validating the resulting filtered songs obtained from step 1 using the identified criteria. \

The process of automatic filtering along with resulting statistics is presented in the supporting notebook, with csv files indicating the resulting scores that were used for analysis. \

At this point, we have curated a set of 20 songs, however, the methodology can be extended to add more songs from the resulting list. 

## Downloading the data
The dataset is available for conducting non-commercial research related to choral singing. It is available upon request on Zenodo alongside an extended description of the selected songs, motivation, license, and ownership of the data.

# Installation
The authors recommend the use of virtual environments.

git clone https://github.com/MTG/CPDL.git
cd CPDL
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt