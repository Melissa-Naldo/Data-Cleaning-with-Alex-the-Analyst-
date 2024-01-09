# Data-Cleaning-with-Alex-the-Analyst-

In this document, I will provide a comprehensive overview of the data cleaning steps undertaken during the [Alex the Analyst Cleaning Tutorial](https://www.youtube.com/watch?v=_jmiEGZ6PIY&list=PLp2Apd97xy_RullBm_1ZBqA7aPpN5BNz3&index=5&t=1067s) with Microsoft Excel. 

## **Data Cleaning Steps:**

+ _**Changed Column Names:**_	Renamed columns to ensure clarity and consistency in data representation.

+ _**Remove Duplicates:**_ N- avigated to the Data tab and utilized the “Remove Duplicates” function, resulting in the removal of two duplicate entries.

+ _**Proper Case in the President Column:**_ Applied **‘=PROPER()’** function to format the President column, ensuring that every name starts with a capital letter followed by lowercase letters.

+ _**Corrected Spelling with Find and Replace:**_ Utilized the Find and Replace function to correct the spelling of "democratic" to "Democratic." Corrected party affiliations by changing “Republicans” to “Republican” and updating “Whig April 4, 1841 – September 13, 1841” to simply “Whig.”

+ _**Trim Function on Vice-President Column:**_ Applied the Trim function to the Vice-President column to remove any leading or trailing spaces.

+ _**Transformed Salary Data Type:**_ Transformed the data type of the Salary column to a numeric format, facilitating easier SQL analysis.

+ _**Uniformized Date Formats:**_ Standardized all date formats to dd/mm/yyyy, ensuring consistency across the dataset.

+ _**Deleted Unnecessary Columns:**_ Removed the first column and the preceding column, streamlining the dataset for improved clarity and simplicity.

These data cleaning steps were crucial to enhance the accuracy, consistency, and usability of the dataset for subsequent analysis. The refined dataset is now better prepared for SQL analysis, providing a solid foundation for deriving meaningful insights.


## Raw Dataset
![Raw Dataset](https://github.com/Melissa-Naldo/Data-Cleaning-with-Alex-the-Analyst-/blob/main/Images/Uncleaned%20dataset.jpg)


## Cleaned Dataset
![Cleaned Dataset](https://github.com/Melissa-Naldo/Data-Cleaning-with-Alex-the-Analyst-/blob/main/Images/Cleaned%20dataset.jpg)
