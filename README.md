# ScopingReview
Github page: https://github.com/mohsensheikhhassani/ScopingReview/tree/main
Legal Concerns in Health-Related Artificial Intelligence: A Scoping Review 

The data extraction and analysis for this study included multiple steps. The data, steps for analysis, and associated computer code, are provided in this repository. 
Data extraction
Relevant data was extracted from the dataset of 432 included records using a pilot-tested Excel-based extraction tool and guidance document. 
The data was put into two spreadsheets, one including record demographics and the other including extracted discussions of legal issues and solutions. These are saved and referred to as Book2 and Book1 in the code, respectively (and saved in a local directory). Record_Demographics_dir = "D:\M.Sheikh\Book2.xlsx" Record_Data_Extraction = "D:\M.Sheikh\Book1.xlsx"
These can be accessed here upon approval : https://drive.google.com/drive/folders/1Ml0DGQw_GQ5zIBXR5rffeNi9qkp2_UW1?usp=sharing

Quantitative analysis was based on the extracted data, organized by legal issue, solution type, and faculty of the corresponding author. 

Script 1 groups the extracted text by the legal issue under discussion, further categorizing it by the faculty of the corresponding author. It results in multiple files with grouped quotes, along with associated bibliographical information, such as author and journal name, added into arrays.

Script2 converts the resulting files into a more readable Word files with improved formatting.

Script 3 groups extracted text relating to solutions to legal problems. It results in separate documents listing all solutions belonging in each category (e.g., reforms of existing laws, litigation, international treaty, etc.,) along with a single folder including all these ‘solutions’ files. Solution quotes are provided alongside bibliographical information such as article title and journal name. 

We then create one plot for each of the topics mentioned, with the first bar of the plot showing the overall number of times the topic has been mentioned, and the rest of the bars showing how many times the topic has been mentioned broken down by discipline. These plots are not the plots used in the review itself, rather created to give a better understanding of our data to the authors of the review.
