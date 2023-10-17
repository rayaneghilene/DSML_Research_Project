# DSML_Research_Project
### Analysis of and Responses to Extremist Narratives passing through the Socially Unacceptable Discourse Analysis.



![My Project](https://github.com/rayaneghilene/DSML_Research_Project/blob/main/Images/Cy_ENSEA10.png)




## Description
This repository contains the research work done by Rayane GHILENE For a research Masters in Data Science and Machine Learning and it aims to generate counter-narratives to hate speech.
The repository contains different methods used for this purpose such as the fine-tuning of a GPT-2 Model for counter-narrative generation.


## Files 

- [Hate speech Classification](/DSML_Research_Project/MultiClassConan.ipynb)
- [Fine-tuning of a GPT-2 Model](/DSML_Research_Project/GPT2-fine-tuning.ipynb)

### Hate speech Classification
[Hate speech Classification](/DSML_Research_Project/MultiClassConan.ipynb)

I started by Training a model on Hate speech Classification, the model calculates the probability of a text's label and returns the highest one.
![Prompt](https://github.com/rayaneghilene/CONAN/blob/master/Images/Fichier%20210.png)

### Fine-tuning of a GPT-2 Model

[Fine-tuning of a GPT-2 Model](/DSML_Research_Project/GPT2-fine-tuning.ipynb)

This method consisted of fine-tuning a GPT-2 Model for counter-narratives generation for hate speech. it was trained on the multitarget CONAN Dataset.
Here's an example prompt that the model was able to generate

![Prompt](https://github.com/rayaneghilene/CONAN/blob/master/Images/Prompt_example10.png)



## Dataset 


All the datasets are created starting from examples written by experts. For each dataset we provide a description of its characteristics, the data, and the corresponding publication.

| Dataset                                    |                                  Content                                 | Year | Paper                                             |
|--------------------------------------------|----------------------------------------------------------------------|--------------|---------------------------------------------------|
| [DIALOCONAN](#dialoconan)                                    | A multi-turn HS/CN dialogue dataset.                                   | 2022         | https://aclanthology.org/2022.emnlp-main.549.pdf                                               |
| [Multitarget CONAN](#multitarget-conan)                          | HS/CN pairs dataset covering multiple targets of hate.              | 2021         | https://aclanthology.org/2021.acl-long.250.pdf    |
| [CONAN](#conan)                                      | Multilingual expert-based HS/CN pairs dataset on Islamophobia. | 2019         | https://aclanthology.org/P19-1271.pdf             |
| [Knowledge-grounded hate countering dataset](#knowledge-grounded-hate-countering-dataset) | HS/CN pairs with the background knowledge corresponding to the CN.     | 2021         | https://aclanthology.org/2021.findings-acl.79.pdf |

***

## Contact
If you have any questions or would like to discuss my work further, please don't hesitate to contact me at rayane.ghilene@ensea.fr.


## License
These resources can be used for research purposes and cannot be redistributed. Please cite the corresponding publication when publishing.
