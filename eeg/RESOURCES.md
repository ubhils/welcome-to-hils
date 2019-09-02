# Get started with EEG!
One of the main modalities we use in our lab to study Human-robot interaction is EEG (others include EMG, haptics). Here are some resources which introduce you to the analysis of EEG. 

# Setting up EEG recordings 

Here is a small video on how to setup advanced brain monitoring electrodes for EEG recording. 

> Please feel free to drop by the lab to get more information

<a href="https://www.youtube.com/watch?v=RZtLw0lSGi4" target="_blank"><img src="http://img.youtube.com/vi/RZtLw0lSGi4/0.jpg"
alt="Introduction to BCI" width="240" height="180" border="10" /></a>

<a href="https://www.youtube.com/watch?v=bptpN6ybUSA" target="_blank"><img src="http://img.youtube.com/vi/bptpN6ybUSA/0.jpg"
alt="Introduction to BCI" width="240" height="180" border="10" /></a>


# EEG analysis steps 
For those who are starting with EEG analysis, it can be overwhelming to go across a lot of steps. Here is almost a standard procedure for a lot of EEG analysis. Each block is a research area by itself. There are a lot of papers on each block. Do not get scared once you start analysis some EEG data, these steps will become second to your nature. Do read below given paper about how others are doing these steps. We use [mne-python](https://www.nmr.mgh.harvard.edu/mne/stable/index.html) to implement different block functionalities. If you want more information, refer to [Mike X Cohen's lectures](http://mikexcohen.com/lectures.html) 

![](eeg_analysis.png)


# MNE 
In the lab, we extensively use [mne-python](https://www.nmr.mgh.harvard.edu/mne/stable/index.html) for analysis of a lot of EEG (time series in general) data. It is an amazing package with a lot of development and an amazing community. If you get a chance, do join the [mailing list.](https://mail.nmr.mgh.harvard.edu/mailman/listinfo/mne_analysis)

> Here are some resources to get you started with mne-python 

[Basic mne-python](https://mybinder.org/v2/gh/wmvanvliet/SNL_workshop_2019/master?filepath=SNL_workshop_2019.ipynb)

[Intermediate mne-python tutorials](https://mne.tools/0.14/tutorials.html)

# EEG databases
Here are some databases on which you are apply your mne-python skills. 

> The best way to learn a (Python) package is to use it on your own data and see what are the capabilities

Pick up some data from this repository: [meagmohit/EEG-Datasets](https://github.com/meagmohit/EEG-Datasets). Use mne-python do some analysis and that how you get introduced to analysis of EEG.

> If you have doubts, do drop by to HILS lab and ask any questions!

# Papers

* [A revised glossary of terms most commonly used by clinical electroencephalographers and updated proposal for the report format of the EEG findings. Revision 2017](https://search.lib.buffalo.edu/discovery/fulldisplay?docid=sciversesciencedirect_elsevierS2467-981X(17)30021-5&context=PC&vid=01SUNY_BUF:everything&search_scope=UBSUNY&tab=EverythingUBSUNY&lang=en)

* [Best Practices in Data Analysis and Sharing in Neuroimaging using MEEG.](https://osf.io/a8dhx/)

* [A Reproducible MEG/EEG Group Study With the MNE Software: Recommendations, Quality Assessments, and Good Practices](https://www.frontiersin.org/articles/10.3389/fnins.2018.00530/full)

* [EEG artifact removal—state-of-the-art and guidelines](https://search.lib.buffalo.edu/discovery/fulldisplay?docid=iop10.1088/1741-2560/12/3/031001&context=PC&vid=01SUNY_BUF:everything&search_scope=UBSUNY&tab=EverythingUBSUNY&lang=en)