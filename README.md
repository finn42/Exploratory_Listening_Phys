# Exploratory Listening Quantitative Analysis Repository


This repository shares extracted data features and code for analysing and ploting the quantitative descriptors of music and physiological measurements of musicians and audience members reported in the paper.

Haswell-Martin, R., Upham, F., Høffding, S., Nielsen, N. (2025) "Embodied, Exploratory Listening in the Concert Hall." Behavioral Sciences 15, x


The data are excerpts of the [Bodies in Concert](https://www.uio.no/ritmo/english/projects/Bodies-in-Concert/) research project at the RITMO Center of excellence in Rhythm, Time, and Meter. This project includes multiple orchestral concert research projects, collaborations with institutions to recording concurrent physiological signals and performance information from musicians on stage and live attending audiences. The data included here are from concert experiments conducted in 2024, one in Stavanger and the other in Oslo. Audience member participants were university music students recruited to attend and report on their experience or volunteers from the ticketed public (Oslo only). Featured participants in the case studies were music students that were also interviewed, and information from that data collection is reported else where. 

The data folder shares cleaned and resampled physiological measurements (respiration wave, and core body accelerometery) from featured participants during performances of Saevarud's Kjempeviseslåtten, both case study audience members and the orchestra conductor for one performance. Additional statistics from other audience members are reported in summary in the analysis notebooks but not provided as complete signals. Aslo in the data folder are descripters of the music performances: Constant-Q transform spectrograms of the two featured recordings (third not displayed), encoded score information (part entries) for both performances. Lastly, there are annotation notes for the two performances, showing the time stamps and annotations initially assigned through the close reading of the music and participants concurrent measurements. 

The plots folder shows the output compound plots prepared for the paper plus some minor variations. The main folder contains the rp2.py function file (respy2, developped by author) and python notebooks to prepare the signals in their published form and assess and report each case study. Some cells are descriptive beyond what is reported. 

 ---

## Content description

data/
	- Annotations/: CSV files with time-stamped annotations for the plots of Case 1 and Sase 2, comparisons between performed music and audience member physiology signals.
	- Performance_data/: CSV files describing the audio of the performances (10_cqt.csv) featured in each analysis and corresponding annotation files describing the music and playing information.
	- Physiological_data/: CSV files of physiological measurements from the featured audience member signals for each case studies, the conductor's signals as well as concurrent signals of other audience members during the same performances or pieces, resampled for convenient evaluation.

plots/
	notebook outputs of the Exact figures featured in papers plus figures for supplementary materials (Supp)

Code:
	- rp2.py: functions for respiration signal processing used in notebooks
	- Signal Preparation.ipynb: Code base to generate audio feature and physiological data features in the data folder from raw measurements (not shared)
	- CaseStudy1_SSO.ipynb: Notebook sequence to show analysis and generate figures for Case study 1, plots for main text and related supplimentary materials
	- CaseStudy2_KORK.ipynb: Notebook sequence to show analysis and generate figures for Case study 2, plots for main text and related supplimentary materials

License
README.md
CITATION.cff

Python libraries used:
Package                       Version
librosa                       0.10.1
notebook                      6.1.5
numpy                         1.25.2
pandas                        2.2.1
pingouin                      0.5.4
scipy                         1.11.3
seaborn                       0.13.2

---

Finn Upham, 2025-02-26
Updated, 2025-05-17
