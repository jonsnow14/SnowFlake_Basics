## Data Ingestion with snowflake 

> Data Ingestion in snowflake can be categroized into two categorirs -Batch Ingestion and Streaming Ingestion

>> Batch Ingestion.   
>>>  Data processed in Large,Discrete chunks    
>>>  onetine event/scheduled intervals    
>>>  Typically used in scenarios where real time processing/utlization of data is not critical    
>>>  Typically used   when large amount of data is ingested at a frequency      
    
>> Steps Involved in batch Ingestion  
>>> 1.Prepare Data File  
>>>2.Staging/Storing Data Files somewhere , common AWS S3 bucket, local computers, other data systems  
>>>3.Perform the ingestion with SQL or Python  
        
>>Data Laoding    
>>>Load Data from Snowflake Market place  
>>>Load Data from Snowflake's web inteference  
>>>Load Data from local using Snowflake's CLI  
>>>COPY INTO SQL command to load data from files in cloud into snowlake  


>>Load data from snowflake market place (steps involved)
>>>Log into snowflake account
>>>Click on MarketPlace 
>>>Search for data
>>>click get
>>>Upon appearance of dropdown menu , select options to rename database and roles to access DB
>>>Click Get
>>>Upon successfull loading a Ready to use pop up will appear along with Query Data options
>>>Query Data will open a SQL worksheet 
>>>Start Exploring 
>>>Note upon successfull loading of Data a database would be created  wich user can work onto.
        
Loading Data using Snowflake's Web interface.










Streaming Ingestion  
    Continous Real time, Near Real time- data ingestion  
    Deals with dta piece fby Piece virtually continously  
    Comman use case  like finacial trading  
    
