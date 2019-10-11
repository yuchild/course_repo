# DSI Capstone I guide

Capstone projects showcase your data science skill and passion.  They 
result in a digital portfolio of public Github repositories that you can talk
about with potential employers.  We've had employers waive in-person coding 
requirements because an applicant's Github "looks great."  We hope that happens
to you.

## Components of a Good Capstone
The Galvanize curriculum has been tailored over time to equip you with skills 
requested in the job market.  Look to showcase these skills: 

* **Well Written Code**  
There's a reason that we test for Python in our entrance exam and work on it 
every day.  Code is how you to bring ideas to life.  Code is what you share with
others to get a job done.  Well written code with relevant documentation is your
ticket to working with others.

* **A Helpful, Organized Github Repository**  
Make it as easy as possible for those from diverse backgrounds to understand your 
capstone.  Have a well written `README.md` that introduces your project at a high 
level for all to understand, but also provides depth for those looking for it. 
Organizationally, put Python scripts in the `src` folder, Jupyter notebooks in 
a `notebooks` folder, data (probably just a subset) in a `data` folder, tests
for your Python scripts in a `tests` folder, and images in an `images` folder.

Here are some examples of excellent READMEs and Githubs from past first capstones:
* [Traffic Accidents in Denver](https://github.com/johnherr/Traffic-Accidents-in-Denver)
* [Purifying Hearthstone Data](https://github.com/NJacobsohn/Hearthstone-Data-Analysis)
* [Does Work-Life Balance Matter?](https://github.com/tsandefer/dsi_capstone_1)
* [Services provided by Non-State actors](https://github.com/gagejane/Terrorism-NonViolent)

* **Evidence of Data Wrangling**
Data wrangling - the process of cleaning and unifying messy and complex data sets 
for easy access and analysis - consumes a large part of our jobs as data scientists. 
Clean datasets aren't the norm, so most likely whatever data you have will be 
sufficiently messy to show your skill.  However, there are some sites that host 
data that may have already been cleaned or featurized (Kaggle, for instance) that 
don't present much of a challenge.  Check with your instructors if you have questions 
about the cleanliness of your data.

## Capstone I specifics
Your first capstone project comes before you have learned anything about machine 
learning.  Many students wonder why we choose to have a capstone at this time, 
but it turns out that demonstrating mastery of the technological and statistical
foundations of the field are very powerful examples of your ability to quickly 
integrate onto DS teams.  As a reminder, your capstone projects should serve as 
demonstrations of a large and general skill set. 

### Skills to Feature
#### Web Scraping
Being able to create your own dataset is a powerful skill that requires practice.
This is a great opportunity for you to work with ```BeautifulSoup```, 
```Selenium```, and ```Scrapy``` in order to create a novel dataset.
Note the complications acquiring data that you experience in this process. 
Lessons learned will help you with making and cleaning datasets in the future. 

*BONUS* - Often the most interesting studies come from combining multiple sources 
of information.  Make an entirely new dataset that helps you answer a specific
problem.   

#### Data Pipelines
Information is not data.  Data is well formatted, regular, and able to be 
leveraged by statistical models.  As such, building a pipeline that will clean 
and transform the data into well formatted files is very important.  If you 
web-scraped into Mongo, consider a pipeline that will read in `.json` from Mongo 
and write tabular, cleaned data to PostgresQL.

#### Data Visualization
A significant portion of this project should be devoted to data exploration and plotting. 
Make sure to follow best practices (axis labels with easily legible font!).  

#### Hypothesis Testing
This capstone is an excellent time to demonstrate your ability to conduct a 
statistical study.  Remember that test power, significance levels, the null
and alternate hypotheses should be conducted before a single byte of data is 
collected.

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
We only have a week for this capstone; it's hard to do a good job when you've only 
had the real dataset for a couple of days.  This can make it challenging to 
work with a company.  Their timescale is different from the DSI.  "Fast" for them is a 
couple of weeks.  You needed the dataset yesterday.

3) State your MVP.  MVP is your Minimum Viable Product.  What's the minimum that you 
hope to accomplish?  Then, feel free to expand on MVP+, and MVP++.  

## Evaluation  
The three capstones account for 40% of your DSI assessment score/grade.  The scores
equally weight each capstone, and equally weight the presentations (~10 minutes) and 
accompanying Github for each capstone.  

#### Capstone I Github scoring rubric:

|Scoring item                          |Points | Description                                                 |
|:-------------------------------------|:-----:|:------------------------------------------------------------|
|Repository organization               |   3   | 0: No organization. 3: scripts in `src`, jupyter notebooks in `notebooks`, data, images, and other files similarly organized.|
|Appropriate use of scripts/notebooks  |   3   | 0: Everything in a jupyter notebook, 3: Perhaps some EDA presented in notebooks, but data acquisition, cleaning, and important analyses in scripts.|
|Object-oriented programming           |   3   | 0: You are repeating repeating yourself yourself. 2: In functions. 3: Appropriate use of classes|
|Code style                            |   3   | 0: It is difficult to understand what your code is doing and what variables signify. 2: Good variable/function/class names, `if __name__ == '__main__'` block, appropriate documentation.  3: All previous and would perfectly pass a [pycodestyle](https://pypi.org/project/pycodestyle/) test.|
|Coding effort (in scripts)            |   3   | 0: <= 50 lines of code, 1: 51-100, 2: 101-150, 3: > 150     |

#### Capstone I presentation scoring rubric
|Scoring item                          |Points | Description                                                 |
|:-------------------------------------|:-----:|:------------------------------------------------------------|
|Project question/goal                 |   2   | 0: What are you doing? 2: Stated clearly with gusto.        |
|Description of raw data               |   2   | 0: Mentioned in passing - no idea of what the features are, where it came from, how it was obtained.  1: Just a few features, the source described in text (but no images of raw data.) 2: Source described, walk through exemplary features and rows, appropriate tables/screenshots.|
|Exploratory Data Analysis             |   3   | 0: Who needs to understand the data, anyway? 1: Perfunctory - general pair-wise scatter matrix that says..what? 2:  Documentation of interesting relationships between the features and target. 3: All previous and with thoughtful feature engineering.|
|Analysis (e.g cleaning pipeline, database creation, statistical tests) |   5   | 0: None apparent. 3: Done but with some minor things missing/incorrect.  5: Nicely done, impressive effort.| 
|README                                |   3   | 0: Missing or useless in describing project.  1: Misspellings, hard to read font, strange formatting, ugly screenshots, inconsistent text sizes, wall-of-text. 2: Generally pleasing that describes project well - good illustrations, a few minor issues. 3: Beautiful and an impressive showcase for the project with good organization, appropriate use of text and illustrations, and helpful references.|


