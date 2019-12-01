# Welcome

Welcome to the Galvanize Data Science Immersive Program!  On this page you'll find information you about the program as a whole as well as links to daily readings and assignments.  You'll be working with this page everyday - please bookmark it in your web browser.

# Weekly overview
The Data Science Immersive (DSI) has 8 instructional weeks, 3 capstone weeks, and the final showcase week.  Most instructional weeks begin with a 1 hour assessment on Monday and end with a group case study on Friday.

The capstone weeks are reserved for your capstone projects (see below).  You will scrum with your peers during this time, participate in mock job interiews, and at the end of the week present your project to either your peers and instructors (capstones 1 & 2), or the data science community in the capstone showcase (capstone 3).

The final week is reserved for finishing your capstone, completing Career Services deliverables, presenting at the capstone showcase, and graduating.

To jump to a week of interest, click on the link.  

| Week | Date | Topic |
| --- | --- | --- |
| 1 | 12/02/19 | [Programming](#week-1-programming-for-data-science) |
| 2 | 12/09/19 | [Statistical Inference](#week-2-statistical-inference) | 
| 3 | 12/16/19 | [Big Data](#week-3-big-data) |
| - | 12/23/19 | Break Week |
| - | 12/30/19 | Break Week |
| 4 | 01/06/20 | [Capstone 1](#week-4-unit-1-capstone)|
| 5 | 01/13/20 | [Regression](#week-5-supervised-learning-and-regression)|
| 6 | 01/20/20| [Supervised Learning](#week-6-nonlinear-supervised-learning)|
| 7 | 01/27/20 | [Unsupervised Learning](#week-7-nlp-and-unsupervised-learning)|
| 8 | 02/03/20 | [Capstone 2](#week-8-unit-2-capstone)|
| 9 | 02/10/20 | [Advanced Topics 1](#week-9-advanced-topics-1) |
| 10 | 02/17/20 | [Advanced Topics 2](#week-10-advanced-topics-2) |
| 11| 02/24/20 | [Capstone 3](#week-11-unit-3-capstone) |
| 12 | 03/02/20 | [Showcase](#week-12-showcase) |

## Other important links
* [Solutions repo](https://github.com/GalvanizeDataScience/solutions-g105)  Solutions for the daily assignments, weekly reviews, and assessments will be added to this repository.  If a solution is missing, please bug an instructor!
* [Weekly feedback](https://forms.gle/26uC3TQmSaZCqfW49) Every Friday you'll be given some time to reflect on the week and be given a chance to let us know how you're doing.  Then let us know how well you think we taught the material.  We'll use your contstructive criticism to adapt as the course proceeds.
* [Past student projects](https://github.com/GalvanizeDataScience/project-proposals/blob/master/past_student_projects.md)  Whether you're looking for capstone ideas or resources to help you with your current capstone, take a look here.  The instructor voted most exemplary/helpful ones are marked with an astericks.
* [Lectures](https://github.com/GalvanizeDataScience/lectures/tree/Denver) Lectures for each day can be found in the lectures repo of the same name.  Clone (don't Fork) this repo.  Then checkout the Denver branch.

## Capstone Projects
Capstone projects allow you to put in to practice some of the knowledge you are gaining in the program on projects of your choosing.  They help build your Github portfolio, and give you specific skills to talk about during job interviews.You will submit capstone proposals to the instructors for approval before the capstone weeks begin.  Very often capstone 3 builds on work done on capstone 2, and sometimes even capstone 1.


# Daily Outline
In the weekly tables below, each row represents a day.  Each row information and links on:

* __Day:__ Day of the Week
* __Repos:__ The day's exercises.
* __Readings__ Readings for the day (complete the night before).

The readings are expected to take 1-1.5 hours each night. They will help you understand the lecture material better the next day. 

### Week 1: Programming for Data Science
|    Day    |Repos                                                                           |         Readings (bold is required)             |  
|:---------:|:-------------------------------------------------------------------------------|:------------------------------------------------|    
| Monday    |Assessment 0<br>Orientation<br>[git][git]<br>[Unix][c1.1.1]                     |  [**Development Workflow**][r1.1.1]<br>[**Pair Programming**][r1.1.2]<br>[**A Taxonomy of Data Science**][r-tds]<br>[**Unix Philosophy**][1.1.3]|
| Tuesday   |[Python Intro.][python]<br>[OOP][oop] (Denver branch)                           | [**Python code style**][r-python]<br>[**Classes**][r-oop]|
| Wednesday |[Numpy][c1.4.1]<br/>[Linear Algebra][c1.4.2]                                    | [**Linear Algebra Overview**][r-dlb-la](2.1-2.7)<br>[**Linear Algebra and Numpy**][r-la-np] |
| Thursday  |[Pandas][c1.2.1]<br>[Matplotlib][c1.2.2]                                        | [**10 minutes to Pandas**][1.2.1]<br>[**Matplolib tutorial and reference**][r-mpl]<br>[**Less is More**][1.2.6]<br>[Pandas Top 10][1.2.2]<br>[EDA with pandas][1.2.3]<br>[Data Wrangling with pandas][1.2.4]<br>[Effective Matplotlib][1.2.5]|
| Friday    |[Review][wr]<br>[Feature Branch Workflow][fbw]<br>[EDA case study][cs-eda]    | [**Git workflows**][r-gwf] (esp. feature branch)<br>[**What is EDA?**][r-eda1]<br><br>Examples of beautiful EDA:<br>[**Denver Auto Accidents**][r-jh]<br>(check out the plotting code in `src/plot.py`)<br>[**Service Provisions by Non-State Actors**][r-jst]<br>(see `FinalCode.py`)|

--

### Week 2: Statistical Inference
|    Day    | Repos                                                                          |                     Readings                   |  
|:---------:|:-------------------------------------------------------------------------------|:-----------------------------------------------|    
| Monday    | Assessment 1<br>[Probability][prob-dist]<br>[Binomial Tests][binom-tst]        | [**Seeing Theory: Basic Prob., Compound Prob., and Prob. Distributions**][r-see-theory-1-3]<br>[**Binomial Test**][v-binom-t]<br>[Review of Probability Theory][3.1.1] |
| Tuesday   | [Sampling Distributions][smp-dist]<br>[Law of Large Numbers][law-ln]           | [**Seeing Theory: Frequentist Inference**][r-see-theory-4]<br>[**Law of Large Numbers**][r-law-large-numbers]|
| Wednesday | [Central Limit Theorem][clt-bs]<br>[Maximum Likelihood Estimation][mle]        |[**Central Limit Theorem**][v-clt]<br>[**MLE**][v-mle1]<br>[MLE for Normal][v-mle2]   |
| Thursday  | [Hypothesis Testing][hyp-ts-d]<br>[Power Calculation][power]                   |[**z-test VS t-test**][3.4.1]<br>[**Hypothesis Testing**][3.4.2]<br>[**Power Analysis**][3.4.3]|
| Friday    | [Review][wr]<br>[Bayesian Inference][r-bi]<br>[Bayesian Testing][r-bab]        |[**Intro. to Bayesian Statistics 1**][r-ibs1]<br>[**Intro. to Bayesian Statistics 2**][r-ibs2]|

--

### Week 3: Big Data
|    Day    | Repos                                                                          | Readings                                        |  
|:---------:|:-------------------------------------------------------------------------------|:------------------------------------------------|    
| Monday    | Assessment 3<br>[Algorithmic Complexity][c2.1.1]<br>[Docker][c2.2.1]           |[**Introduction to Algorithms**][algorithms] (ch 2, pg 16-37)<br>[**Docker Getting Started**][2.2.1](wait to install in class)<br>[Big O notation][r-bigO]|
| Tuesday   | [SQL][c2.3.1]<br>[Python SQL][c2.3.2]                                          |[**SQLZOO (tutorial: 1-9)**][2.3.1]<br>[**Psycopg**][r-psycopg]<br>[Visual Explanation of Joins][2.3.2]|
| Wednesday | [AWS][c2.2.2]<br>[Mongo & Web Scraping][c1.5.2]                                |[**About AWS**][r-about-AWS]<br>[**Getting Started on AWS**][r-start-AWS]<br>**Read through three 10 minute tutorials**:<br>- Launch a VM (EC2)<br>- Store and Retrieve a File (S3)<br>- Store Multiple Files to the Cloud Using s3 and the AWS CLI<br>[**MongoDB Basics**][r-mdb]<br>[**Webscraping with Python and Beautiful Soup**][r-ws]|
| Thursday  | [CI proposal due 9 am][cI]<br>[Spark RDDs][c2.4.1]<br/>[Spark SQL][c2.4.2]     |[**Learning Spark**][LearningSpark] (ch 1-2, pg 1-22)<br>[Learning Spark][LearningSpark] (ch 11: MLlib, pg 183-212)|
| Friday    | [Review][wr]<br>[Spark EDA Case Study][c2.5.1]                                 |-                          |--

--

### Break Weeks 1 and 2
Your priorities for the holiday break:
<ul>
<li>Study material from the previous weeks.</li>
<li>Research capstone 1 ideas</li>
<li>Recharge for the rest of the course</li>
</ul>

--

### Week 4: Unit 1 Capstone
| Day  | Topic | Readings |
|:--:|:--|:---|
| Monday |  Assessment 2<br>[Capstone I][cI]<br>[Mock Interview][mi] |  -  |
| Tuesday | [Capstone I][cI]<br>[Mock Interview][mi] | - |
| Wednesday | [Capstone I][cI]<br>[Mock Interview][mi] | - |
| Thursday | [Capstone I][cI]<br>[Mock Interview][mi] | - |
| Friday | Code Review / Capstone Presentations  | - |

--

### Week 5: Supervised Learning and Regression
|    Day    | Repos                                                                          |                     Readings                   |  
|:---------:|:-------------------------------------------------------------------------------|:-----------------------------------------------|    
| Monday    |[KNN][c5.1.1]<br>[Cross Validation][c5.1.2]                                     | ---- |
| Tuesday   |[Linear Regression Intro][r-lreda]<br>[Predictive Linear Regression][r-prlr]    | ---- |
| Wednesday |[Regularized Regression][c5.3.1]<br>[Logistic Regression][c5.4.1]               | ---- |
| Thursday  |[Gradient Descent][r-grds]<br>[Decision Rules (Denver)][r-decr]                 | ---- |
| Friday    |[Review][wr]<br>[Regression Case Study (Denver)][c5.5.1]                       | ---- |

--

### Week 6: Nonlinear Supervised Learning
|    Day    | Repos                                                                          |                     Readings                   |  
|:---------:|:-------------------------------------------------------------------------------|:-----------------------------------------------|    
| Monday    | Assessment 4<br>[Decision Trees][c6.1.2]<br>[Bagging][c6.2.1]                  | ---- |
| Tuesday   |[Random Forests][r-rfa]<br>[Gradient Boosted Regressors][c6.3.1]                | ---- |
| Wednesday |[Time Series][r-ts]<br> [Neural nets - MLP (Denver)][c6.4.2]                    | ---- |
| Thursday  |[Image Analysis][r-imp]<br>[Neural nets - CNN][r-cnn]                           | ---- |
| Friday    |[Review][wr]<br>[Supervised Learning Case Study][r-csml]                        | ---- |

--

### Week 7: NLP and Unsupervised Learning
|    Day    | Repos                                                                          |                     Readings                   |  
|:---------:|:-------------------------------------------------------------------------------|:-----------------------------------------------|    
| Monday    | Assessment 5<br>[NLP Intro (Denver)][r-nlp]<br>[Text Classification][r-nvb]    | ---- | 
| Tuesday   | [PCA][r-pca]<br>[SVD][r-svd]                                                   | ---- |
| Wednesday | [Clustering][r-clst]<br>[NMF][r-tm]                                            | ---- |
| Thursday  | [Latent Dirchlet Allocation][r-lda]<br>[Graphs][r-gr1]                         | ---- |
| Friday    | CII proposals due 9 am<br>[Review][wr]<br>[NLP & Unsupervised Learning Case Study][r-csnlp2]| ---- |

--

### Week 8: Unit 2 Capstone
|    Day    | Repos                                                                          |                     Readings                   |  
|:---------:|:-------------------------------------------------------------------------------|:-----------------------------------------------|    
| Monday | [Capstone 2][cII]<br>[Mock Interviews][mi] | - |
| Tuesday | [Capstone 2][cII]<br>[Mock Interviews][mi]|  -  |
| Wednesday |[Capstone 2][cII]<br>[Mock Interviews][mi]|  -  |
| Thursday  |[Capstone 2][cII]<br>[Mock Interviews][mi] | - |
| Friday | Code Review / Capstone Presentations   | - |

--

### Week 9: Advanced Topics 1
|    Day    | Repos                                                                          |                     Readings                   |  
|:---------:|:-------------------------------------------------------------------------------|:-----------------------------------------------|    
| Monday    | Assessment 6<br/>[Data products: Flask][r-flsk]                                | ---- |
| Tuesday   | [Neural Nets- RNN][r-rnn]                                                      | ---- |
| Wednesday | [Content-based Recommenders][r-cbr]<br>[Similarity Recommenders][r-smr]        | ---- |
| Thursday  | [Matrix Factorization Recommenders][r-mfr]                                     | ---- |
| Friday    | [Recommender Case Study (Denver)][r-csrec1]                                    | ---- |

--

### Week 10: Advanced Topics 2
|    Day    | Repos                                                                          |                     Readings                   |  
|:---------:|:-------------------------------------------------------------------------------|:-----------------------------------------------|    
| Monday    |[Bayesian Testing][r-bab]<br> [Multi-Armed Bandit][r-mab]                       | ---- |
| Tuesday   |[Autoencoders (Denver)][c10.3.1]<br>[Transfer Learning][r-tlnn]                          | ---- |
| Wednesday |[Monte Carlo Markov Chain][r-mcmc]<br>Open or [RL with neural networks][r-rlnn] | ---- |
| Thursday  |CIII proposals due 9 am<br>[Fraud Case Study (day 1)][r-fdcs]                  | ----- |
| Friday    | [Fraud Case Study (day 2)][r-fdcs]                                             | ----- |

--
### Week 11: Unit 3 Capstone
|    Day    | Repos                                                                          |                     Readings                   |  
|:---------:|:-------------------------------------------------------------------------------|:-----------------------------------------------|    
| Monday |  Capstone III<br>[Mock Interview][mi] |  -  |
| Tuesday | Capstone III<br>[Mock Interview][mi] | - |
| Wednesday | Capstone III<br>[Mock Interview][mi] | - |
| Thursday | Capstone III<br>[Mock Interview][mi] | - |
| Friday | **Talk/Poster drafts due 12 pm**<br>(must have preliminary results)<br>Capstone III<br>[Mock Interview][mi]| - |

--

### Week 12: Showcase
|    Day    | Repos                                                                          |                     Readings                   |  
|:---------:|:-------------------------------------------------------------------------------|:-----------------------------------------------|    
| Monday |**CODE FREEZE 3 pm**| - |
| Tuesday | |  -   |
| Wednesday |   |  -  |
| Thursday | PM - Showcase |  -  |
| Friday | Lunch - Graduation |  -  |

--

## Textbooks
We will focus on a few canonical texts for the class and readings will be assigned from them. If they are not in a physical form in our library, they are located in digital form on the Time Capsule or the Internet.
* [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20Sixth%20Printing.pdf): The book we use for the majority of machine learning readings.
* [Machine Learning In Action](https://drive.google.com/file/d/0B1cm3fV8cnJwcUNWWnFaRWgwTDA/view?usp=sharing):

### Supplementary
* [Doing Data Science](http://www.amazon.com/Doing-Data-Science-Straight-Frontline/dp/1449358659): One of the best treatments of the field with plenty of case studies.
* [Python for Data Analysis](http://shop.oreilly.com/product/0636920023784.do): Some of the `pandas` methods have changed (always reference `pandas` [online documentation](http://pandas.pydata.org/)) but a solid book on data analysis in Python.
* [Practical Data Science with R](http://www.manning.com/zumel/): through we will not use R, this is a stellar book and we will use it for its content/theory

## Getting Help
* [Data Science Stack Exchange](http://datascience.stackexchange.com/)
* [Stats Stack Exchange](http://stats.stackexchange.com/)
* [MetaOptimize: ML and Datascience forum](http://metaoptimize.com/qa)

## References

### Machine Learning
* [Machine Learning in Action](http://www.manning.com/pharrington/)
* [Programming Collective Intelligence](http://www.amazon.com/Programming-Collective-Intelligence-Building-Applications/dp/0596529325)
* [Machine Learning for Hackers](http://shop.oreilly.com/product/0636920018483.do)
* [An Introduction to Machine Learning](http://alex.smola.org/drafts/thebook.pdf)

### Statistics
* [Probabilistic Programming and Bayesian Methods for Hackers](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)
* [Think Stats](http://www.greenteapress.com/thinkstats/)
* [Think Bayes](http://www.greenteapress.com/thinkbayes/)
* [All of Statistics](http://www.stat.cmu.edu/~larry/all-of-statistics/)
* [Mostly Harmless Econometrics](http://www.amazon.com/Mostly-Harmless-Econometrics-Empiricists-Companion/dp/0691120358)

### Computer Science/Programming
* [Think Python](http://www.greenteapress.com/thinkpython/thinkpython.html)
* [Algorithms (Papadimitriou)](http://www.cs.berkeley.edu/~vazirani/algorithms)
* [Think Complexity: Analysis of Algorithms](http://www.greenteapress.com/compmod/html/thinkcomplexity004.html)


### Numpy
* [Official Numpy Tutorial](http://wiki.scipy.org/Tentative_NumPy_Tutorial)
* [scipy Lectures](https://scipy-lectures.github.io/intro/numpy/index.html)
* [Crash Course in Python for Scientist](http://nbviewer.ipython.org/gist/rpmuller/5920182)
* [Scientific Python Lectures](http://nbviewer.ipython.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-2-Numpy.ipynb)
* [Numpy Broadcasting](http://wiki.scipy.org/EricsBroadcastingDoc)
* [Python Bootcamp Lectures](http://nbviewer.ipython.org/github/profjsb/python-bootcamp/blob/master/Lectures/05_NumpyMatplotlib/IntroNumPy.ipynb)

### SQL
* [http://sqlfiddle.com/](http://sqlfiddle.com/)
* [http://use-the-index-luke.com/](http://use-the-index-luke.com/)
* [http://missqlcommand.com/](http://missqlcommand.com/)
* [http://sql.learncodethehardway.org/book/](http://sql.learncodethehardway.org/book/)
* [SQL School](http://sqlschool.modeanalytics.com/)

### Scipy
* [scipy Lectures](https://scipy-lectures.github.io)

### scikit-learn
* [Introduction to Machine Learning with sklearn](http://researchcomputing.github.io/meetup_spring_2014/python/sklearn.html)
* [scikit-learn workshop](https://github.com/jakevdp/sklearn_pycon2014)
* [Machine Learning Tutorial](https://github.com/amueller/tutorial_ml_gkbionics)
* [Introduction to scikit-learn](http://nbviewer.ipython.org/github/tdhopper/Research-Triangle-Analysts--Intro-to-scikit-learn/blob/master/Intro%20to%20Scikit-Learn.ipynb)
* [Data analysis with scikit-learn](http://sebastianraschka.com/Articles/2014_scikit_dataprocessing.html)
* [Advanced Machine Learning with scikit-learn](https://us.pycon.org/2013/community/tutorials/23/)

### Extra
* [University of Colorado Computational Science workshops](http://researchcomputing.github.io/meetup_spring_2014/)
* [Networkx tutorial](http://snap.stanford.edu/class/cs224w-2012/nx_tutorial.pdf)

<!-- ************************** References **************************************** -->
<!-- References have been reorganized into several sections.  Please add links in accor - ce with the name and numbering schema-->
<!-- ************************** References **************************************** -->
<!-- References have been reorganized into several sections.  Please add links in accor - ce with the name and numbering schema-->

<!-- Lecture Repos -->
<!-- Week 1 -->

<!-- Content Repos (sprints and assessments) -->
<!-- Week 1 -->
[c1.1.1]: https://github.com/GalvanizeDataScience/unix
[c1.2.1]: https://github.com/GalvanizeDataScience/pandas
[c1.2.2]: https://github.com/GalvanizeDataScience/matplotlib
[c1.3.1]: https://github.com/GalvanizeDataScience/oop
[c1.4.1]: https://github.com/GalvanizeDataScience/numpy
[c1.4.2]: https://github.com/GalvanizeDataScience/linear-algebra
[c1.5.1]: https://github.com/GalvanizeDataScience/mongo-db
[c1.5.2]: https://github.com/GalvanizeDataScience/web-scraping

<!-- Week 2 -->
[c2.1.1]: https://github.com/GalvanizeDataScience/algorithmic-complexity
[c2.1.2]: https://github.com/GalvanizeDataScience/data-structures
[c2.2.1]: https://github.com/GalvanizeDataScience/docker
[c2.2.2]: https://github.com/GalvanizeDataScience/aws
[c2.3.1]: https://github.com/GalvanizeDataScience/sql
[c2.3.2]: https://github.com/GalvanizeDataScience/sql-python
[c2.4.1]: https://github.com/GalvanizeDataScience/spark-rdds
[c2.4.2]: https://github.com/GalvanizeDataScience/spark-dfs
[c2.5.1]: https://github.com/GalvanizeDataScience/Spark-Case-Study

<!-- Week 3 -->
[c3.2.1]: https://github.com/GalvanizeDataScience/sampling-distributions
[c3.2.2]: https://github.com/GalvanizeDataScience/law-of-large-numbers
[c3.3.1]: https://github.com/GalvanizeDataScience/central-limit
[c3.3.2]: https://github.com/GalvanizeDataScience/maximum-likelihood
[c3.4.1]: https://github.com/GalvanizeDataScience/hypothesis-testing
[c3.4.2]: https://github.com/GalvanizeDataScience/statistical-power

<!-- Week 4 -->

<!-- Week 5 -->
[c5.1.1]: https://github.com/GalvanizeDataScience/knn
[c5.1.2]: https://github.com/GalvanizeDataScience/cross-validation
[c5.2.1]: https://github.com/GalvanizeDataScience/predictive-linear-regression
[c5.3.1]: https://github.com/GalvanizeDataScience/regularized-regression
[c5.3.2]: https://github.com/GalvanizeDataScience/inferential-regression
[c5.4.1]: https://github.com/GalvanizeDataScience/logistic-regression
[c5.4.2]: https://github.com/GalvanizeDataScience/decision-rules
[c5.5.1]: https://github.com/GalvanizeDataScience/regression-case-study

<!-- Week 6-->
[c6.1.1]: https://github.com/GalvanizeDataScience/search-trees
[c6.1.2]: https://github.com/GalvanizeDataScience/decision-trees
[c6.2.1]: https://github.com/GalvanizeDataScience/random-forests
[c6.3.1]: https://github.com/GalvanizeDataScience/gradient-boosted-regression
[c6.3.2]: https://github.com/GalvanizeDataScience/gradient-boosted-classification
[c6.4.1]: https://github.com/GalvanizeDataScience/gradient-descent
[c6.4.2]: https://github.com/GalvanizeDataScience/perceptrons
[c6.5.1]: https://github.com/GalvanizeDataScience/supervised-learning-case-study/

<!-- Week 10 -->
[c10.3.1]: https://github.com/GalvanizeDataScience/auto-encoders

<!-- Readings -->
<!-- Week 1 -->
[r1.1.1]: notes/workflow.md
[r1.1.2]: notes/pairing.md

<!-- Denver -->
<!-- Week 1 -->
[git]: https://github.com/GalvanizeDataScience/git-intro
[unix]: https://github.com/gSchool/dsd-unix
[r-aws]: notes/setup_aws.md
[r-unix]: https://en.wikipedia.org/wiki/Unix_philosophy
[r-tds]: http://www.dataists.com/2010/09/a-taxonomy-of-data-science/
[r-python]: https://docs.python-guide.org/writing/style/#general-concepts
[r-oop]: http://www.greenteapress.com/thinkpython/html/thinkpython016.html
[r-dlb-la]: http://www.deeplearningbook.org/contents/linear_algebra.html
[r-la-np]: https://github.com/GalvanizeDataScience/course-outline/blob/master/notes/reading_material/numpy_reading.md
[r-gwf]: https://buddy.works/blog/5-types-of-git-workflows
[r-eda1]: https://www.itl.nist.gov/div898/handbook/eda/section1/eda11.htm
[r-jh]: https://github.com/johnherr/Traffic-Accidents-in-Denver
[r-jst]: https://github.com/gagejane/Terrorism-NonViolent
[python]: https://github.com/GalvanizeDataScience/python-intro/
[oop]: https://github.com/GalvanizeDataScience/oop/tree/Denver
[l-py]: https://github.com/gschool/DSI_Lectures/tree/master/python-intro
[l-oop]: https://github.com/gschool/DSI_Lectures/tree/master/OOP
[r-pan]: http://pandas.pydata.org/pandas-docs/stable/getting_started/10min.html
[r-mpl]: https://www.stat.berkeley.edu/~nelle/teaching/2017-visualization/README.html
[l-pn]: https://github.com/gschool/DSI_Lectures/tree/master/pandas
[l-mpl]: https://github.com/gSchool/DSI_Lectures/tree/master/pandas-matplotlib
[r-la]: https://github.com/gschool/dsi-precourse/blob/master/Chapter_2_Linear_Algebra/notes.md
[r-la4ds]: https://medium.com/@rathi.ankit/linear-algebra-for-data-science-a9648b9daee0
[l-nplalg]: https://github.com/gSchool/DSI_Lectures/tree/master/numpy-linear-algebra
[r-mdb]: https://flaviocopes.com/mongodb/
[r-ws]: https://www.dataquest.io/blog/web-scraping-tutorial-python/
[l-md]: https://github.com/gSchool/DSI_Lectures/tree/master/mongo/elliot_cohen
[l-ws]: https://github.com/gschool/DSI_Lectures/tree/master/web-scraping
[wr]: https://github.com/GalvanizeDataScience/weekly-student-led-review
[cs-eda]: https://github.com/GalvanizeDataScience/pandas-eda-case-study
[fbw]: https://github.com/GalvanizeDataScience/feature-branch-git-workflow

<!-- Week 2 -->
[prob-dist]: https://github.com/GalvanizeDataScience/probability-distributions
[binom-tst]: https://github.com/GalvanizeDataScience/binomial-tests
[smp-dist]: https://github.com/GalvanizeDataScience/sampling-distributions
[law-ln]: https://github.com/GalvanizeDataScience/law-of-large-numbers
[clt-bs]: https://github.com/GalvanizeDataScience/central-limit-theorem
[mle]: https://github.com/GalvanizeDataScience/maximum-likelihood
[hyp-ts-d]: https://github.com/GalvanizeDataScience/hypothesis-testing-dev
[power]: https://github.com/GalvanizeDataScience/statistical-power
[flask]: https://github.com/GalvanizeDataScience/data-products
[l-prob]: https://github.com/gSchool/DSI_Lectures/tree/master/probability
[l-samp]: https://github.com/gSchool/DSI_Lectures/tree/master/estimation-sampling
[l-powr]: https://github.com/gSchool/DSI_Lectures/tree/master/power-bayesian
[l-flsk]: https://github.com/gSchool/DSI_Lectures/tree/master/data-products
[l-ab]: https://github.com/gSchool/DSI_Lectures/tree/master/ab-testing
[v-mle1]: https://www.youtube.com/watch?v=XepXtl9YKwc
[v-mle2]: https://www.youtube.com/watch?v=Dn6b9fCIUpM
[v-clt]: https://www.youtube.com/watch?v=YAlJCEDH2uY
[v-binom-t]: https://www.youtube.com/watch?v=J8jNoF-K8E8
[r-ibs1]: https://mathcs.clarku.edu/~djoyce/ma218/bayes1.pdf
[r-ibs2]: https://mathcs.clarku.edu/~djoyce/ma218/bayes2.pdf


<!-- Week 3-->
[l-bgO]: https://github.com/gSchool/DSI_Lectures/tree/master/big-O
[l-dck]: https://github.com/gSchool/DSI_Lectures/tree/master/docker
[l-aws]: https://github.com/gSchool/DSI_Lectures/tree/master/aws
[l-sql]: https://github.com/gSchool/DSI_Lectures/tree/master/sql
[l-pg2]: https://github.com/gSchool/DSI_Lectures/tree/master/sql-python
[l-spk]: https://github.com/gSchool/DSI_Lectures/tree/master/spark

[prob-dist]: https://github.com/GalvanizeDataScience/probability-distributions
[binom-tst]: https://github.com/GalvanizeDataScience/binomial-tests
[smp-dist]: https://github.com/GalvanizeDataScience/sampling-distributions
[law-ln]: https://github.com/GalvanizeDataScience/law-of-large-numbers
[clt-bs]: https://github.com/GalvanizeDataScience/central-limit-theorem
[mle]: https://github.com/GalvanizeDataScience/maximum-likelihood
[hyp-ts-d]: https://github.com/GalvanizeDataScience/hypothesis-testing-dev
[power]: https://github.com/GalvanizeDataScience/statistical-power
[flask]: https://github.com/GalvanizeDataScience/data-products
[l-prob]: https://github.com/gSchool/DSI_Lectures/tree/master/probability
[l-samp]: https://github.com/gSchool/DSI_Lectures/tree/master/estimation-sampling
[l-powr]: https://github.com/gSchool/DSI_Lectures/tree/master/power-bayesian
[l-flsk]: https://github.com/gSchool/DSI_Lectures/tree/master/data-products
[l-ab]: https://github.com/gSchool/DSI_Lectures/tree/master/ab-testing

<!-- Week 4-->
[mi]: https://github.com/GalvanizeDataScience/mock-interview-questions
[cI]: ./notes/capstone_I.md

<!-- Week 5-->
[l-knn]: https://github.com/gschool/DSI_Lectures/tree/master/non-parametric-learners
[l-rgcv]: https://github.com/gschool/DSI_Lectures/tree/master/regularized-regression
[l-linr]: https://github.com/gschool/DSI_Lectures/tree/master/linear-regression
[l-logr]: https://github.com/gschool/DSI_Lectures/tree/master/logistic-regression
[l-regr]: https://github.com/gschool/DSI_Lectures/tree/master/regularized-regression
[l-grds]: https://github.com/gSchool/DSI_Lectures/tree/master/gradient-descent
[l-decr]: https://github.com/gSchool/DSI_Lectures/tree/master/profit-curve
[r-linr]: https://github.com/gSchool/dsi-linear-regression
[r-grds]: https://github.com/GalvanizeDataScience/gradient-descent
[r-decr]: https://github.com/GalvanizeDataScience/decision-rules
[cs-regression]: https://github.com/gSchool/dsd-case-study-linear-models
[r-lreda]: https://github.com/GalvanizeDataScience/linear-regression-eda
[r-prlr]: https://github.com/GalvanizeDataScience/predictive-linear-regression

<!-- Week 6-->
[r-abst]: https://github.com/gSchool/dsi-boosting
[l-dt]: https://github.com/gSchool/DSI_Lectures/tree/master/non-parametric-learners
[l-rf]: https://github.com/gSchool/DSI_Lectures/tree/master/random-forest
[l-boo]: https://github.com/gSchool/DSI_Lectures/tree/master/boosting
[l-mlp]: https://github.com/gSchool/DSI_Lectures/tree/master/nn-mlp
[l-cnn]: https://github.com/gSchool/DSI_Lectures/tree/master/nn-cnn
[l-rnn]: https://github.com/gSchool/DSI_Lectures/tree/master/nn-rnn
[r-cnn]: https://github.com/GalvanizeDataScience/convolutional-neural-nets
[r-rnn]: https://github.com/GalvanizeDataScience/recurrent-neural-nets
[r-csml]: https://github.com/gSchool/dsd-non-parametric-case-study
[r-imp]: https://github.com/GalvanizeDataScience/image-processing
[l-imp]: https://github.com/gSchool/DSI_Lectures/tree/master/image_featurization
[r-rfa]: https://github.com/GalvanizeDataScience/random-forests-application

<!-- Week 8-->
[r-nlp]: https://github.com/GalvanizeDataScience/nlp
[r-nvb]: https://github.com/GalvanizeDataScience/text-classification
[l-nlp]: https://github.com/gSchool/DSI_Lectures/tree/master/nlp
[r-pca]: https://github.com/GalvanizeDataScience/pca
[r-svd]: https://github.com/GalvanizeDataScience/svd
[r-clst]: https://github.com/GalvanizeDataScience/clustering
[r-tm]: https://github.com/GalvanizeDataScience/topicmodeling
[r-gr1]: https://github.com/GalvanizeDataScience/graphs-searching
[r-gr2]: https://github.com/GalvanizeDataScience/graphs-communities
[l-pca]: https://github.com/gSchool/DSI_Lectures/tree/master/dimensionality-reduction
[r-lda]: https://github.com/gSchool/dsd-lda
[l-clst]: https://github.com/gSchool/DSI_Lectures/tree/master/clustering
[l-tm]: https://github.com/gSchool/DSI_Lectures/tree/master/topicmodeling
[l-grph]: https://github.com/gSchool/DSI_Lectures/tree/master/graphs
[r-csnlp]: https://github.com/GalvanizeDataScience/nlp_case_study
[r-csnlp2]: https://github.com/gSchool/dsi-unsupervised-case-study
[cII]: ./notes/capstone_II.md

<!-- Week 9-->
[r-ts]: https://github.com/GalvanizeDataScience/time-series
[l-ts]: https://github.com/gSchool/DSI_Lectures/tree/master/time-series
[r-bi]: https://github.com/GalvanizeDataScience/bayes-intro
[r-bab]: https://github.com/GalvanizeDataScience/bayes-testing
[l-bab]: https://github.com/gSchool/DSI_Lectures/tree/master/power-bayesian
[l-bay]: https://github.com/gschool/DSI_Lectures/tree/master/power-bayesian
[l-mab]: https://github.com/gschool/DSI_Lectures/tree/master/multi-armed-bandit
[r-cbr]: https://github.com/GalvanizeDataScience/content_based_recommender
[r-smr]: https://github.com/GalvanizeDataScience/similarity_based_recommenders
[l-rcmd]: https://github.com/gSchool/DSI_Lectures/tree/master/recommendation-systems
[r-mfr]: https://github.com/GalvanizeDataScience/factorization_recommender                      
[r-csrec]: https://github.com/GalvanizeDataScience/recommender-case-study
[r-mab]: https://github.com/GalvanizeDataScience/multi-armed-bandit
[l-mab]: https://github.com/gSchool/DSI_Lectures/tree/master/multi-armed-bandit   
[r-csrec2]: https://github.com/gSchool/dsd-recommender-case-study
[r-flsk]: https://github.com/GalvanizeDataScience/data-products
[l-flsk]: https://github.com/gSchool/DSI_Lectures/tree/master/data-products
[r-csrec1]: https://github.com/GalvanizeDataScience/recommender-case-study/tree/Denver


<!-- Week 10-->

<!-- Reading References -->

<!-- Books -->
[algorithms]: http://ressources.unisciel.fr/algoprog/s00aaroot/aa00module1/res/%5BCormen-AL2011%5DIntroduction_To_Algorithms-A3.pdf
[LearningSpark]: https://drive.google.com/file/d/0B1cm3fV8cnJwc2ZnMFJmT2RLOXM/view?usp=sharing
[ISLR]: http://www-bcf.usc.edu/~gareth/ISL/ISLR%20Sixth%20Printing.pdf
[MLIA]: https://drive.google.com/file/d/0B1cm3fV8cnJwcUNWWnFaRWgwTDA/view?usp=sharing
[EoSL]: https://web.stanford.edu/~hastie/ElemStatLearn/download.html
[MMDS]: http://infolab.stanford.edu/~ullman/mmds/book.pdf
[SNA]: readings/Social_Network_Analysis_for_Startups.pdf

<!-- Week 1 -->
[1.1.1]: workflow.md
[1.1.2]: pairing.md
[1.1.3]: https://en.wikipedia.org/wiki/Unix_philosophy
[1.1.4]: https://leanpub.com/artofdatascience

[1.2.1]: http://pandas.pydata.org/pandas-docs/stable/10min.html
[1.2.2]: http://manishamde.github.io/blog/2013/03/07/pandas-and-python-top-10/
[1.2.3]: http://nbviewer.ipython.org/github/cs109/content/blob/master/labs/lab3/lab3full.ipynb
[1.2.4]: http://nbviewer.ipython.org/github/cs109/content/blob/master/lec_04_wrangling.ipynb
[1.2.5]: http://pbpython.com/effective-matplotlib.html
[1.2.6]: http://www.randalolson.com/2014/06/28/how-to-make-beautiful-data-visualizations-in-python-with-matplotlib/
[r-mpl]: https://www.stat.berkeley.edu/~nelle/teaching/2017-visualization/README.html

[1.3.1]: https://www.souravsengupta.com/cds2015/python/LPTHW.pdf
[r-python]: https://docs.python-guide.org/writing/style/#general-concepts
[r-oop]: http://www.greenteapress.com/thinkpython/html/thinkpython016.html

[1.4.1]: https://github.com/GalvanizeDataScience/course-outline/blob/master/notes/reading_material/numpy_reading.md
[1.4.2]: http://cs229.stanford.edu/section/cs229-linalg.pdf
[r-la4ds]: https://medium.com/@rathi.ankit/linear-algebra-for-data-science-a9648b9daee0

[1.5.1]: http://openmymind.net/mongodb.pdf
[r-ws]: https://www.dataquest.io/blog/web-scraping-tutorial-python/
[1.5.2]: https://medium.freecodecamp.org/how-to-scrape-websites-with-python-and-beautifulsoup-5946935d93fe

<!-- Week 2 -->

[2.2.1]: https://docs.docker.com/get-started/
[r-start-AWS]: https://aws.amazon.com/start-now/
[r-about-AWS]: https://aws.amazon.com/about-aws/

[r-bigO]: https://medium.freecodecamp.org/time-is-complex-but-priceless-f0abd015063c

[2.3.1]: http://sqlzoo.net/wiki/Main_Page
[2.3.2]: http://blog.codinghorror.com/a-visual-explanation-of-sql-joins/
[2.3.3]: http://openmymind.net/mongodb.pdf
[r-psycopg]: http://www.postgresqltutorial.com/postgresql-python/


<!-- Week 3 -->
[3.1.1]: http://cs229.stanford.edu/section/cs229-prob.pdf
[r-see-theory-1-3]: https://seeing-theory.brown.edu/basic-probability/index.html
[r-binom-test]: https://en.wikipedia.org/wiki/Binomial_test

[r-see-theory-4]: https://seeing-theory.brown.edu/frequentist-inference/index.html
[r-law-large-numbers]: https://en.wikipedia.org/wiki/Law_of_large_numbers

[3.3.1]: https://www.khanacademy.org/math/probability/statistics-inferential/sampling_distribution/v/central-limit-theorem
[3.3.2]: https://www.youtube.com/watch?v=I_dhPETvll8

[3.4.1]: https://www.youtube.com/watch?v=5ABpqVSx33I
[3.4.2]: https://www.youtube.com/watch?v=-FtlH4svqx4
[3.4.3]: https://www.youtube.com/watch?v=lHI5oEgNkrk
[r-ibs2]: https://mathcs.clarku.edu/~djoyce/ma218/bayes2.pdf


<!-- Week 4 -->
[4.1.1]: http://flask.pocoo.org/
[4.1.2]: http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world
[4.1.3]: http://www.w3schools.com/tags/ref_httpmethods.asp

<!-- Week 5 -->


<!-- Week 6 -->
[6.4.1]: https://www.youtube.com/watch?v=bxe2T-V8XRs
[6.4.2]: http://www.asimovinstitute.org/neural-network-zoo/
[6.4.3]: http://cs229.stanford.edu/notes/cs229-notes1.pdf

<!-- Week 7 -->
[tfidf1]: http://blog.christianperone.com/?p=1589
[tfidf2]: http://blog.christianperone.com/?p=1747
[tfidf3]: http://blog.christianperone.com/?p=2497
[NLP]: https://radimrehurek.com/phd_rehurek.pdf
[py.nlp]: https://pdfs.semanticscholar.org/3673/bccde93025e05431a2bcac4e8ff18c9c273a.pdf
[nmf-reading]: http://www.quuxlabs.com/blog/2010/09/matrix-factorization-a-simple-tutorial-and-implementation-in-python/




<!-- Week 8 -->


<!-- Week 9 -->
[9.2.1]: http://stevehanov.ca/blog/index.php?id=132

[r-matrix-recom]:https://datajobs.com/data-science-repo/Recommender-Systems-%5BNetflix%5D.pdf

<!-- Week 10 -->
[10.1.2]: https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/
[10.1.3]: https://github.com/tensorflow/models/tree/master/research/inception

[10.2.1]: https://www.otexts.org/fpp
[10.2.2]: http://conference.scipy.org/proceedings/scipy2011/pdfs/statsmodels.pdf
[10.2.3]: https://colah.github.io/posts/2015-08-Understanding-LSTMs/
[10.2.4]: https://karpathy.github.io/2015/05/21/rnn-effectiveness/

[10.3.1]: http://ufldl.stanford.edu/tutorial/unsupervised/Autoencoders/
[10.3.2]: https://machinelearningmastery.com/transfer-learning-for-deep-learning/
[r-rlnn]: https://github.com/GalvanizeDataScience/reinforcement-learning-with-nn
[r-tlnn]: https://github.com/GalvanizeDataScience/transfer-learning
[r-mcmc]: https://github.com/GalvanizeDataScience/mcmc
[r-fdcs]: https://github.com/GalvanizeDataScience/fraud-detection-case-study
