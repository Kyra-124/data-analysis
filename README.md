# data-analysis

You’ll be the data analyst for ShoeFly.com, a fictional online shoe store.

//task 1
Load the data from shoefly.csv into the variable 'orders' and nspect the first 5 lines of the data.://

orders = pd.read_csv('shoefly.csv')

print(orders)
![head](https://github.com/Kyra-124/data-analysis/assets/98788777/892dcccd-fcd6-4a81-9cb5-06e3a5ae50f2) 

//task 2
Your marketing department wants to send out an email blast to everyone who ordered shoes!

Select all of the email addresses from the column email and save them to a variable called emails.://

emails = orders.email

//task 3
Frances Palmer claims that her order was wrong. What did Frances Palmer order?

Use logic to select that row of orders and save it to the variable frances_palmer.://

frances_palmer = orders[(orders.first_name == 'Frances') | (orders.last_name == 'Palmer')]

print(frances_palmer)

![wrong_order](https://github.com/Kyra-124/data-analysis/assets/98788777/909a682f-f0b9-492e-829d-00b09b50e0a4)


