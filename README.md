# Adapted Git Scraper for the Under the Button Website

Adapted from [Jérémie Lumbroso's template](https://github.com/jlumbroso/basic-git-scraper-template). This git scraper scrapes the featured headline from the Under the Button website.

The changes can be summarized as follows: The request now targets the "Under the Button" website. The code identifies the primary headline by locating the first anchor tag with the class "article-link." The text of the headline is retrieved from the alt attribute of an image within this anchor tag. The data extraction logic is accordingly adjusted to accommodate this structure. Lastly, the output is directed to a new JSON file at data/under_the_button_headlines.json, ensuring that the scraped data is stored in a separate, organized file specific to the new website.
