# data-analysis

You’ll be the data analyst for ShoeFly.com, a fictional online shoe store.

//task 1
Load the data from shoefly.csv into the variable 'orders' and nspect the first 5 lines of the data.://

orders = pd.read_csv('shoefly.csv')

print(orders)
![head](https://github.com/Kyra-124/data-analysis/assets/98788777/892dcccd-fcd6-4a81-9cb5-06e3a5ae50f2) 

//task 2
Your marketing department wants to send out an email blast to everyone who ordered shoes!

Select all of the email addresses from the column email and save them to a variable called emails.//

emails = orders.email

