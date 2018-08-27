
### Directory information
    ./data/TRAIN
Directory containing the training set.


    ./data/TEST
Directory containing the test set (TO BE ADDED).

### File contents
    ./data/TRAIN/labeled_10k.csv
Small labeled dataset, with Moment, Concept, Agency, and Social fields.

    ./data/TRAIN/unlabeled_70k.csv
Large unlabeled dataset, with Moment as the only field.



### Label descriptions

**Agency**

Agency: Is the author in control?  YES/NO
Examples of sentences where the author is in control (Answer is YES):
    
    "I ran on the treadmill for 20 minutes straight when I could barely do 5 minutes 3 months ago."
    "Going out to a special birthday lunch for my great grandmother in law's birthday."

Examples of sentences where the author is not in control (Answer is NO):

    "My youngest daughter got accepted to a number of prestigious universities and accepted an offer to attend college in San Diego.
    "A small business deal change over for small profit."


**Social**

Social: Does this moment involve other people other than the author? YES/NO
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

Concepts can have up to 15 possible values, and each moment can have multiple values separated by a piping symbol, e.g.
    
    "family|education|party"
