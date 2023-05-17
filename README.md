# Project-1

# IMDB Top 250 Films
Examining trends of the Top-Rated Films
This project is drawing data primarily from the IMDB Top 250 Films Dataset, taken from Kaggle. Revenue and Budget data have been imported from the MovieLens Movies Dataset. Budget data has been adjusted for inflation in an attempt to show a clearer reflection of changes over time.

Basic data cleaning has been done to remove unneeded columns and remove obvious errors of movies whose budget exceeds the highest recorded budget of all time or duplicate entries in the Movies Dataset. That being said, the financial data provided by the dataset was not audited line-by-line and is taken as true for the sake of this analysis.

The goal of this analysis is to identify trends in genre, duration, budget and revenue over time and to answer the following questions:

- Is there a certain genre of film that is more popular within this dataset?
- What is the distribution of ratings?
- How have film runtimes changed over time?
- How has film revenue changed? Is it increasing/decreasing?
- Are film budgets growing or shrinking and what impact does that have on revenue and profit?
- What is the budget to revenue comparison for the Top 10 Films from the dataset?
- Do newer or older films garner more votes on the IMDB?

Overall, we can see that more money is being spent to make movies as time passes, they generate more revenue and more profit as a result.


Resources used for code:
Inflation adjustment:  https://towardsdatascience.com/the-easiest-way-to-adjust-your-data-for-inflation-in-python-365490c039
https://sparkbyexamples.com/pandas/pandas-convert-string-to-integer/#:~:text=Alternatively%2C%20you%20can%20convert%20all,'Fee'%20column%20to%20int.
https://stackoverflow.com/questions/25668828/how-to-create-colour-gradient-in-python
https://www.tutorialspoint.com/matplotlib/matplotlib_setting_ticks_and_tick_labels.htm
