# Data Cleaning
To make our data concise, we need to do a data cleaning first to get rid of those meaningless characters. 

e.g. **Floo d ,  rep!ort i''n 1980** should be cleaned into **Flood report in 1980**. 

Thus, we will do a fine-tuning on ChatGPT (temp choice) to help recognize and correcting those raw data. (Wait, why?)

# Fine Tuning Code
Python3 is used to call the fine-tuning APIs. 
ChatGPT fine tuning doc is here: https://platform.openai.com/docs/guides/fine-tuning