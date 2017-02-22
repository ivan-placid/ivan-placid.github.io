---
layout: page
title: "Python script for Novatour"
---

### Problem
I was surprised, that sometimes it is easier to hire a freelancer to scrape your site, than get data from another department. Novatour is one of the largest russian outdoor companies, so such inconsistency looks a bit weird at first glance. Anyway, their tech director get in touch with me, and after some discussion I wrote a little python script to scrape some data from _their own site_. That script build a report, about existence of video review for each product both in product description and comments. 
### Solution
I'm not sure if I can share source code here, but I'll mention technologies.
Since comments section was loaded with JS, I used [dryscrape](https://pypi.python.org/pypi/dryscrape/) instead of [requests](https://pypi.python.org/pypi/requests) to get page body, then [lxml](https://pypi.python.org/pypi/lxml) to extract specific elements (video name, author, etc.) and [PrettyTable](https://pypi.python.org/pypi/PrettyTable) to build an output.