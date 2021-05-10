# Scraping_CNE
#**Data extraction from the Venezuelan CNE (National Electoral Center) web platform**.

The idea of developing this code began out of curiosity, when I saw a billing system of an electronics store, I could see that at the time of generating the invoice the customer's ID was entered and with this information the name and address of the buyer was extracted, this data was used to generate the invoice.
I always wanted to replicate this functionality, so on different occasions I investigated how to do it, which I will explain below.

The CNE makes all these data available to the public on its web page, for this you only need to enter the web platform and enter the ID number. Looking at the code of the page, I could see that a GET request is made to a PHP file, it returns an HTML structure to be displayed on the web, at this point just examine the HTML tags and performing Web Scraping extracts the data supplied or required.

I chose python, for the ease of use both in its syntax and its libraries, also for the possibility of using in Google Colab and have a faster execution than on my personal computer.
