# Week One

Data collection considerations
- How the data will be collected, Choose the data sources, Decide what data to use, How much data to collect, Select the right data type, Determine the time frame
- Nominal data: type of qualitative data that is categorized without a set of order. Example> Answer of the question "Did you watch this movie?" > Yes, NO, Not sure
- Ordinal data: A type of qualitative data with a set order or scale. Example: Ranking of movie in 1 to 5.
- Internal data: data that lives in a company's own system. Example: If a movie studio has compiled all the data in the spreadsheet using their own collection methods, then it would be their internal data
- External data: generate outside organisation. if the movie studio has to use movie data that is owned or shared by other studios and sources.
- Data model: A model that is used for organising data elements and how they relate to one another
- Data models help to keep data consistent and provide a map of how data is organised. This makes it easier for analysts and other stakeholders to make sense of their data and use it for business purposes.
- Structured data: defined data types, most often quantitative data, easy to organize, easy to search, easy to analyze, stored in relational databases & data warehouses, contained in rows and columns, examples: excel, google sheets, SQL, customer data, phone records, transaction history
- Unstructured data: varied data types, most often qualitative data, difficult to search, provides more freedom for analysis, stored in data lakes, data warehouses, and NoSQL databases, can't be put in rows and columns, Examples: text messages, social media comments, phone call transcripts, various log files, images, audio, video
- Three most common types of data modeling: Conceptual (business concepts), Logical (Data Entities), Physical (Physical Tables)
- Conceptual data modeling gives a high-level view of the data structure, such as how data interacts across an organization. For example, a conceptual data model may be used to define the business requirements for a new database. A conceptual data model doesn't contain technical details. 
- Logical data modeling focuses on the technical details of a database such as relationships, attributes, and entities. For example, a logical data model defines how individual records are uniquely identified in a database. But it doesn't spell out actual names of database tables. That's the job of a physical data model.
- Physical data modeling depicts how a database operates. A physical data model defines all entities and attributes used; for example, it includes table names, column names, and data types for the database.
- Data modeling techniques: ERD (Entity Relationship Diagram), UML (Unified Modeling Language)
- ERDs are a visual way to understand the relationship between entities in the data model.
- UML diagrams are very detailed diagrams that describe the structure of a system by showing the system's entities, attributes, operations, and their relationships. 
- Wide data: data in which every data subject has a single row with multiple columns to hold the values of various attributed of the subject. It lets you easily identify and quickly compare different columns. 
- Wide data is preferred when creating tables and charts with a few variables about each subject, comparing straightforward line graphs
- Long data: Data in which each row is one time point per subject, so each subject will have data in multiple rows
- long data is preferred when storing a lot of variables about each subject, For example: 60 years worth of interest rates for each bank, performing advanced statistical analysis or graphing
- Data transformation usually involves: Adding, copying, or replicating data, Deleting fields or records, Standardizing the names of variables, Renaming, moving, or combining columns in a database, Joining one set of data with another, Saving a file in a different format. For example, saving a spreadsheet as a comma separated values (CSV) file.
- Goals for data transformation might be: Data organization: better organized data is easier to use, Data compatibility: different applications or systems can then use the same data, Data migration: data with matching formats can be moved from one system to another, ta merging: data with the same organization can be merged together, Data enhancement: data can be displayed with more detailed fields  comparison: apples-to-apples comparisons of the data can then be made 


