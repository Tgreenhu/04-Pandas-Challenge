# 04-Pandas-Challenge

In the event that my Jupyter Notebook file does not load correctly on GitHub, please follow the link below for better readability:
https://nbviewer.jupyter.org/github/Tgreenhu/04-Pandas-Challenge/blob/master/HeroesOfPymoli/HeroesOfPymoli_Taylor.ipynb

In this assignment, we are given a CSV file of the recent history of purchases from the Heroes of Pymoli video game.  Using Pandas, we were tasked to analyze and generate a report from the following purchase data:

    - Purchase ID
    - Screen Name
    - Age
    - Gender
    - Item ID
    - Item Name
    - Item Price

Using the CSV given above, I created DataFrames that:

    - Found the total number of players across the history of the given data
    - Found the number of unique items, average price, number of total purchases, and total revenue
    - Separate the data based off of gender to find the total number & percentage of each, as well as purchase counts and average purchase per item and per person.
    - Separated the data based off of age groups to find the total number & percentage of each, as well as purchase counts and average purchase per item and per person.
    - Found both the most popular & most profitable items purchased by purchase count, average purchase price, and total value.

From this data, 3 trends I found were:

    - This game is most popular with Males, accounting for 392 more players than the other genders combined and over $1500 more dollars spent.
    - The majority of purchases take place with users between the ages of high school & college students. This would make sense as these aged students typically have jobs while also have the free time to play video games as well.
    - While the average purchase per person for all genders lies around 3−3.30, the 3 most popular items purchased are all over $1 more than the average. This must mean these items are vital or special to the game play.
