# Automated Generation of Edgar Allen Poe-Style Text Using GPT-2

This notebook contains code for fine-tuning the smallest version of the GPT-2 pre-trained language model using text written by Edgar Allen Poe. Three model training notebooks are included in this repository:

- gpt2_poem_line.ipynb - trains GPT-2 using line-wise text sequences taken from Edgar Allen Poe's poetry
- gpt2_poem_stanza.ipynb - trains GPT-2 using stanza-wise text sequences taken from Edgar Allen Poe's poetry
- gpt2_story.ipynb - trains GPT-2 using sentence-wise text sequences taken from Edgar Allen Poe's short stories

A dataset containing text for each of Edgar Allen Poe's short stories can be found here:  [https://www.kaggle.com/leangab/poe-short-stories-corpuscsv](https://www.kaggle.com/leangab/poe-short-stories-corpuscsv)

Poems written by Edgar Allen Poe were scraped from *[The Complete Poetical Works of Edgar Allan Poe](https://www.gutenberg.org/ebooks/10031)*, a collection of Poe's poetry that is available in the public domain on Project Gutenburg. Poetry data was scraped using BeautifulSoup, and the code used to obtain poetry data is found in the notebook entitled poe_poem_scraper.ipynb.

Also, please take a look at the Medium article I wrote based around the stanza-wise model contained in this repository:  [Generating an Edgar Allen Poe-Styled Poem Using GPT-2](https://scottmduda.medium.com/generating-an-edgar-allen-poe-styled-poem-using-gpt-2-289801ded82c)