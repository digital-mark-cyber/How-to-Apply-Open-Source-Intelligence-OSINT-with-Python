# How to Apply Open Source Intelligence OSINT with Python

Open-source intelligence (OSINT) has emerged as a vital resource for researchers, analysts, and cybersecurity specialists in the modern world. Gathering data accessible to the public is part of OSINT, which tracks, analyzes, and monitors digital footprints. Python is frequently used for these kinds of activities because of its extensive library and simplicity in automation. 

This article will discuss obtaining OSINT data using Python and offer code samples for various intelligence-gathering activities.


## OSINT: What is it?
Data that is available to the public for collecting and analyzing is referred to as "open-source intelligence".

• Social networking sites.

• Discussion boards.

• Search engines.

• News stories.


Analysts can combine data from several sources to provide insightful knowledge about a subject, group, or occurrence. This technique is frequently employed in threat detection, competitive intelligence, and cybersecurity investigations.

**Python OSINT Libraries**

The following libraries can be used to conduct OSINT in Python:

**1. Requests**: To make HTTP requests and collect data from websites.

**2. BeautifulSoup**: For XML and HTML document parsing.

**3. Selenium**: For handling dynamic web pages and web automation.

**4. Whois**: For analysis and domain search.

**5. Shodan**: To obtain information about Internet of Things products and services.

**6. Tweety**: To obtain Twitter's social media intelligence (SMI) data.

**7. SpiderFoot**: An extensive module system for automated OSINT.


   
## Basic Python OSINT Tasks
**1. OSINT-related web scraping**

Web scraping is one of the main techniques used in OSINT. We can scrape open forums, websites, and social media networks to obtain information about a subject or individual.

**2. Lookup Domains Making Use of Whois**

An essential component of OSINT is knowing who owns a domain, how it was registered, and its status. This task is made simpler using Python's whois package.

 ![001](https://github.com/user-attachments/assets/6954eb88-29f0-4926-ad2c-136d6a695096)

This script retrieves a domain's registration information, including name servers, creation and expiration dates, and registrar details. This information can be used to track domain ownership or investigate dubious websites.


**3. Compiling Data on Shodan**

Shodan is a device and service search engine for the internet. A Shodan API wrapper for Python enables the automation of IoT device queries.

The next step is to install the Shodan library. This is a crucial part of the process, as it will enable you to start using the Shodan API for your IoT device queries.

 ![002](https://github.com/user-attachments/assets/74f067aa-5148-46bd-aadf-4837591024f6)


Here's a simple script to query Shodan.

![003](https://github.com/user-attachments/assets/7e4ea437-5679-47f6-9281-ece981c7bcbf)

 
Shodan is a powerful tool that can be used to uncover a wealth of information. It can find open ports, servers that are susceptible, or webcams that are connected to a botnet.


**4. Twitter API-powered Social Media Intelligence with Tweepy**

Monitoring social media conversations can yield valuable data, particularly when examining online movements, trends, or individual users. We can gather tweets from Twitter with Tweepy.

Install the Tweepy library first:

![004](https://github.com/user-attachments/assets/4f84c2df-513f-4c28-a688-f6ee8df46561)


 
Here’s how you can use it to gather tweets on a specific topic.

 ![005](https://github.com/user-attachments/assets/bd10bf5a-b0a6-4c2b-8099-e470355e52a2)



This code facilitates the monitoring of conversations surrounding particular subjects or occasions by retrieving recent tweets about "cybersecurity."
Shodan is a powerful tool that can be used to uncover a wealth of information. It can find open ports, servers that are susceptible, or webcams that are connected to a botnet.



Python is perfect for OSINT jobs because of its extensive libraries and versatility. It offers an efficient way to obtain intelligence, from studying dark web activities to scraping websites and accessing APIs. By combining these resources with strong research techniques, you can significantly improve your capacity to investigate and handle security incidents, enhancing your confidence and security.




