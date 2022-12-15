
### Get this product for $5

<i>Packt is having its biggest sale of the year. Get this eBook or any other book, video, or course that you like just for $5 each</i>


<b><p align='center'>[Buy now](https://packt.link/9781839217074)</p></b>


<b><p align='center'>[Buy similar titles for just $5](https://subscription.packtpub.com/search)</p></b>


# DAXCookbook

<a href="https://www.packtpub.com/data/dax-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781839217074"><img src="https://www.packtpub.com/media/catalog/product/cache/e4d64343b1bc593f1c5348fe05efa4a6/9/7/9781839217074-original.png" alt="DAX Cookbook" height="256px" align="right"></a>

This is the code repository for [DAX Cookbook](https://www.packtpub.com/data/dax-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781839217074), published by Packt.

**Over 120 recipes to enhance your business with analytics, reporting, and business intelligence**

## What is this book about?
DAX is a library of functions and operators that can be combined to build formulas and expressions in Power BI Desktop, Azure Analysis Services, SQL Server Analysis Services, and Power Pivot in Excel. This book is a desk reference for people who want to leverage DAX's functionality and flexibility in BI and data analytics domains.

This book covers the following exciting features: 
* Understand how to create common calculations for dates, time, and duration
* Create key performance indicators (KPIs) and other business calculations
* Develop general DAX calculations that deal with text and numbers
* Discover new ideas and time-saving techniques for better calculations and models
* Perform advanced DAX calculations for solving statistical measures and other mathematical formulas
* Handle errors in DAX and learn how to debug DAX calculations
* Understand how to optimize your data models
If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1839217073) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders.

The code will look like the following:
```
R05_summarizedTable = SUMMARIZE(
 'R05_Table',                             // This is the table to summarize
 [Month],                                 // This is the column by which we want to group values
 [Weekday],                               // This is a second column by which we want to group values
 "# of Days",                             // Create a column called "# of Days"
 COUNTROWS('R05_Table'),                  // Return the count of rows for "# of Days"
 "First Date",                            // Create a second column called "First Date"
 MINX('R05_Table','R05_Table'[Value])     // Return first date weekday occurs in the month in "First Date"
 )
```

**Following is what you need for this book:**
Business users, BI developers, data analysts, and SQL users who are looking for solutions to the challenges faced while solving analytical operations using DAX techniques and patterns will find this book useful. Basic knowledge of the DAX language and Microsoft services is mandatory.

With the following software and hardware list you can run all code files present in the book (Chapter 1-13).

### Software and Hardware List

| Chapter  | Software required                                                                    | OS required                        |
| -------- | -------------------------------------------------------------------------------------| -----------------------------------|
| 1 - 13   |   Power BI Desktop                                                                   | Windows                            |
|   1      |   SQL Server Management Studio                                                       | Windows                            |

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://static.packt-cdn.com/downloads/9781839217074_ColorImages.pdf).


### Related products <Other books you may enjoy>
* Learn Power BI [[Packt]](https://www.packtpub.com/data/learn-power-bi?utm_source=github&utm_medium=repository&utm_campaign=9781838644482) [[Amazon]](https://www.amazon.com/Learn-Power-developing-interactive-intelligence-ebook/dp/B07X32RJDB)

* Hands-On Business Intelligence with DAX [[Packt]](https://www.packtpub.com/data/hands-on-business-intelligence-with-dax?utm_source=github&utm_medium=repository&utm_campaign=9781838824303) [[Amazon]](https://www.amazon.com/Hands-Business-Intelligence-DAX-intricacies/dp/1838824308)

## Get to Know the Author
**Greg Deckler**
is Vice President of the Microsoft Practice at Fusion Alliance and has been a professional technology systems consultant for over 25 years. Internationally recognized as an expert in Power BI, Greg Deckler is a Microsoft MVP for Data Platform and a superuser within the Power BI community with over 100,000 messages read, more than 11,000 replies, over 2,300 answers, and more than 75 entries in the Quick Measures Gallery. Greg founded the Columbus Azure ML and Power BI User Group (CAMLPUG) and presents at numerous conferences and events, including SQL Saturday, DogFood, and the Dynamic Communities User Group/Power Platform Summit.

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSdy7dATC6QmEL81FIUuymZ0Wy9vH1jHkvpY57OiMeKGqib_Ow/viewform) if you have any feedback or suggestions.
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781839217074">https://packt.link/free-ebook/9781839217074 </a> </p>