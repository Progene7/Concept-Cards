# Concept Cards

## Project Overview 

The concept cards (CC) are revision aids for students which facilitate quick revision of key concepts in the national examinations like JEE and NEET. Each chapter will be covered in 30-40 CC’s and 40-50 words/CC

The concept card may contain bullet points, images, formula, etc for enhanced revision.

## Source of Content 

We used the source material like NCERT and reference form Allen modules, the text and images are extracted via OCR and converted to mmd files

## Python notebooks and LLM Integration 

The mmd files are processed to OpenAI API on multiple prompts, delicately engineered according to our use case and best ones are stored as .csv files for future processing.

[**Ref :** CC\_Gen.ipynb {**Now :** CC\_Gen\_Thread.ipynb  —> Incorporated threading}]

## Evaluation 


The .csv files are evaluated on 4 parameters namely, correctness, completeness, formula accuracy, and clarity. The LLM also provides a “Confidence level” of its output. 

[**Ref :** CC\_Evaluation.ipynb {**Now :** CC\_Evaluation\_Thread.ipynb  —> Incorporated threading}]















