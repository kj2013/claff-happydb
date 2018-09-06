
### Directory information
    ./data/TRAIN
Directory containing the training set.


    ./data/TEST
Directory containing the test set (TO BE ADDED).

### Corpus details for Shared Task 2019

**Labeled training set:** Single-sentence happy moments from the available HappyDB corpus, annotated with authors' demographics and reflection period information, as well as labels that identify the 'agency' of the author and the 'social' characteristic of the moment, and concept labels describing its theme.

**Unlabeled training set:** The remaining single-sentence happy moments with authors' demographics and reflection period information.

**Test set:** Previously unreleased, labeled, single-sentence happy moments, freshly collected in the same manner as the original HappyDB data, with authors' demographics, reflection period information and duration of the happy moment.

### File contents
    ./data/TRAIN/labeled_10k.csv
Labeled training set.

    ./data/TRAIN/unlabeled_70k.csv
Unlabeled training set.



### Label descriptions

**Age, Gender, Country, Married, Parenthood**
Demographics of the author of the happy moment.

Age: Real valued and continuous, with some "NA" and some "prefer not to say" values

Gender: Categorical, with 4 possible values: "m"(male), "f"(female), "o"(other) or NA

Country: Categorical, with 96 possible values as three-letter country codes

Married: Categorical, with six possible values: "single", "married", "divorced", "separated", "widowed" or NA

Parenthood: Identifying the author as a parent or not, with values as "n"(no), "y"(yes) or NA

**Reflection**
The <time period> of reflection indicated in the HIT question, with two possible values: "24h", "3m"
    
**Duration (available for test set ONLY)**
The duration for which the author felt happy, with 5 possible categorical values: "all_day_im_still_feeling_it", "at_least_one_hour", "half_a_day", "a_few_minutes" or NA

**Agency**
Binary label describing whether or not the author is in control (yes/no)

Examples of sentences where the author is in control (Answer is YES):
    
    "I ran on the treadmill for 20 minutes straight when I could barely do 5 minutes 3 months ago."
    "Going out to a special birthday lunch for my great grandmother in law's birthday."

Examples of sentences where the author is not in control (Answer is NO):

    "My youngest daughter got accepted to a number of prestigious universities and accepted an offer to attend college in San Diego.
    "A small business deal change over for small profit."


**Social**

Binary label describing whether or not this moment involve people other than the author. (yes/no)

Please note that objects (e.g., bus, work) are not considered social. 

Examples of sentences which involve other people (Answer is YES):

    "Going out to a special birthday lunch for my great grandmother in law's birthday."
    "My youngest daughter got accepted to a number of prestigious universities and accepted an offer to attend college in San Diego."

Note that sometimes a person is implicitly involved although not explicitly mentioned. In this case, we still wish to label the happy moment as social. E.g., 

    “I received compliments on my tattoo."

Examples of sentences which is not social (Answer is NO):

    "I ran on the treadmill for 20 minutes straight when I could barely do 5 minutes 3 months ago."
    "A small business deal change over for small profit."
    “The weather is great today.”
    “The bus came on time so I reached work early.”


**Concepts**

Concepts can have up to 15 possible values, and each moment can have multiple (up to 4) values separated by a piping symbol, e.g.
    
    "family|education|party"
