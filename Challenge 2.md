# Challenge 2: Build Structure (Data Model)

## Background

You showed the data model diagram to the CTO, He expressed his satisfaction and appreciation for your work. He then instructed you to proceed with the next phase of the project. He asked you to start building the data model structure in Microsoft Dataverse, using the diagram as a guide. He specified that you should add 'Broken Material', 'Server Room Related', 'Internet Problems', 'AC Problems', 'Sick Employee' in problems 

## Challenge

For this challenge, you'll use Microsoft Dataverse to make a data model. Start by making some tables and listing out what goes inside them. When adding things to the tables, think about the choices you need to include. Make sure you show how these tables connect to each other. You'll also import some department information from an Excel file. You will also assign each problem type to a department. When you're all done, present the data model to your coach.

#### Hints

- When creating the tables, in the 'Primary Column' section, select 'Advanced options', change 'Required' from 'Business Required' to 'Optional'
- When creating the 'ProblemType' column, select 'New Choice' to add a Choice (Note: Do not change the 'Value' when adding a new choice)
- When you create the correct relationship, a 'Department' column of type 'Lookup' will be automatically created in 'Problems' table
- Your coach will provide an excel file containing data for a table, import it and map the correct columns(They share the same name).
- In the 'Problems' table, for each row you create, manually assign each 'ProblemType' to a 'Department' as this will be considered as our matrix table (double tap on each cell to add data)
- When you complete all the steps, in 'Objects' select 'all', then click on 'Publish all customizations'

## Success Criteria

- Create a data model with the correct tables and their respective columns, including a relationship according to the data model diagram you previously drew
- 'ProblemType' should be of type 'Choice' and synced with the correct choices
- Able to see the data you imported into table 'Department', and the data manually added into table 'Problem'
- Present your data model to your coach

## Prerequisites

#### - Complete Challenge 1 


## References
- [Data modeling documentation](https://learn.microsoft.com/en-us/power-platform-release-plan/2022wave2/data-platform/data-modeling)
- [Dataverse documentation](https://learn.microsoft.com/en-us/power-apps/maker/data-platform/)
- [Overview documentation](https://learn.microsoft.com/en-us/power-platform/)
- [Import or export data from Dataverse](https://learn.microsoft.com/en-us/power-apps/maker/data-platform/data-platform-import-export)
