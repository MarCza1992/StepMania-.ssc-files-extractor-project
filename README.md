Used technologies:
C++, MySQL, Power BI

In this project, I used my own custom packs created for the game StepMania.

The program, written in C++, extracts all necessary information from .ssc files to a ChartsData.txt and NotesData.txt files.
An .ssc file is used in the rhythm game StepMania; in short, each individual file stores all information about a song and its corresponding chart.

In the SQL folder, you will find .csv files that were converted from .txt files generated by the C++ program. These tables were then processed in SQL (Data Cleaning), and I added several interesting queries for analysis. Finally, the cleaned data was visualized in Power BI (see the Power BI visualization folder).

To make the extraction program work, you need to place sample StepMania packs containing .ssc files into the Packs folder and run the "StepMania .ssc files extractor.exe" in the bin -> x64 -> Debug folder.
For example:
bin -> x64 -> Debug -> Packs -> example pack 1 -> song folder -> (this is where the .ssc file is located)

SQL Folder – .csv tables, data cleaning scripts, and SQL queries

PowerBI visualization Folder – visualizations and example screenshots
