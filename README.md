# Google-ads-Database
Google is a multinational technology company offering online advertising services through the Google ads platform. As a data analyst, you have been tasked with developing a comprehensive Relational Database Management System (RDBMS) to support GoogleAds operations. The goal is to manage advertisers, campaigns, ads, keywords and performance metrics 

## Objectives 
* Identifying the main entities in the database system.
* Clearly defining the main attributes and constraints that support the business needs.
* Designing an entity relationship diagram that support the business needs based on the database entities , relationships and participation constraints. 



## Main entities in the database 
Entities are tables or real world objects that are meant to store information in a database. They are the foundational components of an Entity Relationship Diagram (ERD).

# Advertiser
This is the table that stores the advertisers information . The attributes are as follows:
AdvertiserID **INT** <BR>
Advertisername VARCHAR <BR>
Contactperson VARCHAR <BR>
ContactEmail VARCHAR <BR>


# Campaign
This is the table that stores information from the campaigns. The attributes and data types are as follows: 

CampaignID<br>
AdvertiserID<br>
CampaignName<br>
StartDate<br>
Budget<br>

# Ad

AdID <br>
CampaignID <br>
Adtitle <br>
TargetURL <br>
Impresions <br>

## keyword
KeywordID <BR>
AdID <BR>
Keywordtext <br>
Bidamount<br>
QualityScore <br> 

