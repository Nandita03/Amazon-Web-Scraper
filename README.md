# Amazon-Web-Scraper

In today's fast-paced world, online shopping has become an integral part of our daily lives. Amazon, being the largest e-commerce platform, offers a plethora of products at competitive prices. However, with the constant fluctuation in prices, keeping track of products that interest you can be a daunting task. This is where web scraping comes into play. In this project, we will be using Python to scrape Amazon's website for product information such as product title and price. Furthermore, we will be implementing a feature that sends an email notification whenever the price of a particular product falls below a certain threshold. This project can prove to be useful for anyone who wants to keep track of prices for their desired products on Amazon, and receive timely notifications when a good deal comes along.

## WebPage we are Scraping data from

![image](https://user-images.githubusercontent.com/22257555/234348381-4eae0d1e-a147-4fe4-9740-f143379e6902.png)

## Importing libraries

![image](https://user-images.githubusercontent.com/22257555/234343817-3b0fb341-e03e-44fd-b627-cb68842cfff1.png)

## Connecting to the website

Connecting to the website and extracting Product Name and Price from the website. I used inspecting the network call using the "Inspect element" from the webpage in order to get id of Product Name and Price.

![image](https://user-images.githubusercontent.com/22257555/234344526-211d6981-ef12-4408-8e66-41de693a2bc6.png)

![image](https://user-images.githubusercontent.com/22257555/234345393-7ea781fc-0c8f-4b83-86fe-e4d2b996a565.png)

## Cleaning up the data

![image](https://user-images.githubusercontent.com/22257555/234346325-71d9864a-b24a-497e-9a9f-3774e07b8ee5.png)

## Creating a Timestamp

![image](https://user-images.githubusercontent.com/22257555/234346526-f63764db-75f5-4f3a-8efe-2ac56ec5a078.png)

## Creating CSV file

![image](https://user-images.githubusercontent.com/22257555/234346624-6f2d82f7-943c-4570-889d-a8fb1ff0a42a.png)

## Using Pandas Library to read the CSV File

![image](https://user-images.githubusercontent.com/22257555/234346847-d7be9aae-a423-4f08-b3a2-fdf6781290cd.png)

## Appending the data

![image](https://user-images.githubusercontent.com/22257555/234347019-21e2fbda-b701-42e6-8ffc-66da99c0d03f.png)

## Combining all the Code into one function

![image](https://user-images.githubusercontent.com/22257555/234347390-566d17dc-106c-4c75-aa97-6eaa97b9568e.png)

## Runs check_price after a set time and inputs data into the CSV

![image](https://user-images.githubusercontent.com/22257555/234347595-6dbb58f2-1a85-4924-8eda-01aa994972f3.png)

## Sending Email if the product is below certain value

![image](https://user-images.githubusercontent.com/22257555/234347914-f3ab1fb3-6a91-4000-bbf4-5e22cf277a55.png)



