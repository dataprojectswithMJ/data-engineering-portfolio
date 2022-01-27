# Welcome to my Data engineering portfolio
The project behind this portfolio is an open source data API that I built and maintain..
<br></br>
----------------------------------
[__You can try the API__](https://covidza-data.deta.dev/docs)
<img src='API_test.png' width='800'>
<br></br>
-----------------------------------

There are several parts to this project:
 - Web scraping and resource downloading
 - Data extraction and transformation
 - Loading to the MongoDB Database
 - Creating the API and making it accessible
<br></br>

There are a number of problems with this project, naming just a few:
 - Reliable data sources
 - Scalable yet affordable hosting (it is open source after all)
 - Useable formats
 - Open source APIs

Fortunately, the <a href="https://www.nicd.ac.za/">NICD website</a> has PDF documents uploaded daily but it is a mission extracting the required data from here. Unfortunately, it isn't easy to read.


Raw data | Formatted data
---|---
PDF table | NoSQL database record
<img src="PDF%20Data.png" width=450/> | <img src="db_record.png" width=450/>

---------------------------------------
The code is split into 2 files __Extraction__ and __Transformation__. The __Load__ code exist in both scripts because there are pieces of data stored to the database from both stages.
