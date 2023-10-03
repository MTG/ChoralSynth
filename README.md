# Dataset
### Overview
ChoralSynth is a synthesized dataset of 20 multitrack choral songs curated by carefully listening and analyzing a set of synthetic choral songs generated using one of the state-of-the-art synthesizers. The resulting dataset can serve as a valuable resource for various MIR research endeavors like source separation, melodic analysis, chord analysis, rhythmic analysis amongst others.

### Dataset Curation Process
- **Manual Criteria Design**: The initial step involved the manual design of filtering criteria. This design was based on a careful examination of over 300 scores and their corresponding synthesized versions to ensure comprehensive and relevant criteria. \
- **Automatic Filtering**: Subsequently, the designed criteria were used for automatic filtering of the scores. \
- **Manual Verification**: The filtered songs from step 2 were then examined again manually, 
validating the synthetic versions through attentive listening, ensuring they demonstrated completeness and a resemblance to human singing. 

### Dataset Details

Detailed statistics and insights regarding the automatic filtering process, along with resulting statistics, can be found in the accompanying supporting notebook. Additionally, CSV files are provided, indicating the specific scores that were selected for further analysis.

At this point, we have curated a set of 20 songs, however, the methodology can be extended to add more songs from the resulting list. 

## Downloading the data
The dataset is available for conducting non-commercial research related to choral singing. It is available upon request on Zenodo alongside an extended description of the selected songs, motivation, license, and ownership of the data.

# Installation
The authors recommend the use of virtual environments.
```
git clone https://github.com/MTG/CPDL.git 
cd CPDL 
python3 -m venv venv  
source venv/bin/activate 
pip install -r requirements.txt
```
# Code

```
.
├── LICENSE
├── README.md
├── data_analysis_viviana.xlsx
├── requirements.txt
└── src
    └── scripts
        ├── CPDL_data_filtering.ipynb
        ├── Convert to MIDI.ipynb
        ├── Song Analysis.ipynb
        ├── correct_file_names_removed_treble_wrong_lyrics_cpdl_repeat1.csv
        └── correct_file_names_removed_treble_wrong_lyrics_cpdl_repeat2.csv
```

# License
ChoralSynth is licensed under CC BY-NC-SA 4.0
[![License: CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)  
