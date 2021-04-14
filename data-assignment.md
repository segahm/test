## ABOUT YOU:

- a misfit, data generalist and jack-of-all-trades, poses high resourcefulness. 
- have strong bias towards action.
- have some practical experience. 
- sharp ability to listen
- able to see projects through from conception to implementation
- strong attention to detail.

## ASSIGNMENT REQUIREMENTS

* 50% focused on mundane Data Mining, 
* 30% Ability to Leverage tools, 
* 10% Ability to Learn New Things, 
* 10% Creativity

## TO APPLY:
#### 1) Compile a list of Media Reporters

Gather a list of Big Media Articles (WSJ, Wired, etc) and Author names (as many as possible) for those articles talking about "Google Cloud", such that you have a table looking as follows:

------------------------------------------------------------------------------------
|--- Link --- | --- Reporter Name --- | --- Publication --- | --- Artile Title --- |
------------------------------------------------------------------------------------
Save that in Google Sheets

#### 2) Identify these Reporters on LinkedIn

Use a tool like DataMiner.io and LinkedIn to identify LI profiles for all the Journalists/Reporters. Your table now looks like this:

-----------------------------------------------------------------------------------------------------------------------------------
|--- Link --- | --- Reporter Name --- | --- Publication --- | --- Artile Title --- | --- LI Profile --- | --- LI Current Title --- |
-----------------------------------------------------------------------------------------------------------------------------------
Save that info into the same Google Sheets

#### 3) Auto-populate github repo with content extracts

Create a new Github repo to host auto-generated extracts from each of the article pages
you should have an .md file for each article, structured as follows:
```
title: blah blah
author: blah blah
publication: blah blah
-------
first paragraph extract

```
do this in the automated fashion for all pages. Write-up one paragraph about your choice for how to implement this.

#### 4) RocketReach Enrichment / BigQuery Import
- Now sign-up on rocketreach.co
- Bulk upload 5 contacts from your big list: contact1, email1, email2, email3....
- You should get many email addresses per each contact
- Import the result into BigQuery
- Write a SQL Query to **UNFLATTEN** the results (one email address per column)
- Save this to a new sheet in your Google Spreadsheet

#### 5) Prepare the list of reporters for personalized emails
- for each author use the content extracted in question (3) to come up with 3 columns with personalized text
- save results in Google Spreadsheet

#### 6) Draft up a word document summarizing (1/2 page) your key decisions and results with all relevant links

#### 7) Email results to Segah
- reference your github username and a link to the repo from (3)
- link to the Google Spreadsheet (make sure it is shared with "anyone who has the link")
- Your Word Doc Summary as an attachment (including above SQL query, sample personalized text, # of reporters extracted, and other key factors you think are relevant)
