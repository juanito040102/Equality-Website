# Project Title: Equality Across the World  - Juan Zumarán

### Programming for Cultural Heritage - Pratt Institute
Project to visualize the different equality index values throughout the world

## Description

I Gathered data from Equaldex.com, a public API with data for at least 197 countries on LGBT data. They include their own equality index, that ranks the countries from 1 to 100 (higher is better), and there is data for a “Legal Index” (from 0 to 90), regarding legal initiatives and the penalization of being LGBTQ+ in those countries (higher Legal index is better). Lastly, there is data on the “Public Opinion” index, where registered users can upvote or downvote a country based on data and submit comments that require approval. This last one is the most interesting to me since it contemplates people's opinion and not laws or policies which may not translate into the LGBTQ+ acceptance in the countries.

The goal of this project is to analyze the data from a world perspective, a continent perspective, and an in-depth analysis into the “best” countries to be LGBTQ+ in or travel to, and the “worst” ones. Does the Equality Index vary from country to country visually? How do different continents compare? What can we say about the lowest ranking countries? 

## Rationale

There is a rising movement of anti-woke / anti-LGBTQ+ that is unprecedented for the last decade, and new political groups are getting stronger everyday advocating against gay marriage, gay adoption, gender affirming care, gender re-assingment and other LGBTQ basic human rights. 

This project aims to show the differences in countries and also the variance in regions like continents. With the data of public opinion, there is an aim to show which countries are not safe for LGBTQ+ tourists and residents and which are the reasons why.

## Workflow
The first step was to gather the data, examine it, and prepare it for the visuals (this includes updating the countries with ISO codes, which are necessary to map with plotly). After this, was the construction of the maps. I created a world map that showed the PO index thoughout the world, and then a specific continent map for each region. After this, I wanted to see the distribution of the values so a box plot was created to illustrate the distribution of the data.

After the maps were created, I exported the World map to HTML, to integrate it to github pages and not lose the functions that plotly offers, labels, zoom functions, and overall better user experience. 

The last step was building the github repository that contained the files, including the csv, the notebook, and the images. 
I forked the theme 'cayman' to my github repo to create a static website that flowed thorugh a narrative that explained to the user what they were seeing. 

## Further Uses

This map could be used as an annex of Equaldex, since they already have a lot of maps that illustrate the information, but this website could be used to understand why some countries have lower values and some have higher ones. 

This repository could be used to further expand the LGBTQ+ research on policy and laws, but I think the main purpose is to understand what the public says, so this repository could become a collaborative effort to dive deeper into the different cultures of the different countries in order to comprehend the context of that region

## List of Files

Csv Dataset: equaldex_equality_index.csv
Python Notebook: Draft of Final Project.ipynb
