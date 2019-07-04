
The activity is for creating an APPRAISAL LETTER.

The process consist of two files:

Word file (/Data/IncrementTemplateLetter.docx): Appraisal Letter is in word format, we have to fill the data here.

Excel file (/Data/IncrementData.xlsx): consist of all data to be included in word.


NOTE: We have to perform this activity using orchestrator.

Steps:

1.Create a Queue by the Name 'Appraisal_LetterQueue' in Orchestrator.
2.Open UiPath Start Robotic Enterprise Framework.

The data provided in excel needs to be stored in Queue. (Using Orchestrator)


Fetch these data from Queue.
Generate a word doc for each employee. 
 

Rules:

The data needs to be filled for each employee as per given in the excel sheet.
For '<MonCTC>' in the template, fill the Monthly Gross data from excel, also mention the amount in words.
For '<wef>' add the date given in 'w.e.f' column in excel.
In the table section, the monthly amount will be the same provided in the excel.
For annual amount, have to calculate the amount of monthly and fill it accordingly. 
 

Note: You have to run the project from Orchestrator.

For your reference I have attached an example appraisal letter (/Data/Example_RajeshJain.docx).
