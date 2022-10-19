# Coding Challenge

The main goal of this challenge is to get a sense of your coding style and choices.

The code challenge does not involve any exotic or bleeding-edge technologies, tools, etc. and that’s the point: We’d like to focus on your code style and not get distracted.

On that note, we’re also not looking for "rights and wrongs", and there are no "trick parts" in this challenge. We would merely like to get a more profound impression of how you write code.

That also allows us to have a more fruitful and constructive discussion at the technical interview. We’re not fans of white-boarding at interviews, so we’d much rather have some concrete code to talk about. We think that makes the interview much more enjoyable and productive.


# Your challenge/task

Import the data set and associate as much data as possible

There are two small datasets in this directory, please design the tables and import them to the database separately.

We assume that the two datasets are twitter and linkedin users, and we want to find the connection between them.

## Task Specifications

*  Statements for creating tables
*  Scripts for importing datasets
*  Script to find the connection
   -  Let's assume that people with the same name are the same person, and people with the same email are also the same person.
   -  When we associate the two datasets, we can find the company name of a person by his twitter account.
   -  You can create a new table to store this relationship, twitter account -> linkedin name
   -  Note that some people may have a middle name, we assume that if the first and last names match, it is the same person.

## Notes
* Please consider indexes when designing tables, as this is a small dataset, and in the real world, we may be running on files with millions of rows
* Please use `php` or `python` to write the script
* Please use`mysql` as database
* Don't worry if you can't find an associated person, since this is a small test dataset and we are only focusing on the code side.