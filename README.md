# CDEval: A Benchmark for Measuring the Cultural Dimensions of Large Language Models

## Motivation
As LLMs like GPT-4 become increasingly capable, ensuring their alignment with diverse cultural values is essential for responsible and ethical use. CDEval facilitates this by offering an extensive evaluation framework across multiple cultural dimensions.

## The pipeline of benchmark construction 
![](images/pipeline.png?v=1&type=image)
## The examples of CDEval
![](images/data_examples.png?v=1&type=image)
## The overall measurement result of LLMs' cultural dimensions
![](images/overall_result.png?v=1&type=image)
## Some Findings
### Diverse patterns across six dimensions. 
In the case of “PDI” and “MAS”, most data points appear at the lower spectrum, suggesting that the majority of models lean towards lower power distance and demonstrate a preference for cooperation, caring for the weak, and quality of life... 
### Distinct differences in specific dimensions. 
Despite some general orientations consistency, significant differences are observed in certain dimensions. For instance, in the case of “PDI”, it is evident that GPT-4 and GPT-3.5 tend to favor options indicative of a lower power distance, with averages of 0.24 and 0.28, respectively. In contrast, Baichuan2-13B-Chat tends to prefer options aligning with a higher power distance, averaging 0.54 ...
pattern is observed in the “MAS” dimension, where the models demonstrate varying inclinations towards femininity. Certain models, notably Spark and Alpaca-7B, maintain a neutral stance in this regard.
### Domain-specific cultural orientations. 
Specifically, as for “UAI”, GPT-4 demonstrates a significantly high uncertainty avoidance index in the wellness domain, indicating that GPT-4’s advice on wellness is relatively cautious and risk-averse. This is contrary to the mean likelihood on “UAI”.
More results are illustrated in our paper. 

## Download
Download the data from this [LINK](https://drive.google.com/drive/folders/1m6IIyNfDuiInpCNlrWxfu3vd_xtcG757?usp=drive_link).
