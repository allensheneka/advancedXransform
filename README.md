# advancedXransform


## Introduction

This exercise requires working with a heavily modified version of the Superheroes dataset from Kaggle.

The dataset includes two csv's:

1. [superhero_info.csv](https://docs.google.com/spreadsheets/d/e/2PACX-1vS1ZstYLwFgwhZnqDsPjtnlHYhJp_cmW55J8JD5mym0seRsaem3px7QBtuFF0LiI7z1PLCkVKAkdO7J/pub?output=csv)

* Contains Name, Publisher, Demographic Info, and Body measurements.

2. [superhero_powers.csv](https://docs.google.com/spreadsheets/d/e/2PACX-1vSzdWOBaXOoz52vPmCFV5idNlDBohLY1Lsbc1IfZIZQ7cV_aNB2wYBfhF49uE1TaO1B5MQCGWiNrFfd/pub?output=csv)

* Contains Hero name and list of powers


## Problem Description

There are two major tasks:

1. Clean the files and combine them into one final DataFrame.

>This dataframe should have the following columns:

* Hero (Just the name of the Hero)
* Publisher
* Gender
* Eye color
* Race
* Hair color
* Height (numeric)
* Skin color
* Alignment
* Weight (numeric)
* Plus, one-hot-encoded columns for every power that appears in the dataset. E.g.:
* Agility
* Flight
* Superspeed, etc.

**Hint:** There is a space in "100 kg" or "52.5 cm"

2. Use your combined DataFrame to answer the following questions.

>Compare the average weight of super powers who have Super Speed to those who do not.
>What is the average height of heroes for each publisher?
 
