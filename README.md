# CL-Aff Shared Task - In Pursuit of Happiness 

Corpus and annotations for the CL-Aff Shared Task - In Pursuit of Happiness - from the University of Pennsylvania

A part of the AffCon Workshop @ AAAI 2019 for Modeling Affect-in-Action

Check out the Workshop and Shared Task website:  <a href="https://sites.google.com/view/affcon2019/home">https://sites.google.com/view/affcon2019/home</a>


# This Shared Task is now closed, but feel free to use our datasets

# Check out the FAQ!

The CL-Aff Shared Task comprises two sub-tasks in affect modeling and understanding on data from the HappyDB corpus (see <a href="https://github.com/rit-public/HappyDB">https://github.com/rit-public/HappyDB</a>). Further documentation about HappyDB can be found <a href="https://rit-public.github.io/HappyDB/">here</a> and <a href="https://www.kaggle.com/ritresearch/happydb">on Kaggle</a>. 

This package contains a release of training and test data to aid in modeling affect and emotion from text. 

This README describes the directory structure and contents of this gitrepo. To know how this corpus was annotated for the CL-Aff Shared Task 2019, please see ./docs/annotation_rules.txt
Please "WATCH" this repository! We may be pushing more updates in the following weeks.
We also plan to further enrich this data, with more annotations, meta-features and trained classifiers to aid with downstream applications.

If you use the data and publish, please let us know and cite our CL-Aff overview paper:

@inproceedings{jaidka2019cl,
  title={The CL-Aff Happiness Shared Task: Results and Key Insights.},
  author={Jaidka, Kokil and Mumick, Saran and Chhaya, Niyati and Ungar, Lyle},
  booktitle={AffCon@ AAAI},
  pages={39--49},
  year={2019}
}

You can also cite our forthcoming ICWSM-2020 paper, we'll upload a camera-ready version soon:
@inproceedings{jaidka2020happy,
  title={Beyond Positive Emotion: Deconstructing Happy Moments based on Writing Prompts},
  author={Jaidka, Kokil and Mumick, Saran and Chhaya, Niyati and Killingsworth, Matthew and Halevy, Alon and Ungar, Lyle},
   booktitle={Proceedings of the International AAAI Conference on Web and Social Media},
    year={In press}
}
## README for The Computational Linguistics Affect Understanding Shared Task Corpus (CL-Aff 2019)

August 24, 2018

Please read further for details on the CL-Aff Shared Task run as part of AffCon Workshop @ AAAI 2019 - official website hosted at: <a href="https://sites.google.com/view/affcon2019/home">https://sites.google.com/view/affcon2019/home</a> <br>

To participate in the 2019 shared task, please register your team details at: <a href="https://easychair.org/conferences/?conf=affcon2019">https://easychair.org/conferences/?conf=affcon2019</a>  Please prefix your submission title with [CL-Aff Shared Task]<br>

### Overview

You are invited to participate in the first CL-Aff Shared Task, to be held as a part of the Affective Content Analysis workshop @ AAAI 2019. The purpose of the CL-Aff Shared Task is to challenge the current understanding of emotion and affect in text through a task that models the experiential, contextual, and agentic attributes of happy moments. It has long been known that human affect is context-driven, and that labeled datasets should account for these factors in generating predictive models of affect. The Shared Task is organized in collaboration with researchers at Megagon Labs and builds upon the HappyDB dataset, comprising human accounts of 'happy moments'. The Shared Task comprises two sub-tasks for analyzing happiness and wellbeing in written language, on a corpus of 100,000 descriptions of happy moments. 


### Tasks

Given: An account of a happy moment, marked with individual's demographics, recollection time and relevant labels.

**TASK 1: WHAT ARE THE INGREDIENTS FOR HAPPINESS?**

Semi-supervised learning task: Predict agency and social labels for happy moments in the test set, based on a small labeled and large unlabeled training data. 

**TASK 2: HOW CAN WE MODEL HAPPINESS?**

Unsupervised task: Propose new characterizations and insights (not necessarily and not limited to concepts/ themes) for happy moments in the test set, e.g., in terms of affect, emotion, participants and content.

Evaluation (Task 1): Accuracy, AUC, F1

Evaluation (Task 2): Subjective, based on qualitative characteristics.

## Corpus details

**Labeled training set:** Single-sentence happy moments from the available HappyDB corpus, annotated with labels that identify the 'agency' of the author and the 'social' characteristic of the moment, as well as concept labels describing its theme

**Unlabeled training set:** The remaining single-sentence happy moments with no labels.

**Test set:** Previously unreleased, labeled, single-sentence happy moments, freshly collected in the same manner as the original HappyDB data 

## Git Contents

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

    ./data/TRAIN
  
Directory containing the training set.

    ./data/TEST

Directory containing the test set.



## Organisers' Contacts

The system outputs from the test set should be submitted to the task organizers, for the collation of the final results to be presented at the workshop.

For further information about this data release, contact the following members of the AffCon 2019 workshop organising committee:

* <a href="https://kokiljaidka.wordpress.com/">Kokil Jaidka</a> (University of Pennsylvania) kokil.j@gmail.com
* Niyati Chhaya (Adobe Research) nchhaya@adobe.com


--------------------------------------------------------------------------
