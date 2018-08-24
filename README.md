# claff-happydb
Corpus and annotations for the CL-Aff Shared Task from the University of Pennsylvania

This package contains a release of training and test data to aid in modeling affect and emotion from text. 

The CL-Aff Shared Task is run off the CL-Aff corpus, and comprises two sub-tasks in affect modeling on data from the HappyDB corpus (see https://www.kaggle.com/ritresearch/happydb). For the CL-Aff Shared Task 2019, the details of the training corpus are provided below. We plan to further enrich this dataset in time, with more annotations, meta-features and trained classifiers to aid with downstream applications.

For more details, see the Contents Section at the bottom of this Readme. To know how this corpus was constructed, please see ./docs/corpusconstruction.txt

Results of the CL-Aff Shared Task 2019 will be released in the Affective Content Analysis (AffCon) Workshop @ AAAI-2019. 
Check out the Workshop and Shared Task website:  <a href="https://sites.google.com/view/affcon2019/home">https://sites.google.com/view/affcon2019/home</a>
Register your team now via EasyChair: <a href="https://easychair.org/conferences/?conf=affcon2019">https://easychair.org/conferences/?conf=affcon2019</a>

If you use the data and publish please let us know and cite our CL-Aff overview paper:
@inproceedings{TBA
}

## README for The Computational Linguistics Affect Summarization Shared Task Corpus (CL-Aff 2019)

August 24, 2018

Please read further for details on the CL-Aff Shared Task run as part of AffCon Workshop @ AAAI 2019 - official website hosted at: <a href="https://sites.google.com/view/affcon2019/home">https://sites.google.com/view/affcon2019/home</a> <br>

To participate in the 2018 shared task, please register your team details at: <a href="https://easychair.org/conferences/?conf=affcon2019">https://easychair.org/conferences/?conf=affcon2019</a> <br>

### Overview

You are invited to participate in the first CL-Aff Shared Task, to be held as a part of the Affective Content Analysis workshop @ AAAI 2019. The shared task will be on modeling affect in language from user-provided descriptions of happy moments. 

There is a rising need for methods to monitor and automatically moderate online behavior on social media. It can lead to unintended social and political consequences. Trolling and incivility is often masked as high affect behavior, with the use of sarcasm, euphemism and humor to convey what incendiary ideas. In the quest to understand user expression, we propose a task to undertake the first basic understanding of human affect - happiness. We contribute a new labeled corpus of happy moments and pose two novel challenges to spur the development of supervised and semi-supervised approachs in modeling human affect.

Task
Given: A sentence describing a happy moment written in first person, as an answer to the question "What made you happy? Reflect on the past <time period>, and recall three actual events that happened to you that made you happy." 

For Task 1, the labeled training set includes labels that identify the 'agency' of the author and the 'social' characteristic of the moment. 
For Task 2, the labeled training set includes up to three concept labels describing the theme of the moment.

Evaluation: <TBA>

## Contents

This is the open repository for the Scientific Document Summarization Corpus and Annotations contributed to the public by the Web IR / NLP Group at @ the National University of Singapore (WING-NUS) 
with generous support from Microsoft Research Asia.

    ./README.md
 
This file.

    ./FAQ2019
	
Frequently asked questions including updates to the corpus.

    ./docs/corpusconstruction.txt
 
A readme detailing the rules and steps followed to create the document
corpus.
  

    ./docs/annotation_rules.txt
  
Rules followed for the annotation.


    ./data/Task-?/TRAIN
  
Directories containing the training set.

    ./data/Task-?/TEST

Directories containing the test set.

## Annotation

For Task 1 annotations, workers labeled a happy moment following the instructions provided at <link>
For Task 2 annotations, workers labeled a happy moment with a maximum of two concept labels from a set of five automatically selected "best matching" labels from a superset of 15 labels.
The training set for Task 2 of xxx moments is already available for download and can be used by participants to pilot their systems. The test set of xx for Task 1 and xxx for Task 2 will be released on xxx. The system outputs from the test set should be submitted to the task organizers, for the collation of the final results to be presented at the workshop.


## Organisers' Contacts

For further information about this data release, contact the following members of the BRNDL 2017 workshop organising committee:

* <a href="https://kokiljaidka.wordpress.com/">Kokil Jaidka</a> (University of Pennsylvania) kokil.j@gmail.com

--------------------------------------------------------------------------
