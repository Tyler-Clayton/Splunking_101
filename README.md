# Splunking_101 🤿
![Splunk Logo](https://i.imgur.com/pnoitET.jpg)

## Introduction 🏁🚦
In this project, I explore basic utilizations of Splunk, a SIEM tool that can provide deep visibility by manipulating raw data. It is a highly useful tool for IT ops, network ops, security ops, and business systems. After initially configuring the app and data to be used, Splunk's Indexer will sift through that data. Using Splunk's query language, SPL, to define search parameters, the particular input of data can be analyzed and extracted. Then the data can be formatted into a highly digestible and effective presentation for the target audience.

## Important Items Used in This Project 🧑‍💻
- Sandbox environment provided by Splunk
- SPL (Splunk Processing Language)
- App on Splunk: splunk4rookies
- Data input/source: uploaded web log file
- Curiosity
  
## The App🧰
![App Selection](https://i.imgur.com/dSjEmDd.jpg)
There are a large number of apps that can be created and used on Splunk. They can be geared towards a specific purpose regarding operational visibility (web, security). The splunk4rookies app I used was already set up for use in this sandbox. However, it's important to note that these apps can be adjusted to include multiple knowledge objects and data inputs. 

## The Data🧩
![Data Source 1](https://i.imgur.com/TOgplDM.jpg)
![Data Source 2](https://i.imgur.com/KlLVrke.jpg)
![Data Source 3](https://i.imgur.com/KiI6zzO.jpg)
![Sourcetype Input](https://i.imgur.com/ao1WRGB.jpg)
![Sourcetype input 2](https://i.imgur.com/GKO9cx2.jpg)
![sourcetype input review](https://i.imgur.com/eHegV3k.jpg)

The raw sample data used in this project consisted of logs from a web server that Splunk is also running on. After selecting the appropriate data (weblogs) from the file, I chose the proper source type, which is important for determining how Splunk formats the data during the indexing process. My source type was "Web" and then "access_combined" because I would be sifting through HTTP web server logs. It's important to note that the source type can be manually selected like in this project, or set to automatic. 

## Searching for Events with SPL🔍
![Search1](https://i.imgur.com/pqjY1O0.jpg)
![Search2](https://i.imgur.com/DzmsnYk.jpg)
![Search 3](https://i.imgur.com/X4QOcAD.jpg)
![Extracting fields](https://i.imgur.com/3zkrLdN.jpg)
There are multiple parameters to use when searching, and certain items in the presented data can be extracted. After a particular item is extracted a specific log, such as the client browser or OS being used on the other end, it can be added to the fields section during the search. This allows you to easily select that information going forward. The time period of that data being reviewed can also be changed, which is helpful if you need to locate a specific issue, or if you need to monitor/measure results over time. 

## The Dashboard📈
![Data Format Options](https://i.imgur.com/iSEcckb.jpg)
![Bar chart1](https://i.imgur.com/XnIXrF5.jpg)
![Last Search Map Visual](https://i.imgur.com/u4f8NAV.jpg)
After I searched and located data, I could format it into a pattern, statistics or an easy to read visual such as a chart or graph. I could then take those visuals and create a dashboard. These dashboards provide an effective way to convey relevant information. With the customization and operability of the Splunk platform, the uses are infinite across multiple facets of information technology, information security, and business development/administration. 
![Dash1](https://i.imgur.com/YPLqNsj.jpg)
![Dash2](https://i.imgur.com/bwcyu81.jpg)
![Dash3](https://i.imgur.com/3naesgy.jpg)

