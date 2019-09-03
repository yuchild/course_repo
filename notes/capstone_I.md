# DSI Capstone I guide

Capstone projects let you showcase your data science skill and passion.  They 
result in a digital portfolio of public Github repositories that you can show 
potential employers.  We've had employers waive in-person coding requirements 
because an applicant's Github "looks great."  We hope that happens to you.

## Components of a Good Capstone
The Galvanize curriculum has been tailored over time to directly equip you with 
skills that are based on the demands of the market.  Therefore, you should look 
to showcase mastery of these skills through your project.  There are a few keys 
to success:

* **Well Written Code**  
There is a reason that we test for Python to get in the course, and work on it 
every day.  Code is the primary means for you to bring your ideas to life, and 
as such, beautifully written code with descriptive doc strings are incredibly 
important.  

* **A Helpful, Organized Github Repository**  
You should make it as easy as possible for people from diverse backgrounds 
to understand your capstone.  The single easiest way of doing so is having a
well written `README.md` file in your repo that introduces your project. 
Organizationally, put Python scripts in the `src` folder, Jupyter notebooks in 
a `notebooks` folder, data (probably just a subset) in a `data` folder, tests
for your Python scripts in a `tests` folder, and images in an `images` folder.

Here are some examples of excellent READMEs and Githubs from past capstones:
* [Traffic Accidents in Denver](https://github.com/johnherr/Traffic-Accidents-in-Denver)
* [Purifying Hearthstone Data](https://github.com/NJacobsohn/Hearthstone-Data-Analysis)
* [Does Work-Life Balance Matter?](https://github.com/tsandefer/dsi_capstone_1)
* [Services provided by Non-State actors](https://github.com/gagejane/Terrorism-NonViolent)

* **Evidence of Data Wrangling**
Data wrangling - the process of cleaning and unifying messy and complex data sets 
for easy access and analysis - consumes a large part of our jobs as data scientists.  
Really clean datasets are not the norm, so most likely whatever data you have to do
a capstone will be sufficiently messy to show your skill.  However, there are some
sites that host data that may have already been cleaned or featurized (Kaggle, 
for instance) that don't present much of a challenge.  Check with your instructors 
if you have questions about the cleanliness of your data.

## Capstone I specifics
Your first capstone project comes before you have learned anything about machine 
learning.  Many students wonder why we choose to have a capstone at this time, 
but it turns out that demonstrating mastery of the technological and statistical
foundations of the field are very powerful examples of your ability to quickly 
integrate onto DS teams.  As a reminder, your capstone projects should serve as 
demonstrations of a large and general skill set. 

### Skills to Feature
#### Web Scraping
Being able to create your own dataset is a powerful skill set, and it's unlikely 
you've mastered this skill on the one day of class that it was covered.  This is 
a great opportunity for you to work with ```BeautifulSoup```, ```Selenium```, and
```Scrapy``` in order for you to create wholly novel datasets.  Take careful 
note of all of the complications in acquiring data that you encounter in this 
process.  As you move to your later projects, your desire for larger datasets 
will only expand, and being able to satisfy this desire will require planning 
and effort. 

*BONUS* - Often the most interesting studies come from combining multiple sources 
of information.  If you can scrape multiple websites, your datasets will be even 
more impressive to hiring managers.

#### Data Pipelines
Information is not data.  Data is well formatted, regular, and able to be 
leveraged by statistical models.  As such, building a pipeline that will clean 
and transform the data into well formatted files is very important.  If you 
web-scraped into Mongo, consider a pipeline that will read in .json from Mongo 
and write tabular, cleaned data to PostgresQL.

#### Data Visualization
A good portion of this project should be devoted to data explorations and plotting. 
Make sure to follow best practices (axis labels with easily legible font!).  

#### Hypothesis Testing
This capstone is an excellent time to both deepen your understanding of, and 
demonstrate your ability to conduct a statistical study.  Remember, that many of 
the calculations surrounding test power and the number of statistics ought to be
conducted before a single byte of data is ever collected.

*Note* - many students feel that if they fail to reject their null hypothesis, 
their capstone is a failure.  As scientists, we should be dispassionate about 
the outcomes of our studies.  This means that if we only have results where we 
fail to reject the null, we're either being unscrupulous or unambitious. 

## Capstone I proposal  

You need to write-up a Capstone I proposal and submit it to your instructors for
review.  Please submit a **one-page PDF** file (no text files, markdowns, or 
Word Documents).

The proposal should:

1) State your question.  What is it that you are curious about?  What are you looking 
for in the data?

2) Demonstrate that you have looked at your data.  What are your columns?  Are they
numerical/catagorical?  How many Nan's are there?  Have you made a couple of plots? 
We only have a week for this capstone. It's very hard to do a good capstone when 
you've only had the real dataset for a couple of days.  This can make it challenging to 
work with a company.  Their timescale is different from the DSI.  "Fast" for them is a 
couple of weeks.  You needed the dataset yesterday.

3) State your MVP.  MVP is your Minimum Viable Product.  What's the minimum that you 
hope to accomplish?  Then, feel free to expand on MVP+, and MVP++.