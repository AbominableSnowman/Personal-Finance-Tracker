# Personal-Finance-Tracker
Program that generates summary of expenses by taking in text files of daily expenses of each month. 
Text files must be written in a specific format so that the program interpret it. I found it most convenient to record my expenses on my iphone so I use the standard notes app and email the note to myself at the end of every month. Format is as follows:

Example text file:
{

Januaray 2018 Expenses

Bank account: $1234.56

Credit Card Debt: $1234.56

1/02/2018
  - $34.56 (groceries) - trip to Meijer
  
1/04/2018
  - $23.45 (cell) - bill
...

}

The file contains a header consisting of the amount of money in ones bank account and the current amount of money on credit card(s) at the beginning of the month. Regarding expenses, the date of the expense preceeds the expense entry. The expense entry starts with the amount spent and is followed by the category in parantheses and ends with an optional note that is marked by a dash. There are a set list of categories although this can easily be modified in the program.
