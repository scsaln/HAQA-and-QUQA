================================================================
QUQA  Version 1.0 and HAQA Version 1.0
QUQA: Test Collection for Arabic Question Answering on the Holy Quran
HAQA: Test Collection for Arabic Question Answering on the Hadith Sharif
April 5, 2023
================================================================

The following table describes the QUQA Annotation:

-------------------------------------------------------------------------------------------------------------------------------------------------
|Annotation	                       | Description                                                                                                |
-------------------------------------------------------------------------------------------------------------------------------------------------
|Record_Id	                       |The unique record number.                                                                                   |
|Question_Id                       |The question number may appear many times in this dataset in two situations:                                |
|                                  |1.      The questions have many different answers.                                                          |
|                                  |2.      The questions have one answer but are mentioned in many different verses in Quran.                  |
|Question_Text                     |The question text                                                                                           |
|Quetion_Type                      |The type of question can be Factoid (F), Confirmation (C) or Descriptive (D).                               |
|Question_Start_Word	           |The question keyword.                                                                                       |
|Answer_ID	                       |The answer number to the same questions uniquely.                                                           |
|                                  |1) If the question has only one answer in a sense, but it came in totally or partly in different            |
|                                  |verses with different syntax, the numbering is done 1.1 and 1.2 and so on.                                  |                  
|                                  |2) If the question has different answers in the same or different verses, the numbering is done 1, 2, 3 etc.|
|Full_Answer	                   |The whole answer consists of the Expert Commentary, the Quran Verse and Hadith.                             |
|Expert_Commentary	               |Answer using the expert's words only.                                                                       |
|Answer-Instances	               |The exact part from the verse that answers the question.                                                    |
|                                  |The verse may contain more than one answer, and each answer considers an answer instance.                   |
|Quran_Full_Verse_Answer	       |The complete verse that considered the answer or contains the answer.                                       |
|Chapter_Name	                   |The chapter name                                                                                            |
|Chapter_Number	                   |The chapter number                                                                                          |
|Verses_Number_Start	           |The First verse number.                                                                                     |
|Verses_Number_End	               |The Last verse number.                                                                                      |
|Source_Name	                   |The name of the source.                                                                                     |
|Source_Link	                   |The link to the source.                                                                                     |
|Credibility                       |Yes, if an Islamic expert reviews the answers. No, if it is not.                                            |
|Question_ID_in_the_Orignal_Dataset|The Question ID in the Orignal Dataset.                                                                     |                                                    
-------------------------------------------------------------------------------------------------------------------------------------------------

The following table describes the HAQA Annotation:

-------------------------------------------------------------------------------------------------------------------------------------------------
|Annotation	                       | Description                                                                                                |
-------------------------------------------------------------------------------------------------------------------------------------------------
|Record_Id	                       |The unique record number.                                                                                   |
|Question_Id                       |The question number may appear many times in this dataset in two situations:                                |
|                                  |1.      The questions have many different answers.                                                          |
|                                  |2.      The questions have one answer but are mentioned in many different verses in Hadith..                |
|Question_Text                     |The question text                                                                                           |
|Quetion_Type                      |The type of question can be Factoid (F), Confirmation (C) or Descriptive (D).                               |
|Question_Start_Word	           |The question keyword.                                                                                       |
|Answer_ID	                       |The answer number to the same questions uniquely.                                                           |
|                                  |1) If the question has only one answer in a sense, but it came in totally or partly in different            |
|                                  | Hadith with different syntax, the numbering is done 1.1 and 1.2 and so on.                                 |                  
|                                  |2) If the question has different answers in the same or different Hadith, the numbering is done 1, 2, 3 etc.|
|Full_Answer	                   |The whole answer consists of the Expert Commentary, the Quran Verse and Hadith.                             |
|Expert_Commentary	               |Answer using the expert's words only.                                                                       |
|Answer-Instances	               |The exact part from the The Hadith that answers the question.                                               |
|                                  |The Hadith may contain more than one answer, and each answer considers an answer instance.                  |
|Hadith_Full_Answer        	       |The entire Hadith includes Isnad and Matn.                                                                  |
|Hadith_Matn	                   |The real Hadith teaching.                                                                                   |                                                                                        
|Source_Name	                   |The name of the source.                                                                                     |
|Source_Link	                   |The link to the source.                                                                                     |
|Credibility                       |Yes, if an Islamic expert reviews the answers. No, if it is not.                                            |
|Question_ID_in_the_Orignal_Dataset|The Question ID in the Orignal Dataset.                                                                     |                                                    
-------------------------------------------------------------------------------------------------------------------------------------------------

Note: the HAQA will be released soon.

If you use thess corpora, kindly site the paper:


If you would like to submit corrections or comments about the corpus please send an email to:
scsaln@leeds.ac.uk
