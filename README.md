# StepMania .ssc/.sm files extractor project

## Used technologies:
**C++, MySQL, Power BI**

## Description:
In this project, I used my own custom packs created for the rhythm game StepMania.

The program, written in C++, extracts all necessary information from .ssc or .sm files to a ChartsData.txt and NotesData.txt files.
An .ssc/.sm file is used in the rhythm game StepMania; in short, each individual file stores all information about a song and its corresponding chart.

In the SQL folder, you will find .csv files that were converted from .txt files generated by the C++ program. These tables were then processed in SQL (Data Cleaning), and I added several interesting queries for analysis. Finally, the cleaned data was visualized in Power BI (see the Power BI visualization folder).

## How does it work?
To make the extraction program work:
- you need to place sample StepMania packs containing .ssc files into the Packs folder: bin -> x64 -> Debug -> Packs -> example pack 1 -> song folder -> (this is where the .ssc or/and .sm file is located)
- run the "StepMania .ssc/.sm files extractor.exe" and follow the instructions: bin -> x64 -> Debug folder
- data will be saved in ChartsData.txt and NotesData.txt for future data cleaning and analysis!

## Folders:
- SQL Folder – .csv tables, data cleaning/data analysis queries and ready database in .sql files
- PowerBI visualization Folder – visualization .pbix file and example screenshots

## Change Log:
- 04.04.2025 - changed project name to "StepMania .ssc or .sm files extractor"
- 04.04.2025 - fixed counting objects if .ssc/.sm file has number of measures in #NOTES section
- 04.04.2025 - added support to .sm files in case there is no .ssc file (if both files are present, .ssc file is prioritized)
