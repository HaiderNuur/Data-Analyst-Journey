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

# Week two
- Data bias: a type of error that systematically skews results in a certain direction.
- Sampling bias: when a sample isn’t representative of the whole population as a whole. Unbiased or Random sampling to avoid this.
- Observer bias/ experimenter bias/ research bias: the tendency for different people to observe things differently 
- Interpretation bias: the tendency to always interpret ambiguous situations in a positive or negative way 
- Confirmation bias: the tendency to search for or interpret information in a way that confirms pre-existing beliefs
- Good data sources: data that agree with ROCCC (reliable, original, comprehensive, current, cited. 
- Bad data: that not ROCCC
- Data ethics: well-founded standards of right and wrong that dictate how data is collected, shared, and used. 
- Aspects of data ethics: ownership, transaction transparency, consent, currency, privacy, openness. 
- Ownership: individuals that own data they provide and they have primary control over its usage, how it’s processed and how it’s shared. 
- Transaction transparency: all data-processing activities and algorithms should be completely explainable and understood by the individual who provides their data. 
- Consent: an individual‘s right to know explicit details about how and why their data will be used before agreeing to provide it. 
- Currency: individuals should be aware of financial transactions resulting from the use of their personal data and the scale of these transactions.
- Privacy: preserving a data subject‘s information and activity any time a data transaction occurs


Data privacy concerns the following:
- protection from unauthorised access to our private data.
- freedom from inappropriate use of our data 
- the right to inspect, update, or correct our data 
- ability to give consent to use our data 
- legal right to access the data 

- Openness: free access, usage and sharing of data 
- Standards to maintain in order to be open data: availability and access, reuse and redistribution, universal participation. 
- Benefits of open data: get credible good databases, all of that good data can be leveraged, shared and combined with other data. 
- Data interoperability: the ability of data systems and services to openly connect and share data. 
- Personal identifiable information (PII) is data that is reasonably likely to identify a person and make information known about them. It is important to keep this data safe. - - PII can include a person’s address, credit card information, social security number, medical records, and more.
- Data anonymization is the process of protecting people's private or sensitive data by eliminating that kind of information. Typically, data anonymization involves blanking, hashing, or masking personal information, often by using fixed-length codes to represent data columns, or hiding data with altered values. 
- Here is a list of data that is often anonymized: Telephone numbers, Names, License plates and license numbers, Social security numbers, IP addresses, Medical records, Email addresses, Photographs, Account numbers.

# Week three

- Meta data: data about data 
- A relational database is a database that contains a series of related tables that can be connected via their relationships.
- Primary key: an identifier that references a column in which each value is unique , not null or blank 
- Metadata is used in database management to help data analysts interpret the contents of data within a database 
- 3 types of metadata: descriptive, structural and administrative 
- Descriptive metadata: describes a piece of data and can be used to identify it at a later point of time.
- Structural metadata: indicates how a piece of data is organised and whether it is part of one, or more than one data collection. 
- Administrative metadata: indicates the technical source of a digital asset .

Benefits of metadata: 
- metadata creates a single source of truth by keeping things consistent and uniform. 
- metadata also makes data more reliable by making sure it’s accurate, precise, relevant and timely. 

Metadata repository: a database specifically created to store metadata. They describe the state and location of metadata, the structure of the tables inside, and how data flows through the repository, keep track of who accesses the data and when. 

- Metadata is stored in a single, central location and it gives the company standardised information about all of its data. 
- Data governance is a process to ensure the formal management of a company’s data assets.


**Open data helps create a lot of public datasets that you can access to make data-driven decisions. Here are some resources you can use to start searching for public datasets on your own:

- The Google Cloud Public Datasets allow data analysts access to high-demand public datasets, and make it easy to uncover insights in the cloud. 
- The Dataset Search can help you find available datasets online with keyword searches. 
- Kaggle has an Open Data search function that can help you find datasets to practice with.
- Finally, BigQuery hosts 150+ public datasets you can access and use. 

Public health datasets
- Global Health Observatory data: You can search for datasets from this page or explore featured data collections from the World Health Organization.  
- The Cancer Imaging Archive (TCIA) dataset: Just like the earlier dataset, this data is hosted by the Google Cloud Public Datasets and can be uploaded to BigQuery.
- 1000 Genomes: This is another dataset from the Google Cloud Public resources that can be uploaded to BigQuery. 

Public climate datasets
- National Climatic Data Center: The NCDC Quick Links page has a selection of datasets you can explore. 
- NOAA Public Dataset Gallery: The NOAA Public Dataset Gallery contains a searchable collection of public datasets.

Public social-political datasets
- UNICEF State of the World’s Children: This dataset from UNICEF includes a collection of tables that can be downloaded.
- CPS Labor Force Statistics: This page contains links to several available datasets that you can explore.

The Stanford Open Policing Project: This dataset can be downloaded as a .CSV file for your own use.

# Week four
## Feel confident in your data
- Benefits of organizing data: makes it easier to find and use, helps you avoid making mistakes during your analysis, helps to protect your data
- Best practices when organizing data: naming conventions, foldering, archiving older files
- Two more things: align your naming and storage practices with your team, develop metadata pracctices

File naming DO's
- work out your conventions early
- align file naming with your team
- make sure file names are meaningful
- keep file names short and sweet
- Format dates yyyymmdd: SalesReport20201125
- Lead revision numbers with 0: SalesReport20211201v02
- Use hyphens, underscores, or capitalized letters: Sales_Report_2020_11_22_v02

### Security features in spreadsheets
- Data security: Protecting data from unauthorized access or corruption by adopting safety measures
- Usually the purpose of data security is to keep unauthorized users from accessing or viewing sensitive data. Data analysts have to find a way to balance data security with their actual analysis needs. This can be tricky-- we want to keep our data safe and secure, but we also want to use it as soon as possible so that we can make meaningful and timely observations. 
- Encryption uses a unique algorithm to alter data and make it unusable by users and applications that don’t know the algorithm. This algorithm is saved as a “key” which can be used to reverse the encryption; so if you have the key, you can still use the data in its original form.  
- Tokenization replaces the data elements you want to protect with randomly generated data referred to as a “token.” The original data is stored in a separate location and mapped to the tokens. To access the complete original data, the user or application needs to have permission to use the tokenized data and the token mapping. This means that even if the tokenized data is hacked, the original data is still safe and secure in a separate location. 
- 
