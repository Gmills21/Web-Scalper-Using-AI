AI Web Scraper Agent
This is a personal project I built to play around with LangGraph and the Groq API.

The idea was to make a script that could do more than just scrape a webpage. I wanted to see if I could chain a bunch of AI calls together to automatically get a deep analysis of any article.

It uses BeautifulSoup to grab the content from a URL, and then LangGraph runs that text through a whole pipeline of analysis steps.

What it does:
Scrapes the page: Grabs and cleans the text.

Classification: Tries to figure out what the content is about.

Summarization: Writes a quick 2-3 sentence summary.

Tag Extraction: Pulls 5-7 of the most relevant tags.

Related Topics: Suggests 3-5 related topics.

Sentiment Analysis: Guesses the emotional tone and gives a score.

Key Phrase Extraction: Finds important quotes and their context.

Readability Analysis: Scores the complexity and guesses the target audience.

Fact Checking: Tries to spot 3-5 claims that might need verification.

Content Structure Analysis: Looks at how the article is organized.
