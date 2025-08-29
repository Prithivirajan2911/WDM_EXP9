### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 29.08.25
### AIM: To implement preprocessing technique on Twitter Data using Rapidminer
### Description: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
1) ***Import Twitter data:*** Import the Twitter data into RapidMiner. You can do this by selecting the appropriate
data source operator, such as "Read Excel" or "Read CSV," and specifying the location of your Twitter data
file.
2) ***Preprocess data:*** Preprocess the imported data to clean and prepare it for text processing. Use the following
operators for preprocessing:
    <p>a. Tokenize: Split the text into individual words or tokens.
    <p>b. Transform Cases: Convert the text to lowercase or uppercase to ensure consistency.
    <p>c. Remove Stopwords: Remove common words that do not provide much meaningful information.
    <p>d. Remove Special Characters: Eliminate special characters, such as punctuation marks or symbols.
    <p>e. Remove Numbers: Exclude numeric values from the text.
3) ***Stemming:*** Apply stemming to reduce words to their root forms. You can use operators like "Stem (Porter)"
for this purpose.


### Output:

<img width="1709" height="956" alt="Screenshot 2025-08-29 093302" src="https://github.com/user-attachments/assets/315f713c-a2e1-403d-8ad5-4df9b0cb7314" />

<img width="1692" height="960" alt="Screenshot 2025-08-29 094528" src="https://github.com/user-attachments/assets/72599d46-3629-4067-ad0f-8b95a9f3d000" />

<img width="1556" height="848" alt="image" src="https://github.com/user-attachments/assets/74ff782a-dd02-4aee-85f3-fd05adb69230" />

<img width="1699" height="964" alt="Screenshot 2025-08-29 093226" src="https://github.com/user-attachments/assets/141d2326-d2ac-45de-9c30-27704cf0affb" />

### Result:
Thus, the implement preprocessing technique on Twitter Data using Rapidminer.
