### This project is structured in terms of different versions. Each version begins with a cell of all the libraries you need to import for that version to run.
### All versions can be run independently
### Here are the versions described below:
#### Laney REU 2024: Used a summary of 20ish bug reports from GPT and compared cosine similarities within topics
#### Laney_REU_2024_draft2.: Failed attempt to use the GPT API to summarize bug reports and compare cosine similarities within topics
#### Laney_REU_2024_draft3_no_summaries: Stopped using summarizing and refactored code so that it would compare cosine similarities within topics
#### Laney_REU_2024_draft5_timesorted: Separated the data frame into different time frames rather than topics and compared cosine similarities 
#### Laney_REU_2024_draft6_similarity_val_change1: Tested different threshold values for cosine similarity to classify them as duplicate or not duplicate 
#### Laney_REU_2024_draft8_top_k: Created a function to output k number of similar bugs rather than bugs above a certain similarity threshold 
#### Laney_REU_2024_draft9: Performed recall and precision on the top k similar bugs
#### # binary_classification: test MLP, BERT, and Naive Bayes for determining if a bug is a duplicate or not
#### Laney_REU_2024_draft10_gpt_summary.ipynb: Used API to summarize bug reports and then used cosine similarity
