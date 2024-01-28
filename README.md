# 102103038_Pre-trained_model

This is an Assignment Task for finding the best pre-trained model taken from Hugging Face for comparing the best model for text sentence similarity.

# Title
To find the best pre-trained Model by applying Topsis for text sentence similarity.

# Description
In the initial phase, sentence data was gathered, comprising various sentence pairs intended for evaluation based on distinct parameters. Subsequently, tokenization was applied, and models were retrieved from Hugging Face. These models were then employed to compute sentence similarity for the given text pairs across five evaluation parameters. The outcomes were recorded and stored in a CSV file for further analysis.After getting the output in a csv file we then run topsis analysis to find topsis score for each model and rank them accordingly. For topsis analysis we wrote a python code to generate a csv file with topsis score and ranking 

# Result
I found  'bert-base-uncased' model showed the best outcomes for sentence similarity with a Topsis Rank of 1 and score 82.03.

![image](https://github.com/Kunalg55/102103038_Pre-trained_model/assets/142966912/7a3a8c77-43a4-4a87-bcd8-389e24f3fe9d)


# Comparison graph between topsis score v/s models

![image](https://github.com/Kunalg55/102103038_Pre-trained_model/assets/142966912/67fc0e02-c8c3-4079-ae96-6e48cfb4a561)



