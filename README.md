# Project 2: Crowdfunding_ETL

## Collaborators: David Kogge and Dan Kramer
### Division of Responsibilities:
David constructed and exported the category and campaign data frames, and worked on the Schema files in preparation for use in SQL. He imported the tables into SQL and tested their efficacy using SELECT commands to ensure everything worked properly. David also provided screenshots of these SELECT commands.
Dan constructed and exported the subcategory and contacts data frames. He was also responsible for the construction of the README.
David and Dan consulted each other as needed during table and schema creation, and contributed to each other’s progress and coding when necessary.
### Deliverables
Final combined work for the data frames can be found in the file “ETL_Mini_Project_DKogge_DKramer.ipynb.”
The schema diagram can be referenced in the file “Schema Tables.png”
The schema utilized to create our tables in SQL can be found in the file “crowdfunding_db_schema.sql”
Screenshots demonstrating the tables working in the SQL environment (see below in README) can be found in the Resources/Sequel Images folder.
### Schema Diagram
For simple reference, this is an image of the schema relationships:
 
### SQL Verification
In order to verify that the schema imported properly when accessing them via SQL using PGAdmin 4, we have captured the following images. The images were created using simple SELECT * statements to show a return result of the tables within PGAdmin 4.

------------------------------

This is a screenshot of what returned for the “campaign” table:

 
 <img width="1884" alt="Screenshot SQL Campaign Table" src="https://github.com/DKogge/Crowdfunding_ETL/assets/147351952/72a6bd70-2f7d-4929-a2a5-11d58a75180c">

------------------------------

The following screenshot shows the “categories” table:

 
 <img width="1081" alt="Screenshot SQL Category Table" src="https://github.com/DKogge/Crowdfunding_ETL/assets/147351952/b6da8fcf-7d88-4265-afd4-29fb9b362ba9">

------------------------------

Next is a screenshot of the “subcategories” table:

 
 <img width="1145" alt="Screenshot SQL Sub_Category Table" src="https://github.com/DKogge/Crowdfunding_ETL/assets/147351952/4d421f6a-f7a7-42fc-a158-56543c13827c">

------------------------------

This is a screenshot of the “contacts” table:


 <img width="1178" alt="Screenshot SQL Contacts Table" src="https://github.com/DKogge/Crowdfunding_ETL/assets/147351952/b7a790d5-6ed2-4b72-93e8-6c87945f99f9">

------------------------------

Finally, we’ve included a screenshot showing the Foreign Keys relationship within the “campaign”
 table, which references the other tables from the project:

 
 <img width="251" alt="Screenshot SQL Foreign Keys" src="https://github.com/DKogge/Crowdfunding_ETL/assets/147351952/8d515e57-b50d-421b-b5b2-36b69e8ddd5a">

------------------------------

