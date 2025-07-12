
The data used in this annotation job comes from the Civil Comments dataset, originally made available at https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification.

The data contains the raw annotations from the job, and is unaggregated. There are a total of 25,500 comments, with 5 annotations per rater group per comment, with a total of 382,500 annotations.

The different columns in the data are the following:

### id: The id of the comment from the CivilComments data.
### unique_contributor_id: A pseudonymized id for the annotator.
### identity_attack: The annotator's score for the "identity_attack" category. This is a value of -1 (identity attack), 0 (unsure), or 1 (not an - identity attack).
### insult: The annotator's score for the "insult" category. This is a value of -1 (insult), 0 (unsure), or 1 (not an insult).
### obscene: The annotator's score for the "obscene" (profanity) category. This is a value of -1 (profanity), 0 (unsure), or 1 (not profanity).
### threat: The annotator's score for the "threat" category. This is a value of -1 (threat), 0 (unsure), or 1 (not a threat).
### toxic_score: The annotator's score for the "toxicity" category. This is a value of -2 (very toxic), -1 (toxic), 0 (unsure), or 1 (not toxic).
### comment_text: The text of the comment.
### rater_group: The rater group the annotator was a part of. This is a value of "African American", "LGBTQ", or "Control".
To properly cite this dataset, please cite the ACM CSCW 2022 :

Note:

There is one duplicate id in the dataset, from either a sampling error or other processing error. This id is "1.05408E+18". We have excluded the two comments with this id for our analysis for the paper, but leave them in the full dataset for completeness.
Some values in the dataset are "null" because the annotators checked the following box while performing the annotations: "This comment is in a foreign language or not comprehensible for another reason (eg. gibberish, different dialect etc. )"
