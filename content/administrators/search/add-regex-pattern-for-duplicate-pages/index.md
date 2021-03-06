---
uid: add-regex-pattern-for-duplicate-pages
topic: add-regex-pattern-for-duplicate-pages
locale: en
title: Add Regex Pattern for Duplicate Pages
dnneditions: Platform,Evoq Content,Evoq Engage
dnnversion: 09.02.00
parent-topic: administrators-search-overview
related-topics: edit-regex-pattern-for-duplicate-pages,delete-regex-pattern-for-duplicate-pages
---

# Add Regex Pattern for Duplicate Pages

You can optimize the search index by marking generated pages as duplicates if they differ in dynamic content only. The crawler indexes only one from each set of pages that match a specified regex pattern.

## Prerequisites

*   **An administrator account for the site.** Administrators have full permissions to the specific site.

## Steps

1.  Go to **Persona Bar \> Settings \> Site Settings**.
    
    ![Persona Bar > Settings > Site Settings](/images/scr-pbar-host-Settings-E91.png)
    
2.  Go to the **Search** tab, and then the **Crawling** subtab.
    
    ![Search > Crawling](/images/scr-pbtabs-all-Settings-SiteSettings-Search-Crawling-E90.png)
    
3.  In **Duplicates**, click/tap \+ **Add Regex Pattern**.
    
      
    
    ![](/images/scr-SiteSettings-Search-Crawling-duplicates-add-regex-pattern-button-E90.png)
    
      
    
4.  Define the regex pattern for duplicates.
    
      
    
    ![](/images/scr-SiteSettings-Search-Crawling-duplicates-add-regex-pattern-E90.png)
    
      
    
    |**Field**|**Description**|
    |---|---|
    |<strong>Description</strong>|A name for the regex pattern entry. Typically, the name of the module that generates the dynamic content in pages that match the specified pattern.|
    |<strong>Regex Pattern</strong>|The regular expression that describes the various URLs and URL parameters of pages that are considered duplicates.|
    
5.  Save.