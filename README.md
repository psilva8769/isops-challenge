# Technical challenge - IS Ops Specialist

## Challenge context

 There are several files and data that need to be processed and transformed to feed the system optimally. The files contain data about candidates and their movements in different job positions.

### Part 1: Data conversion and formatting

File conversion:
<ul><li>Convert the file "Dados_Candidatos.xlsx" to CSV format while maintaining data integrity.</ul>
<br>

Data reformatting:
<br> - The file contains several lines related to the same candidate, each line referring to the candidate's movement to the respective stage. <ul><li>Transpose these lines so that each stage is a distinct column and the cells contain the date of movement, so there is only one line per candidate in the final file.</ul>
<br>

Data structuring: 
- Ensure that the final CSV file has the following structure:

| ID_Candidate | Name_Candidate | ID_Position | Name_Position | Application_Date | Status | Stage1Date | Stage2Date
| --- | --- | --- | --- | --- | --- | --- | --- | 
|-|-|-|-|-|-|-|-|

And so on...

Data format:
<br> - Ensure that the data in the final CSV file comply with the following restrictions:
<ul><li>Dates: ISO8601 format
<li>Status: possible values are: <ul><li>Active
<li>Rejected
<li>Declined</ul></ul>

### <br>Part 2: Data Aggregation

File consolidation:
<br> - You have XLSX files separated by month (e.g., "Jan.xlsx", "Feb.xlsx"). <ul><li>Combine all these files into a single file by consolidating the data into a single table.</ul>

<br>Sheet merging:
<br> - The file "Dados_Consolidados.xlsx" contains different sheets for each department of the company. <ul><li>Merge the data from all these sheets into a single sheet/table.</ul>

<br>General instructions:
<ul><li>All transformations must maintain the integrity and accuracy of the data.</li>
<li>Create a small report or commentary explaining the steps you followed for each part of the challenge.</li>
<li>Highlight any difficulties or data problems you encountered and how you resolved them.</li></ul>

<br>Deliverables:
<br><ul><li>Final CSV file with data formatted as specified.</li>
<li>A consolidated XLSX or Google Sheets file with data from all months.</li>
<li>A consolidated XLSX or Google Sheets file with one sheet containing all unified department data.</li>
<li>Report or comments on the process, challenges, and solutions applied during the challenge.</li></ul>

<br>Evaluation criteria:
<br> - Data Accuracy: Are the data accurate and correctly formatted and transposed?
<br> - Efficiency: Are the proposed and executed solutions efficient and logical?
<br> - Report: Are the explanations clear and challenges/solutions well communicated?