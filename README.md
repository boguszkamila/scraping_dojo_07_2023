# Task 
Implement a program that automatically scrapes all quotes from [this website](http://quotes.toscrape.com/js-delayed/) and saves them to a single _.jsonl_  file upon execution.

**Note**: The program should scrape [this website](http://quotes.toscrape.com/js-delayed/) where the text appears with a random delay of a few seconds. Substituting this page will result in disqualification. 

## Rules
 1. The project is implemented in Python. Dependencies should be installed by executing the command `pip install -r requirements.txt`
 2. The scraping process should be started by the command python `run.py` without any parameters.
 3. All parameters - proxy, name of the output file, and input URL to be scraped - should be placed in the _.env_ file. This file should NOT be pushed into a repository. If the .env file is located inside a repository or any of the parameters listed below are hardcoded, the task will not be reviewed.
 4. Upon completion, the process should save the _output.jsonl_ file in the same base location as the _run.py_ file. 5. Each line of the _output.jsonl_ file should be in JSON format, with the following fields: `{ "text": "The world as we have created it is a process of our thinking. It cannot be changed without changing our thinking", "by": "Albert Einstein", "tags": ["change", "deep-thoughts", "thinking", "world"] }`

# Reference list:
- https://proxyway.com/guides/selenium-proxy-setup
- https://proxyway.com/guides/web-scraping-with-selenium
- https://stackoverflow.com/questions/76635996/scraping-issue-only-retrieving-quotes-from-one-page-despite-attempts-to-scrape
- https://lynn-kwong.medium.com/simple-web-scraping-using-requests-beautiful-soup-and-lxml-in-python-4f5903c67db2
- https://python.plainenglish.io/how-to-scrape-javascript-webpages-with-splash-requests-and-lxml-in-python-87b7bb4f0e8f
- https://oxylabs.io/resources/integrations/selenium
