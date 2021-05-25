# LHS712-TermProj-Sentiment
Term Project for LHS712 on intercommunity entity-level sentiment analysis

## Overview

This project was intended as a draft for a tool that could flexibly be
pointed at subreddits to gather post and comment data, run entity 
recognition, and report entity-level sentiment per subreddit.

## Directory Layout

- `data` contains a backup of the data harvested from reddit with its
returned sentiment-analysis response from the GoogleCloud NLP API
- `docs` contains backups of our final paper and presentation slides
- `keys` is where credentials for Reddit API access and Google Cloud 
NLP API access need to go
- Main code is split between the two Jupyter notebooks
- Because the project was originally developed on Google Collab, there 
are additional imports not-necessary and import paths need adapting

## ToDo's

- If ever revisiting project, assess actual performance quality of Google Cloud
API's performance, will require manual annotations
- Consider training custom NERS system w/ SpaCy to eliminate paid cloud dependency

