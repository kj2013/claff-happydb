# claff-happydb
Corpus and annotations for the CL-Aff Shared Task from the University of Pennsylvania

This package contains a release of training and test data to aid in modeling affect and emotion from text. 

The CL-Aff Shared Task comprises two sub-tasks in affect modeling on data from the HappyDB corpus (see https://www.kaggle.com/ritresearch/happydb). For the CL-Aff Shared Task 2019, the details of the training corpus are provided below. We plan to further enrich this dataset in time, with more annotations, meta-features and trained classifiers to aid with downstream applications.

For more details, see the Contents Section at the bottom of this Readme. To know how this corpus was constructed, please see ./docs/corpusconstruction.txt

Results of the CL-Aff Shared Task 2019 will be released in the AAAI Workshop on Affective Content Analysis (AffCon) @ AAAI-2019. 
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

You are invited to participate in the first CL-Aff Shared Task, to be held as a part of the Affective Content Analysis workshop @ AAAI 2019. The purpose of the CL-Aff Shared Task is to challenge the current understanding of emotion through a task that models the experiential, contextual and agentic attributes of happy moments. It has long been known that human affect is context-driven, and that labeled datasets should account for these factors in generating predictive models of affect. The Shared Task is organized in collaboration with researchers at Megagon Labs and builds upon the HappyDB dataset, comprising human accounts of 'happy moments'. The Shared Task comprises two sub-tasks for analyzing happiness and wellbeing in written language, on a corpus of 100,000 descriptions of happy moments. 


Task
Given: An account of a happy moment, marked with individual's demographics, recollection time and relevant labels.

Task 1: Predict thematic labels on unseen data, based on a small labeled and large unlabeled training data. 

Task 2: Suggest interesting ways to automatically characterize the happy moments, e.g., in terms of affect, emotion, participants and content.

Annotations


Evaluation: <TBA>

## Contents

This is the open repository for Affect Understanding in Text and Annotations contributed to the public through the collaboration between Univeristy of Pennsylvania and Megagon Labs and builds upon the HappyDB dataset, comprising human accounts of 'happy moments'. 


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

For Task 1, the labeled training set includes labels that identify the 'agency' of the author and the 'social' characteristic of the moment. 

For Task 2, the labeled training set includes up to two concept labels describing the theme of the moment.



## Organisers' Contacts

The system outputs from the test set should be submitted to the task organizers, for the collation of the final results to be presented at the workshop.

For further information about this data release, contact the following members of the AffCon 2019 workshop organising committee:

* <a href="https://kokiljaidka.wordpress.com/">Kokil Jaidka</a> (University of Pennsylvania) kokil.j@gmail.com
* Niyati Chhaya (Adobe Research) nchhaya@adobe.com


--------------------------------------------------------------------------
