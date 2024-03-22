# Project 2: Crowdfunding_ETL

## Collaborators: David Kogge and Dan Kramer

### Division of Responsibilities:

David constructed and exported the category and campaign data frames, and worked on the Schema files in preparation for use in SQL. He imported the tables into SQL and tested their efficacy using SELECT commands to ensure everything worked properly. David also provided screenshots of these SELECT commands.

Dan constructed and exported the subcategory and contacts data frames. He was also responsible for the construction of the README.

David and Dan consulted each other as needed during table and schema creation, and contributed to each other’s progress and coding when necessary.

### Deliverables
Final combined work for the data frames can be found in the file “ETL_Mini_Project_DKogge_DKramer.ipynb.”

The schema diagram can be referenced in the file “crowdfunding_db_schema.png”

The schema utilized to create our tables in SQL can be found in the file “crowdfunding_db_schema.sql”

Screenshots demonstrating the tables working in the SQL environment (see below in README) can be found in the "Resources/SQL Images" folder.

### Dataframe Verification

David and Dan were able to successfully replicate the data frame results as shown in the Project 2 information. The following images are the results achieved after running the notebook:

------------------------------

![category_df](https://github.com/DKogge/Crowdfunding_ETL/assets/147351952/ea99ecda-f1fc-45b4-a144-deff5593c99a)

------------------------------

![subcategory_df](https://github.com/DKogge/Crowdfunding_ETL/assets/147351952/af88803c-44f5-4c30-bde8-2ec9efe4dd9c)

------------------------------

![campaign_cleaned_df](https://github.com/DKogge/Crowdfunding_ETL/assets/147351952/1aa95e93-6a2a-48e9-8eae-1686d8afe60f)

------------------------------

![cleaned_contacts_df](https://github.com/DKogge/Crowdfunding_ETL/assets/147351952/31cf5cff-e24d-4392-baaf-ffe607415203)

------------------------------


### Schema Diagram
For simple reference, this is an image of the schema relationships:

![crowdfunding_db_schema](https://github.com/DKogge/Crowdfunding_ETL/assets/147351952/730ff80a-a833-4f0d-b3c1-50d3c6f71aa0)

------------------------------
 
### SQL Verification
In order to verify that the schema imported properly when accessing them via SQL using PGAdmin 4, we have captured the following images. The images were created using simple SELECT * statements to show a return result of the tables within PGAdmin 4.

------------------------------

First, a screenshot to show the crowdfunding_db database structure:

<img width="355" alt="Screenshot SQL DB and Tables" src="https://github.com/DKogge/Crowdfunding_ETL/assets/147351952/1ed77457-4427-4191-aa0d-29e9893ab506">

------------------------------

This is a screenshot of what returned for the “campaign” table:

 
 <img width="1817" alt="Screenshot SQL Campaign Table" src="https://github.com/DKogge/Crowdfunding_ETL/assets/147351952/242e074f-34b9-46ce-b530-4bcdc4c3c382">

 
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

