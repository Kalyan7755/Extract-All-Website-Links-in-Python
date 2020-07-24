# Extract-All-Website-Links-in-Python
It is a webcrawler which recursively crawls ALL pages in particular domain to list all the URLs of the website.

Run this commands to install requirments:
--> pip install -r requirements.txt
--> pip install requests bs4 colorama (We are going to use colorama just for using different colors when printing, to distinguish between internal and external links).

To Run this .py file to get all the links of a website:
--> python All_links_extractor.py https://www.rirm.in/ -m 2

You will get Output like This:
OUTPUT:
[*] Internal link: https://www.rirm.in/
[*] Internal link: https://www.rirm.in/about/
[*] Internal link: https://www.rirm.in/contact/
[*] Internal link: https://www.rirm.in/we-are-hiring/
[*] Internal link: https://www.rirm.in/we-are-hiring/associate-analyst/
[*] Internal link: https://www.rirm.in/we-are-hiring/content-developer/
[*] Internal link: https://www.rirm.in/we-are-hiring/graphic-designer/
[*] Internal link: https://www.rirm.in/perspectives/
[*] Internal link: https://www.rirm.in/five-questions-to-ask-before-hiring-an-seo-company/
[*] Internal link: https://www.rirm.in/category/hiring-seo/
[*] Internal link: https://www.rirm.in/the-google-medic-update-what-you-need-to-know/
[*] Internal link: https://www.rirm.in/category/google-medic/
[*] Internal link: https://www.rirm.in/just-how-fresh-is-your-structured-data/
[*] Internal link: https://www.rirm.in/category/structured-data/
[*] Internal link: https://www.rirm.in
[*] Internal link: https://www.rirm.in/we-are-hiring/associate-analyst
[!] External link: https://cutshort.io/company/rankitright-media
[+] Total Internal links: 16
[+] Total External links: 1
[+] Total URLs: 17

