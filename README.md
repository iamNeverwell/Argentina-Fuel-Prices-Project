### December 9, 2022

Initial efforts started. Uploaded a few lines of code, using a file that contained a few rows from my own computer.

### December 29, 2022

This project is an attempt to analyze fuel prices using an excel spreadsheet provided by the Argentinian government, with the goal of deriving understanding of trends,
using ML to predict future trends, and see if there are any patterns, such as inflation effects.

Uploaded Jupyter notebook with substantial data wrangling, exploration and visualization.

more to come...

### January 27, 2023

I was able to finally get a copy of MS Excel, and cleaned up the original csv file from the Argentinian government website. There were hundreds of entries with invalid date formats and future dates (like the year 2044).

I used Excel's formatting to divide the csv file into columns, and the date had the time all in one column. Since I wanted to have a column for only the dates, I selected that column and separated the data into two columns using the space used in between the date and the time as the separator. It worked out well, and I sucessfully deleted the new colum that had the time only.

After making sure there were no other invalid entries, I was ready to upload into the IBM Db2 and hop on Python to see the difference.

### January 29, 2023 (late night)

I attempted to upload the new, clean csv file into IBM Db2, but it errors out. I made sure I had the date format correct, and everything else seemed OK

Upon searching the internet for answers, I found a few people that had the same problem as me, but none of the answers were helpful. I tried fiddling around on my own, I gave up on the IBM Db2.

So I thought about uploading the file into my google drive and using the shareable link in the jupyter notebook.

Nope.

Then I tried Oracle MySQL, and it kept telling me the address was wrong until I got locked out. I waited the whole day, and I was still locked out.

So I gave Google a try. It made my head buzz and I felt like I was doing the same process of creating something and enabling APIs but I could not figure out a way of getting the link so I could put it on my jupyter notebook (like I had originally done with the direct link from the Argentinian Government website).

So I tried Microsoft Azure. It's deploying right now. Comparing to all other options above that I was able to create an account, Microsoft Azure seemed to be the most intuitive and easy to navigate...so far.

Tomorrow or whenever I have more free time, I will continue where I left off. If that fails, I will resort to looking and following some youtube tutorial...

### January 29, 2023 (afternoon)

Well, Azure did not work out for the free trial version. I had to go with the pay-as-you-go if I wanted to continue...nope.

Let's go back to Oracle and...it's still locked out.

Instead of watching youtube videos that might be more wasted time, I decided to use PowerBI. It's a tool I haven't used yet, so I thought it would be a perfect time to get to know how to use it and present the visualizations for this project in this fashion.


