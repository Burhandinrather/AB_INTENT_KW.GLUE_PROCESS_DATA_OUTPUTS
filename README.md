# AB_INTENT_KW.GLUE_PROCESS_DATA_OUTPUTS
This folder contains the SQL Script which has been used to create and import Data tables in GLUE_PROCESS_DATA_OUTPUTS Schema.
The Schema contains four different tables   i. EVENTS_DATALAKE  ii. EY  iii. INTERXION iv. MAERSK
We have created four different stages in the Script which we have been used to get the data from AWS S3 bucket and then using the COPY command we load the data from those stages  into the Snowflake tables.
We are not loading data in the above tables in an automated manner using the Snow Pipe as it was the one time process
