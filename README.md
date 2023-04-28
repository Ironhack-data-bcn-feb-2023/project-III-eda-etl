![portada](https://github.com/Ironhack-Data-Madrid-Enero-2021/W3-pipelines-project/blob/master/portadaw3.jpg)

# W3-pipelines-project

## Overview

The purpose of this project is to combine the data cleansing techniques used in project number 1, together with extraction techniques (API, WebScrapping), visualization and SQL, as well as modularization and encapsulation in a topic or field that you are passionate about. You will have to find a data source, take it to a database, clean it and analyze it according to three hypotheses that you set at the beginning.

## What is a pipeline?
A data pipeline is a series of data processes in which the output of each one is the input of the next, forming a chain.

## TO DO's 

- Decide on a topic you want to work with.
- Find a data source and collect the data (600+ data is enough).
	You could find a dataset in kaggle and enrich it with external data (API or web scrapping) or create it yourself.
	- Get data from an API.
	Note: The API you use may require authentication via token or oAuth.
	- Do web scraping with python `beautifulsoup` module.
	merging two datasets is difficult, so we recommend you to use several tables using SQL.
- Decide on 3 hypotheses
- Explore the data and write down what you have found
    - you can use: `df.describe()`, `df["column"]`, etc.
- Export it in a CSV data file and put it into mySQL.
	- you can have your data divided in different tables by categories, or you can have a single table.
- Access the tables or table from python using SQL.
- Show data that validates the conclusions based on your hypotheses in a file named `analysis.ipynb` 
	- Simply sumarize the data and do some basic statistics (mean, max, min, std, etc.).
	- Do domain based statistics or data aggregations using `groupby()`.
	- Go nuts with the investigation.
- Visualize your results (several graphs of different types; maybe also a map?) in a file named `visualization.ipynb`
	- LOTS AND LOTS of plots, of all types and colors.	
- Encapsulate your code into functions and save them into `.py` files: make sure you have docstrings
- Import those functions into your jupyter notebooks and call them (you will substitute your code with your own functions)
- Work on titles and comments to have a well presented and cohesive story in your notebook
- Build a compelling story-telling around your findings. Think of your stakeholders and convince them with your conclusions! (Some slides with few text and pretty plots are normally useful).

## Suggested ways to get started

- We recommend that on the first day of the project kick-off, you find a theme to base your project on, you can start by basing it on what areas you like, here are some examples:

	- Gastronomy
	- Health
	- Economy
	- Sports
	- Marketing
	- Aviation
	- Fashion
	- Manufacturing
	- War

Then, within each area there are different topics, for example:

Within gastronomy we can find topics such as the evolution of gastronomy in Europe and new trends and how it influences the business. Or the best gastronomies in the world and what to consider before setting up a restaurant, etc…

- Find the data source, establish whether you want to use an API, do the process by web scraping or use several kaggle tables.
- After you have the data, examine them and try to understand them and adjust them to your hypotheses or change your hypotheses in case new ones have arisen from examining the data.
- Break the project down into different steps - use the topics covered in the lessons to form a check list, add anything else you can think of that may be wrong with your data set, and then work through the check list.
- Use the tools in your tool kit - your knowledge of Python, data structures, Pandas, and data wrangling. Work through the lessons in class & ask questions when you need to! Think about adding relevant code to your project each night, instead of, you know... procrastinating.
- Commit early, commit often, don’t be afraid of doing something incorrectly because you can always roll back to a previous version.
- Consult documentation and resources provided to better understand the tools you are using and how to accomplish what you want.

## How to deliver the project

1. Create a new repo with the name `data-extraction-viz` on your github account (or another name)
	- Create a README.md file on repo root with project documentation. Make sure to include as much useful information as possible. Someone that finds the README.md should be able to fully get a gist of the project without browsing your files.
	- Include a `.gitignore`
	- At least 1 jupyter notebook is required
	- Create a folder with the name data and put there the SQL file with the tables.
	- Including your functions in a `src.py` is recommended but not required.
2. Open an Issue on this repo and paste your own repo's link.

## Links & Resources

- <https://www.kaggle.com/teajay/global-shark-attacks>
- <https://numpy.org/doc/1.18/>
- <https://pandas.pydata.org/>
- https://docs.python.org/3/library/functions.html
- https://plotly.com/python/
- https://matplotlib.org/
- https://seaborn.pydata.org/
- https://pandas.pydata.org/docs/
- https://pandas.pydata.org/docs/
