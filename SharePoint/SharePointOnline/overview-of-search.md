---
title: "Overview of search in SharePoint Online"
ms.author: tlarsen
author: tklarsen
manager: arnek
ms.date: 6/20/2018
ms.audience: Admin
ms.topic: overview
ms.service: sharepoint-online
localization_priority: Normal
search.appverid:
- SPO160
- MET150
ms.assetid: 479cfd6b-900b-46aa-b497-c13787771d3f
description: "Learn how you can customize the search experience in SharePoint Online to help users find the information they're looking for."
---

# Overview of search in SharePoint Online


SharePoint Online has both a classic and a modern search experience. The classic search experience can be customized (the modern cannot be at this time) to make it easier for customers to find information. Both search experiences use the same search index and some settings can impact both experiences. (See [Differences between the classic and modern search experiences in SharePoint Online](https://docs.microsoft.com/en-us/sharepoint/differences-classic-modern-search)  for more information.)

Many of the available search features are listed in the [SharePoint Online search administration overview](https://docs.microsoft.com/en-us/sharepoint/manage-search-the-admin-center). 

## How search works
<a name="howsearchworks"> </a>

When SharePoint Online indexes lists and libraries of managed properties, it uses site columns to store detailed information about each document indexed.
  
1. Search **crawls** the lists and libraries and adds the site columns and values to the search index. 
    
2. In the **search index**, site columns are mapped to managed properties. 
    
3. When a user enters a **query** in a Search Box Web Part, the query is sent to the search index. 
    
4. The search engine finds **matching results** and sends them to a search results page where the results are displayed in Web Parts. 
    
![A schematic diagram showing the flow from lists/libraries to index, and from search page to index to search results page.](media/33dc2915-da17-4276-b8eb-79609d485d33.png)
  


  
## Make sure the content can be found
  
The content must be crawled and added to the search index for users to find what they're looking for when searching in SharePoint Online.
  
See [Make sure content can be found](https://docs.microsoft.com/en-us/sharepoint/make-sure-content-can-be-found) to learn how to:
- Make content searchable.
- Crawl and index content.
- Search for content across Office 365 and on-premises SharePoint Server at the same time. 

  
## Make the search results presentable
  
Presenting search results the right way makes content easier to find. See [Make the search results look great](https://docs.microsoft.com/en-us/sharepoint/make-search-results-look-great) for tips on how to manage the Search Center and use Web Parts to help each user narrow the scope of their search results. 
  
## Show relevant search results
  
All search results are not relevant to everyone all the time. See [Show the right search results](https://docs.microsoft.com/en-us/sharepoint/show-relevant-search-results) for ideas about how to produce targeted search results.
  
## Logs, limits, and reports
  
Usage logs and reports provide snapshots of query statistics and what users are searching for, while limits set parameters on search results. See Check logs, limits, and reports for tips on:
- How to create logs and reports.
- Find what content the crawler has added to the search index.
- How queries are performing.
- Create limits for search queries, such as number of entries in a custom search dictionary or size of documents which can be crawled.