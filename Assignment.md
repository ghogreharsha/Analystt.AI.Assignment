## Assignment: - 
### 1. A developer is assigned a task to scrape 1 lakh website pages from a directory site, while scrapping he is facing such hcaptcha, which are placed to stop people from scrapping As a project Coordinator suggest ways to solve this problem
Answer: Rotating IP Address is one of the ways to this kind of problem.with rotating IP we will have a changing IP address so that server doesn't detect that the requests are coming from the same machine and hence can’t detect same scrapping.  

### 2.Our client has around 10k linked-in people profiles, he wants to know the estimated income range of these profiles. Suggest ways on how to do this?
Answer: first of all group the same company names then paste the company name to glassdoor, in glassdoor it will show you all the profiles related to company from there you can get to know the income range of the specific profiles. for example. In 10k profiles, I have company name IBM then once I group IBM in by data file by selecting IBM, it will show Analyst,Manager etc now I will group analyst add income range from glassdoor. in the same way I will do for other profiles which are in same company. And the when I am done with IBM profiles, I will group other company and will do the same.This is the shortest and time saving way when we are dealing with large dataset.

### 3.We have a list of 1L company names, need to find linked-in company links of these profiles, how to go about this
Answer:  Use Derrick App extension. Once extension is added, it will open a google sheet, where we can paste company names and from extension tab we can select linked-in importer and email finder, where it will open sidebar with a search button. The search button will add company linked-in links in  a new column automatically upon clicking.

### 4.How to identify list of companies whose tech stack is built on Python. Give names of 5 companies if possible, by your suggested approach
Answer: By Using Builtwith Tool we can find whose tech stack is built on python,following are the companies built on python:
1.Fabric Life Limited
2.Python Software Foundation
3.Parewa Labs Pvt. Ltd
4.Pima Community College
5.Goway Group

### 5.Need to find an API, through which we can send linked-in messages to other linked-in users?
Answer:To find such an API, we can go through linkedin’s API Documentation. 
As per docs following API can used to send the messages:

`POST https://api.linkedin.com/v2/messages`

With  the following request by replacing the values as needed:

```
{
    "recipients": [
        "urn:li:person:123ABC",
        "urn:li:person:456DEF"
    ],
    "subject": "Group conversation title",
    "body": "Hello everyone! This is a message conversation to demo the Message API.",
    "messageType": "MEMBER_TO_MEMBER",
    "attachments": [
        "urn:li:digitalMediaAsset:123ABC"
    ]
}
```
