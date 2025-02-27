README.md Exploratory Listening Quantitative Analysis Repository

This repository shares extracted data features and code for analysing and ploting the quantitative descriptors of music and physiological measurements of musicians and audience members reported in this submitted paper.

The data are excerpts of the Bodies in Concert research project at the RITMO Center of excellence in Rhythm, Time, and Meter. This project includes multiple orchestral concert research projects, collaborations with institutions to recording concurrent physiological signals and performance information from musicians on stage and live attending audiences. The data included here are from concert experiments conducted in 2024, one in Stavanger and the other in Oslo. Audience member participants were university music students recruited to attend and report on their experience or volunteers from the ticketed public (Oslo only). Featured participants in the case studies were music students that were also interviewed, and information from that data collection is reported else where. 

Kjempeviseslåtten The data file shares cleaned and resampled physiological measurements (respiration wave, and core body accelerometery) from featured participants during performances of Saevarud's Kjempeviseslatten, both case study audience members and the orchestra conductor for one performance. Additional statistics from other audience members are reported in summary in the analysis notebooks but not provided as complete signals. Aslo in the data folder are descripters of the music performances: Constant-Q transform spectrograms of the two featured recordings (third not displayed), encoded score information (part entries) for both performances. Lastly, there are annotation notes for the two performances, showing the time stamps and annotations initially assigned through the close reading of the music and participants concurrent measurements. 

The plots folder shows the output compound plots prepared for the paper plus some minor variations. The main folder contains the rp2.py function file (respy2, developped by author) and python notebooks to prepare the signals in their published form and assess and report each case study. Some cells are descriptive beyond what is reported. 

Python libraries used:
Package                       Version
librosa                       0.10.1
notebook                      6.1.5
numpy                         1.25.2
pandas                        2.2.1
pingouin                      0.5.4
scipy                         1.11.3
seaborn                       0.13.2


Finn Upham, 2025-02-26
