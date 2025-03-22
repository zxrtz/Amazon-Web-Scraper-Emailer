# Amazon-Web-Scraper-Emailer
Using Python, I automated the collection of Amazon data to email potential discounts to users daily.

This specific program checks daily if the price of this t-shirt goes below $15. The daily prices are added to a csv file locally. 

If the price goes below $15 on a certain day, then the program will automatically email the end user and remind them that the item has gone on sale!

![image](https://github.com/user-attachments/assets/0af5751f-898b-49cd-a17b-1676f17b789a)

A code sample of a function that periodically checks the price every 24 hours, sending an email if the price drops:

![image](https://github.com/user-attachments/assets/6abe3736-73b1-478a-b4a3-be0c54df81c7)

Note: I used open source code for the function to email the user. The main code that checks and searches the webpage using HTML was made by me.
