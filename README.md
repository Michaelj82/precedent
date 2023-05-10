# Precedent Project

Project which a user will give a query for a case that involves certain ideas, and it will return a case that set precedent for that.

## How it works
I connect to the GovInfo API to collect massive amounts of court case data. From this I extract text from the PDFs given and put into a CSV. Then I use cosine similarity to find a case that matches a user's query.

## Project Capacities
Due to the nature of my capacities, only takes Federal Court cases from Jan 1, 2022 to April 7, 2023.
Theoretically, if the dates and qualifications were changed, you could adjust the code to select decades worth of cases in specific court areas. 

CSV too large to upload to github so I saved it on Kaggle privately.

## Medium Link
https://medium.com/@mjj.yoyogi/nlp-for-court-case-precedent-identification-6bd3b1cb17d8
