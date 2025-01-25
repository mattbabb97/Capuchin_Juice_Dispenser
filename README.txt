Title: Social closeness affects prosocial behavior in capuchin monkey groups

Summary: Although relationships are hypothesized to influence prosocial behavior in capuchin monkeys, finding evidence has been challenging. For our study, we tested prosocial behavior in intact social groups, 
rather than pre-determined dyads, allowing monkeys to choose whether, when, and to whom to donate juice rewards. Capuchins showed prosocial behavior, and preferentially donated juice to group members with whom they 
shared strong affiliative relationships. Induced oxytocin increased overall interactions with the apparatus, but did not influence prosocial behavior or vary by relationship quality. Thus, we demonstrate the 
importance of social relationships on prosocial behavior, providing valuable insights into how natural social dynamics shape decision-making in group-living animals.

Code version: R Markdown

Repository contains both .xlsx files containing the data and .rmd files containing the code to run all statistical tests and figure generation

MSc Model 1 - Task Comprehension [FINAL].RMD
	This file uses the data from Model_1_Data_Frame.xlsx to examine how often the subjects pressed the lever across all sessions. 
	This is session level data used to examine task comprehension.
	It also pulls from Model_1_Runs_per_Session.xlsx to remove lever presses that were followed by runs, which we looked at in the supplementary material.
	This .RMD file  generates Figure 2

MSc Model 2 - Relationships [FINAL].RMD
	This file uses the data from Model_2_Data_Frame.xlsx to examine how often the subjects pressed the lever for specific recipients.
	This .xlsx file is also session level data, but divided by the different types of lever presses
	This .RMD file generates Figure 3

MSc Model 3-4 - Reciprocity [FINAL].RMD
	This file uses the data from Model_3_Data_Reciprocity.xlsx to examine whether the subjects engaged in reciprocity
	This .xlsx file is session level data, but divided by the different recipients in their group
	This .RMD file generates Figure 4

Msc Model 5 - Running [FINAL].RMD
	This file uses data from Model_5_Data_Frame.xlsx to examine the likelihood of a subject running toward the dispenser after pressing
	This .xlsx file is a trial level data, each line of code represents one lever press
	This .RMD file generates Figure 5

All demographic files include the subject's rank, sex, and demographic information for merging purposes. We included multiple files with the same information
because one individual's name was spelled two different ways ("Scarlett" and "Scarlet")

Instructions:
	All .RMD files are separated into chunks and titled with the purpose of the chunk.
	The chunks are intended to be run in sequential order, from Line 1 onward.
	To run a chunk on PC, simply press CTRL+Enter to run it and move to the next chunk.
	
	All figures are automatically saved as .png files into the Working Directory
