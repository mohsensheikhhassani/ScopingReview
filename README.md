# ScopingReview
Legal Concerns in Health-Related Artificial Intelligence: A Scoping Review
Muliple steps were used for data extraction which are include in this repository
The steps included bucketing of the different solutions based on various factorts, and conversion into different file formats

Below is a summary of steps on how to reproduce the qualitative data analysis results using the code and data:
Two spreadsheets were created based on the data extracted from the databases, one including Record Demographics and the other Record Data Extraction. These are saved and referred to as Book2 and Book1 in the code, respectively (and saved in a local directory).
Record_Demographics_dir = "D:\\M.Sheikh\\Book2.xlsx"
Record_Data_Extraction = "D:\\M.Sheikh\\Book1.xlsx"

Script 1 can be run to identify topics mentioned in each paper, and then categorize them based on the corresponding faculty. For each paper, this categorization will take place and result in a number of files based on host faculty and topics mentioned, will include the quote of the text mentiond in the paper, and also a series of additional information such as article number, journal name, etc are extracted from the excel sheets and added into arrays.

Script2 converts the resulting file into readible and easy to review word files with improved formatting.

Script 3 breaks down the document by type of solution proposed in each paper. All solutions belonging to the similar category will be listed in one document. This will result in a single folder with files for all the solutions, with files including solutions1,2 and 3 - separate files created for each of the solutions (such as reforms of existing laws, litigation, International treaty, etc). Again, the solution quotation as well as additional information such as article title, journal name, etc, will also be appended. We then create one plot for each of the topics mentioned, with the first bar of the plot showing the overall number of times the topic has been mentioned, and the rest of the bars showing how many times the topic has been mentioned broken down by discipline.
