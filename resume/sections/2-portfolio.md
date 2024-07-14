# Project Portfolio

## Professional

### RDS GEN AI Portal
*03.2024 - present*

Stack:
- Python
- FastApi
- OpenAI API
- Python Langchain Framework
- Microsoft Azure
- React JS

The online platform enables users to submit natural language requests to personalized Retrieval Augmented Generation (RAG) Large Language Model Agents. I am responsible for discovery, design and development for different backend microservices (RAG Agents) that are communicating with LLMs using Langchain Framework. 
Microservices support different use cases such as:
- answering questions basing on the vectorized knowledge base,
- answering questions based on the analysis of the documents uploaded by the user
- answering questions and providing source documents using different tools to access various internal systems/platforms

### Trial Strategy Platform
*03.2023 - 03.2024*

Stack:
- Python
- Connexion
- Flask
- REST/JSON
- AWS Lambda, SQS, SNS, Redshift
- Snowflake
- Airflow

The flexible platform comprises RESTful microservices deployed using AWS Lambda that share a common structure but have single responsibility. Various communication and orchestration mechanisms allow combining individual services into complex data pipelines. AWS SQS and SNS pub/sub and asynchronous processing. The straightforward application structure, along with published standards and developer tools, facilitates rapid system development and growth. Contract-first API specifications and use-case-driven documentation, supported by testing automation. Responsible for designing and implementing parts of the architecture and infrastructure.


### Strategy Workbench 
*11.2019 - 01.2024*

Stack:
- Python
- Flask
- FastAPI
- REST/JSON
- AWS
- Snowflake 
- RabbitMQ 

Strategy workbench is a micro service based application composed a set of independent modules (micro service) with REST API communicating with each other over HTTP. The application has been developed with Python and Flask or FastAPI, depending on the particular module. Application is using ML trained models to predict the plan and budgeting for medical trials based on user input and historical data. RabbitMQ and Celery based ETL pipelines are utilized to transform and load the data that is later used to constantly update and train models used for prediction. Recent need to scale up the solution resulted in the  currently ongoing  integration with Snowflake ETL/ELT processing.

### JiraToWSR
*06.2018 — 08.2018*

Stack:
- Python
- Django
- REST/JSON
- JavaScript

Integration between JIRA and internal project management software based on Django framework. Creation of a Django module responsible for retrieval, display and drag-and-drop addition of reports based on the last 20 Jira issues updated by the WSR user.


### API Developer Pack
*09.2017 – 10.2019*
Stack:
- Python
- Groovy
- Java

API Developer Pack (ADP) is a set of tools given to new Amadeus customers to boost their start with Amadeus Web Services & introduce them to good practices of session management and web services usage. 
It is a highly customized version of the SoapUI project with lots of Groovy & Java based modules which can be used to automate, visualize content and introduce interactivity to SoapUI test runs. Most of the features available in ADP are not available in vanilla SoapUI versions.

Along with the SoapUI files a set of the product documentation and WSDL files is available within each pack. 

Because the repository of the ADPs started growing rapidly - the whole ecosystem for maintenance and publication needed to be created from scratch. Due to technology stack available at the moment of creation (BitBucket GIT repository as a version control system and an Atlassian Confluence platform for documentation storage and publication) a Python application to deploy and release new versions of the pack was created. Application uses API of the Bitbucket GIT repository (to retrieve the release versions of the ADPs) & Confluence REST API to publish new version for the internal company community. 

### JIRA report creator
*05.2017 – 09.2017*

Stack:
- Python
- JIRA
- Confluence
- Microsoft Excel

A python based application used to create the monthly/weekly workload reports in different formats (txt, csv, xlsx, Confluence page).Application uses oAuth2 authorization, JIRA and Confluence REST/JSON API. From the JQL filter and optional parameters application creates a report which may contain values taken from various JIRA issue fields such as comments, workload, status, due date, priority etc. Based on the user choice the report can be stored in different file formats or exported to a Confluence Space page.

### Aggregation module of the billing system
*03.2013 – 12.2013*

Stack:
- T-SQL
- MS SQL Server 2008
- Enterprise Architect
- XML

One of the modules of the billing system built for customers request. The module role in the billing system was to group customer service fees into monthly groups and create base for invoice preparation. The module also served as message broker between other modules.

### Structures and Unit Test Generator for XML interfaces
*12.2013* 

Stack:
- Python
- T-SQL
- MS SQL Server 2008
- XML
  
Application responsible for automatic creation of the database structures, stored procedures and test data according to XML schema stored in database. Project created out of own initiative to improve the development of XML interfaces between various database modules and client applications.

### Financial accounting system
*10.2011 – 11.2013*

Stack:
- T-SQL
- MS SQL Server 2005/2008
- Enterprise Architect

Financial accounting system crafted directly for customer needs. Speedup of the exiting time of creating monthly closure report from 24 days to 34 hours. Participation from the very beginning until the final deployment phase. 

## Personal

### ShoppingPortal
*05.2019—11.2019*

Stack:
- Python
- Flask
- REST/JSON
- Google API

Shopping portal is a project made for fun in my free time. The purpose of its creation was to discover possibilities of a REST/JSON api design in Flask micro framework, the Google API as well as the web-scraping functionalities of requests-HTML Python library. The reason for the creation of this project was to have a tool which in an easy way will prepare a shopping list straight from the recipes available in different cooking portals on the web.I began to develop a web portal with a possibility to create a repository of the web scraped cooking recipes. User can simply copy & paste the URL of the recipe they like to the portal which will analyze the URL, retrieve the list of ingredients, time of preparation and the recipe itself. After successful analysis the recipe is added to the local list of the stored recipes. User can add as many recipes as they want to their shopping list. With a press of the button user can send the list of all ingredients from those recipes to their Google Keep where it will be stored as a separate cross-out shopping list.


### cityMap 
*10.2017*

Stack:
- Python
- geonames.org database

Project visualizing cities data on a vector graphics map image. Data is taken from the http://www.geonames.org/ service, then the Mercator projection is used to translate the GPS latitude to the (x, y) coordinates of the map image. As a result - the file containing the contour map in svg (scalable vector graphics) format is created for large scale format print.


### BTH-SIFT Content Based Image Retrieval System
*01.2013 – 01.2014*

Stack:
- C++
- QT
- OpenCV

Content Based Image Retrieval System designed to work with large image databases. Image processing based on the SIFT image descriptors improved with Binary Threshold Histograms. Project designed and used in image processing analysis as a part of Master Thesis. Project developed in C++ using Qt Framework and OpenCV image processing library.

### CSV to XLSX converter
*01.2014*

Stack:
- Python
- Microsoft Excel

Python-based tool developed to analyze large amounts of data produced by image processing analysis. The main goal of this project was to analyze and process numeric data given as CSV files and produce xlsx (excel spreadsheet) files containing dynamically created charts and statistic data in sleek and easy to read form. Developed as a part of Master Thesis.
