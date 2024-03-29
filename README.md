This project is about learning by doing. 
It started as an attempt to analyze historical fuel prices as reported by fuel stations, using an excel spreadsheet provided by the Argentinian government on their website. 
The goal, among many, is to derive understanding of trends and insights by using Data Science methods and tools and achieve proficiency.

[project in progress:]

### June 15, 2023

I spent a few hours fiddling around QGIS and was able to generate some basic graphs (below). They are not very informative by themselves and there is a lot of room for improvement, but having the hands-on experience with tangible results may come handy in the future.

Using only 2023 data, each cone location on the map represents the true geolocation of a fuel station; the height of the cone = price. We can clearly see that there are a lot of fuel stations in Buenos Aires that sent their fuel data to the Argentinian government, as it is to be expected.

![image](https://github.com/iamNeverwell/Argentina-Fuel-Prices-Project/assets/117388341/b204adba-d3a6-4af2-8a75-89fd01155c1c)
![image](https://github.com/iamNeverwell/Argentina-Fuel-Prices-Project/assets/117388341/7c8d8105-0ddb-45c2-8e98-c500415240c9)
![image](https://github.com/iamNeverwell/Argentina-Fuel-Prices-Project/assets/117388341/05b4b546-e5e6-43e8-8e2d-70bd39a8395c)

What's next? Not sure, I am taking suggestions.

### June 14, 2023

Updated file names to make it easier to identify them.

Uploaded Jupyter Notebook with ML code that makes a price predictions for 2024.

Just for giggles, it's saying it will be around 2000 ARS for 92 to 95 Octane Gasoline (I highly doubt it, but I guess we'll see in a few months...)

Now, I will read and learn about QGIS and see if I can generate a spike map with the data already generated in the .pdf file. It should look pretty nice.

### January 30, 2023

Created and uploaded a .pdf file from my PowerBI report to Github.

Remarks after analyzing the data:

- AUTOMOVIL CLUB ARGENTINO has the highest amount of price submissions from all the participating fuel stations (by more than half of the second place's amount;

- DEHEZA S.A.I.C.F.I.	has the highest CNG price submissions and is in second place for overall fuel type submissions (which follow very closely behind);

- Even though the data has very few submissions since 2001 (possibly typos or errors), things really started to take shape in 2016 with a total number of CNG submission of 52, from 1 or 2 (and more often none) submission prior. In 2017, hundreds of submissions were sent over the year for each fuel type, with a total of 1953, and roughly double that for every year since. Adoption, thus, really took place starting on 2017;

- Participating stations tend to be located in big cities, and along major highways. As it is to be expected, the further away from Buenos Aires, the less stations appear; and that number dwindles when going south. Ushuaia, the southernmost city in Argentina, has 3 participating stations -- one of each type of fuel;

- Echoing the fact that adoption started from 2017 onwards, the amount of price submissions had prices that did not seem valid when comparing to the rest of the dataset. Prices started to be more constant and valid from 2017 onwards.

- In 2021, the price of the high-grade gasoline, the most expensive fuel type across the years, was surpassed by the high-grade diesel and the trend continues until 2023.

### January 29, 2023 (afternoon)

Well, Azure did not work out for the free trial version. I had to go with the pay-as-you-go if I wanted to continue...nope.

Let's go back to Oracle and...it's still locked out.

Instead of watching youtube videos that might be more wasted time, I decided to use PowerBI. It's a tool I haven't used yet, so I thought it would be a perfect time to get to know how to use it and present the visualizations for this project in this fashion.


### January 29, 2023 (late night)

I attempted to upload the new, clean csv file into IBM Db2, but it errors out. I made sure I had the date format correct, and everything else seemed OK

Upon searching the internet for answers, I found a few people that had the same problem as me, but none of the answers were helpful. I tried fiddling around on my own, I gave up on the IBM Db2.

So I thought about uploading the file into my google drive and using the shareable link in the jupyter notebook.

Nope.

Then I tried Oracle MySQL, and it kept telling me the address was wrong until I got locked out. I waited the whole day, and I was still locked out.

So I gave Google a try. It made my head buzz and I felt like I was doing the same process of creating something and enabling APIs but I could not figure out a way of getting the link so I could put it on my jupyter notebook (like I had originally done with the direct link from the Argentinian Government website).

So I tried Microsoft Azure. It's deploying right now. Comparing to all other options above that I was able to create an account, Microsoft Azure seemed to be the most intuitive and easy to navigate...so far.

Tomorrow or whenever I have more free time, I will continue where I left off. If that fails, I will resort to looking and following some youtube tutorial...


### January 27, 2023

I was able to finally get a copy of MS Excel, and cleaned up the original csv file from the Argentinian government website. There were hundreds of entries with invalid date formats and future dates (like the year 2044).

I used Excel's formatting to divide the csv file into columns, and the date had the time all in one column. Since I wanted to have a column for only the dates, I selected that column and separated the data into two columns using the space used in between the date and the time as the separator. It worked out well, and I sucessfully deleted the new colum that had the time only.

After making sure there were no other invalid entries, I was ready to upload into the IBM Db2 and hop on Python to see the difference.

### December 29, 2022

This project is an attempt to analyze fuel prices using an excel spreadsheet provided by the Argentinian government, with the goal of deriving understanding of trends,
using ML to predict future trends, and see if there are any patterns, such as inflation effects.

Uploaded Jupyter notebook with substantial data wrangling, exploration and visualization.

more to come...

### December 9, 2022

Initial efforts started. Uploaded a few lines of code, using a file that contained a few rows from my own computer.







