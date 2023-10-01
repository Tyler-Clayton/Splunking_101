# Splunking_101 🤿
----splunk image----

## Introduction 🏁🚦
In this project, I explore basic utilizations of Splunk, a SIEM tool that can provide deep visibility by manipulating raw data. It is a highly useful tool for IT ops, network ops, security ops, and business systems. After initially configuring the app and data to be used, Splunk's Indexer will sift through that data. Using Splunk's query language, SPL, to define search parameters, the particular input of data can be analyzed and extracted. Then the data can be formatted into a highly digestible and effective presentation for the target audience.

## Important Items Used in This Project 🧑‍💻
- Sandbox environment provided by Splunk
- SPL (Splunk Processing Language)
- App on Splunk: splunk4rookies
- Data input/source: uploaded web log file
- Curiosity
  
## The App🧰
----app selection image----
There are a large number of apps that can be created and used on Splunk. They can be geared towards a specific purpose regarding operational visibility (web, security). The splunk4rookies app I used was already set up for use in this sandbox. However, it's important to note that these apps can be adjusted to include multiple knowledge objects and data inputs. 

## The Data🧩
----Data Source 1-4 and source type inputs----
The raw sample data used in this project was logs from a web server that splunk is also running on. After selecting the appropriate data (weblogs) from the file, I chose the proper source type, which is important for determining how Splunk formats the data during the indexing process. My source type was "Web" and then "access_combined" because I would be sifting through HTTP web server logs. It's important to note that the source type can be manually selected like in this project, or set to automatic. 

## Searching Raw Data with SPL
----

