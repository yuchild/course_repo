# Welcome 

Welcome to the Galvanize Data Science Immersive Program! On this page you'll find information you about the program as a whole as well as links to daily readings and assignments.  You'll be working with this page everyday; please bookmark it in your web browser. 

### Pairs for Each Day:

[Pairs](notes/g92ds_pairs.md) -- these are your daily pair assignments

#  Weekly overview
The Data Science Immersive (DSI) has 8 instructional weeks, 3 capstone weeks, and the final showcase week.  Most instructional weeks begin with a 1 hour assessment on Monday and end with a group case study on Friday. 

The capstone weeks are reserved for your capstone projects (see below).  You will scrum with your peers during this time, participate in mock job interiews, and at the end of the week present your project to your peers and instructors (capstones 1 & 2), or to the data science community on a demo day (capstone 3).

The final week is reserved for demo day, completing Career Services deliverables, mock interviews, and graduating.

To jump to a week of interest, click on the link. 

| Week | Date  | Topic |
| ---- |:-----:| ----- |
|  0 | 04/29/19 | Week 0 Prep |
|  1 | 05/06/19 | [Programming](#week-1-programming-for-data-science) |
|  2 | 05/13/19 | [Big Data](#week-2-big-data) |
|  3 | 05/20/19 | [Statistical Inference](#week-3-statistical-inference) |
|  4 | 05/27/19 | [Capstone 1](#week-4-unit-1-capstone) |
|  5 | 06/03/19 | [Regression](#week-5-supervised-learning-and-regression) |
|  6 | 06/10/19 | Solo Week |
|  7 | 06/17/19 | [Supervised Learning](#week-7-nonlinear-supervised-learning) |
|  8 | 06/24/19 | [Unsupervised Learning](#week-8-nlp-and-unsupervised-learning)|
|  9 | 07/01/19 | [Capstone 2](#week-9-unit-2-capstone) |
| 10 | 07/08/19 | [Advanced Topics 1](#week-10-advanced-topics-1) |
| 11 | 07/15/19 | [Advanced Topics 2](#week-11-advanced-topics-2) |
| 12 | 07/22/19 | [Capstone 3](#week-12-unit-3-capstone) |
| 13 | 07/29/19 | [Career Week](#week-13-career-week) |

## Other important links
* [Solutions](https://github.com/GalvanizeDataScience/solutions-g92) for warmups, assignments, and assessments will be added to this repository.  If a solution is missing, please bug an instructor!
* [Morning warmup exercises](https://github.com/gschool/dsi-warmups). 
* [Weekly feedback](https://docs.google.com/forms/d/e/1FAIpQLSdg4SE99Cri-9VTGvmaJ2aDsFQGU_ocK7cmJ_-9yGQl_BhOjw/viewform?usp=sf_link) Every Friday you'll be given some time to reflect on the week and be given a chance to let us know how you're doing.  Then let us know how well you think we taught the material.  We'll use your contstructive criticism to adapt as the course proceeds.
* [Previous student capstone projects](https://github.com/gSchool/dsi-project-proposals/blob/master/past_student_projects.md)  Whether you're looking for capstone ideas or resources to help you with your current capstone, take a look here.  The instructor voted most exemplary/helpful ones are marked with an astericks.
* [Pairing](notes/pairing.md): Notes on how to pair program
* [Workflow](notes/workflow.md): Notes on programming workflow
* [Using Git](notes/using_git.md): How to use git with the Galvanize curriculum
* [Google drive for Project Submissions](https://drive.google.com/drive/folders/11kF4hanRIU50rpWLFTh_R7EHb_dr4jtY)

## Capstone Project
Capstone projects allow you to put into practice some of the knowledge you are gaining in the program on projects of your choosing.  They help build your Github portfolio, and give you specific skills to talk about during job interviews. You will submit capstone proposals to the instructors for approval before the capstone weeks begin. Very often capstone 3 builds on work done on capstone 2, and sometimes even capstone 1.

**[Capstone Project Materials](https://github.com/GalvanizeDataScience/course-outline/tree/19-02-DS-SF-g92/projects)**

## Daily Outline
In the weekly tables below, each row represents a day.  Each row information and links on:
* __Day__ Day of the Week
* __Readings__ Readings for the day (to be completed the night before).
* __Repos__ The day's exercise(s). 
* __Lead Instructor__ The instructor who is the point person for the day.
* __Slides__ The day's lecture notes and slides

### Week 1: Programming for Data Science
| Day | Readings | Repos | Lead Instructor | Slides |
|:--:|:-----------------------------------------|:--|:--:|:--:|
| Monday    | [Development Workflow][workflow]<br/>  [Unix Tutorial][r-unix] <br/> [Unix for data science][r-unixfords] <br/> [Pair Programming][pairing]  | [Readiness Assessment][learn0]<br/> [Unix Fundamental][unix] | Elliott/Flora  | [AM][lec-git] <br/> [PM][lec-fun] |
| Tuesday   | [Intro to IPython Notebook][r-intro-nb] <br/> [10 minutes to Pandas][r-10-pandas]<br/> [Pandas Top 10][r-pandas-top] <br/> [EDA with pandas (Extra)][r-eda-pandas]<br/> [Data Wrangling with pandas (Extra)][r-data-wrangling-pandas]<br/> [matplotlib tutorial 1][r-matplot1]<br/> [matplotlib tutorial 2][r-matplot2]| [Pandas][pandas] <br/> [Matplotlib][matplotlib]  | Flora | [AM][lec-pan]<br/>[PM][lec-mat]  |
| Wednesday | [Think Python][r-py15] | [OOP][oop]<br/>[Transformers][transformer]       | Hamid | [AM][lec-oop-am]<br/> [PM][lec-oop-pm]|
| Thursday  | [Linear Algebra and Numpy (precourse)][r-linalg-numpy] <br/> [Linear Algebra Review and Reference][r-linalg-review]| [Numpy][numpy]<br/>[Linear Algebra][linalg] |  Flora         | [AM][lec-lin]<br/>[PM][lec-lin]   |
| Friday    | [Multiprocessing in Python][r-multiproc] <br/> [Intro to Parallel Processes][r-intro-parallel]<br/> [Intro to Threading][r-intro-threading]| [Docker][docker]<br/>[AWS][aws]|  Hamid | [AM][lec-docker] <br/>[PM][lec-aws] |

--

### Week 2: Big Data
| Day | Readings | Repos | Lead Instructor | Slides |
|:--:|:-----------------------------------------|:--|:--:|:--:|
| Monday    |[Introduction to Algorithms][r-intro-alg](ch 2, pg 16-37) | [Assessment 1][learn0]<br/>[Algorithmic Complexity][big-o] |  Flora  | [AM][lec-bigo] |
| Tuesday   |[Little book of MongoDB][r-mongo] <br/> [Basic Web Scaping][r-web-scraping] | [Mongo DB][mongodb]<br/>[Web Scraping][webscraping]                                       |  Hamid  | [AM][lec-web] |
| Wednesday |[SQLZOO (tutorial: 1-9)][r-sqlzoo] <br/> [Visual Explanation of Joins][r-sql-join] | [SQL][sql]<br>[Python SQL][py-sql]                                                           |  Hamid  | [AM][lec-sql]<br/>[PM][lec-sql-python] |
| Thursday  |[Learning Spark ][r-spark](ch 1--2, pg 1--22) <br/> Optional: [Learning Spark][r-spark] (ch 11: MLlib, pg 183--212)| [Spark RDDs][rdds]<br/>[Spark SQL][dfs]                                         |  Flora  | [AM][lec-spark-intro] <br/> [PM][lec-spark-df] |
| Friday    || [Spark EDA Case Study][c2.5.1]     |  Hamid/Flora/Elliott   |  |

--

### Week 3: Statistical Inference
| Day | Readings | Repos | Lead Instructor | Slides |
|:--:|:-----------------------------------------|:--|:--:|:--:|
| Monday   | [Review of Probability Theory][r-prob] | [Assessment 2][learn0]<br/>[Probability][prob]<br/>[Binomial Tests][binom]        |  Flora  | [AM][lec-prob]<br/>[PM][lec-binom] |
| Tuesday  | [Bootstrapping Intro][r-bootstrap] | [Sampling Distributions][sampling]<br/>[Law of Large Numbers][lln]  |  Flora  | [AM][lec-sampling]<br/>[PM][lec-tlln] |
| Wednesday| [Central Limit Theorem][r-clt] <br/> [MLE][r-mle] | [Central Limit Theorem][clt]<br/>[Maximum Likelihood Estimation][mle] |  Hamid  | [AM][lec-clm]<br/>[PM][lec-mm] |
| Thursday | [z-test VS t-test][r-ztest] <br/> [Hypothesis Testing][r-hypo] <br/> [Power Analysis][r-power]| [Hypothesis Testing][hyp]<br/>[Power Calculation][c3.4.2]         |  Hamid  | [AM][lec-hypothesis]<br/>[PM][lec-power] |
| Friday   | | [Data Products][132.0]</br> Discuss and kickoff capstone 1            | Elliott   | [Lecture Repository][132.0] |


--

### Week 4: Unit 1 Capstone 
| Day  | Repos | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|
| Monday    | Holiday (Memorial Day)                      |  -  | - |
| Tuesday   | [Assessment 3][learn0]<br/> Group Check-in <br/> Continue to Capstone |  -  | - |
| Wednesday | Group Check-in <br/> Back to Work! | - | - |
| Thursday  | Group Check-in <br/> MORE WORK!!!! | - | - |
| Friday    | Group Check-in <br/> Deliveriables by 5PM | - | - |

--

### Week 5: Supervised Learning and Regression
| Day |  Readings | Repos | Lead Instructor | Slides |
|:--:|:--|:--|:--:|:--:|
| Monday | [kNN][r-knn] <br/> Optional: [Machine Learning in Action][r-mlia] (2.1, pg 18-24)] <br/> [Bias-Variance Tradeoff][r-bias], [Cross-Validation][r-cv] <br/> [StatLearning][r-islr]: Cross Validation(5-5.1.4, pg 175-184)| [KNN][c5.1.1]<br/>[Cross Validation][c5.1.2] | Lori/Flora | [AM][lec-knn] <br/> [PM][lec-cv] |
| Tuesday | [StatLearning][r-islr]: Linear Regression cont'd] (3.3-3.4, pg 82-104) <br/>[Practical Regression][r-prac-reg] |  [Predictive Linear Regression][c5.2.1] |  Hamid  | [slides][-] |
| Wednesday | [Regularized Regression][r-regu] <br/> [StatLearning: Shrinkage Methods][r-islr] (6.2, pg 214-228) (optional: pg 203-214)  |  [Regularized Regression][c5.3.1]<br/>[Inferential Regression][c5.3.2] |  Flora  | [slides][-] |
| Thursday | [StatLearning][r-islr]: Classification (4-4.4, pg 127-137) <br/> [Machine Learning in Action][r-mlia] (section 7.7, pg 142-148) | [Logistic Regression][c5.4.1]<br/>[Classification Measures of Effectiveness][c5.4.2] |  Hamid  | [slides][-] |
| Friday | | [Regression Case Study][c5.5.1] |  Hamid/Elliott  | [slides][-] |


--
### Week 6: Solo Week
Your priorities this week:
<ul>
<li>Study any material from the previous weeks.</li>
<li>Collect data for upcoming capstones</li>
<li>Recharge for the 2nd half of the course</li>
</ul>

--

### Week 7: Nonlinear Supervised Learning
| Day | Repos | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|
| Monday | [Assessment 4][learn0]<br/>[Search Trees][c6.1.1]<br/>[Decision Trees][c6.1.2] | Hamid | [slides][-] |
| Tuesday |  [Random Forests][c6.2.1] |  Hamid   | [slides][-] |
| Wednesday |  [Gradient Boosted Regressors][c6.3.1]<br/>[Gradient Boosted Classifiers][c6.3.2] |  Flora | [slides][-] |
| Thursday | [Gradient Decent][c6.4.1]<br/>[Basic Neural Networks][c6.4.2] |  Flora  | [slides][-] |
| Friday | [Supervised Learning Case Study][c6.5.1]  |  Hamid/Flora | [slides][-] |

--

### Week 8: NLP and Unsupervised Learning
| Day | Repos | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|
| Monday | [Assessment 5][learn0]<br/>[NLP Intro][-]<br/>[Text Classification][-] | Hamid | [slides][-] |
| Tuesday |  [PCA][-]<br/>[SVD][-] |  Hamid   | [slides][-] |
| Wednesday |  [Clustering][-]<br/>[NMF][-] |  Flora  | [slides][-] |
| Thursday | [Graph Distance][-]<br/>[Graph Communities][-] |  Flora  | [slides][-] |
| Friday | [NLP Case Study][-] |  Hamid/Flora | [slides][-] |

--

### Week 9: Unit 2 Capstone 
| Day | Repos | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|
| Monday | [Assessment 6][learn0]<br/> Discuss and kickoff capstone 2 | - | [slides][-] |
| Tuesday |  Group Check-in <br/> Back to work |  -  | - |
| Wednesday | Capstone Presentations PM | - | - |
| Thursday |  Holiday (Independence Day) | - | - |
| Friday | Holiday (Independence Day) | - | - |

--

### Week 10: Advanced Topics 1
| Day | Repos | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|
| Monday | [Bayesian Inference][-]<br/>[Bayesian Coin Flipping][-] | Hamid | [slides][-] |
| Tuesday |  [Reinforcement Learning][-]<br/>[Multi-Armed Bandit][-] |  Hamid  | [slides][-] |
| Wednesday |  [Similarity Based Recommenders][-]<br/>[Content Based Recommenders][-] |  Flora  | [slides][-] |
| Thursday | [Implicit Recommenders][-] |  Flora  | [slides][-] |
| Friday | [Recommender Case Study][-]  |  Hamid/Flora  | [slides][-] |

--

### Week 11: Advanced Topics 2
| Day | Repos | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|
| Monday | [Image Analysis][-]<br/>[CNNs][-] | Flora | [slides][-] |
| Tuesday | [Fraud Case Study (day 1)][-] |  -  | [slides][-] | 
| Wednesday | [Fraud Case Study (day 2)][-] |  -  | [slides][-] | 
| Thursday | [Sequence Analysis][-]<br/>[RNN/LSTM][-]<br/> Capstone III |  Hamid   | [slides][-] |
| Friday | [Autoencoding/Word Embeddings/Text Classification][-]<br/> |  Hamid  | [slides][-] |

--

### Week 12: Unit 3 Capstone
| Day | Repos | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|
| Monday | group check-in <br/> Work | - | [slides][-] |
| Tuesday | group check-in <br/> Work   |  -   | [slides][-] |
| Wednesday | Work <br/> Code freeze (EOD)  |  -  | [slides][-] |
| Thursday | Practice |  -  | [slides][-] |
| Friday | Practice |  -  | [slides][-] |

--

### Week 13: Career Week
| Day | Repos | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|
| Monday | Demo Day | - | [slides][-] |
| Tuesday | Caereer's Week  |  -   | [slides][-] |
| Wednesday | Caereer's Week  |  -  | [slides][-] |
| Thursday | Caereer's Week |  -  | [slides][-] |
| Friday | Caereer's Week <br/> Graduation |  -  | [slides][-] |

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

<!-- Lecture Repos -->
<!-- Week 1 -->
[lec-git]:https://github.com/gSchool/dsi-week-zero/blob/master/day-1-git-functions-testing/am_git-unix/intro_git_lec.md
[lec-fun]:https://github.com/gSchool/DSI_Lectures/tree/master/fundamentals
[lec-pan]:https://github.com/GalvanizeDataScience/lectures/tree/SF/pandas
[lec-mat]:https://github.com/GalvanizeDataScience/lectures/tree/SF/matplotlib
[lec-lin]:https://github.com/GalvanizeDataScience/lectures/tree/SF/
[lec-oop-am]:https://github.com/GalvanizeDataScience/lectures/blob/SF/oop/oop_am.pdf
[lec-oop-pm]:https://github.com/GalvanizeDataScience/lectures/tree/SF/oop/oop_pm
[lec-docker]:https://github.com/GalvanizeDataScience/lectures/blob/SF/docker/docker.pptx
[lec-aws]:https://github.com/GalvanizeDataScience/lectures/tree/SF/aws

<!-- Week 2 -->
[lec-bigo]:https://github.com/GalvanizeDataScience/lectures/tree/SF/big_o
[lec-web]:https://github.com/GalvanizeDataScience/lectures/tree/SF/web_scraping
[lec-sql]:https://github.com/GalvanizeDataScience/lectures/tree/SF/sql
[lec-sql-python]:https://github.com/GalvanizeDataScience/lectures/tree/SF/sql_python
[lec-spark-intro]:https://github.com/GalvanizeDataScience/lectures/tree/SF/spark/spark_intro_lecture.ipynb
[lec-spark-df]:https://github.com/GalvanizeDataScience/lectures/tree/SF/spark/spark_df_lecture.ipynb

<!-- Week 3 -->
[lec-prob]:https://github.com/GalvanizeDataScience/lectures/tree/SF/probability
[lec-binom]:https://github.com/GalvanizeDataScience/lectures/tree/SF/binomial_test
[lec-sampling]:https://github.com/GalvanizeDataScience/lectures/tree/SF/sampling_distribution
[lec-tlln]:https://github.com/GalvanizeDataScience/lectures/tree/SF/the_law_of_large_numbers
[lec-clm]:https://github.com/GalvanizeDataScience/lectures/tree/SF/central_limit_theorem
[lec-mm]:https://github.com/GalvanizeDataScience/lectures/tree/SF/maximum_likelihood
[lec-hypothesis]:https://github.com/GalvanizeDataScience/lectures/tree/SF/hypothesis_testing
[lec-power]:https://github.com/GalvanizeDataScience/lectures/tree/SF/statistical_power

<!-- Week 5 -->
[lec-knn]:https://github.com/GalvanizeDataScience/lectures/tree/SF/knn
[lec-cv]:https://github.com/GalvanizeDataScience/lectures/tree/SF/cross_validation

<!-- Assignments -->
<!-- Week 1 -->
[unix]: https://github.com/GalvanizeDataScience/unix
[pandas]: https://github.com/GalvanizeDataScience/pandas
[matplotlib]: https://github.com/GalvanizeDataScience/matplotlib
[oop]: https://github.com/GalvanizeDataScience/oop
[transformer]:https://github.com/GalvanizeDataScience/transformers
[linalg]: https://github.com/GalvanizeDataScience/linear-algebra
[numpy]: https://github.com/GalvanizeDataScience/numpy
[docker]: https://github.com/GalvanizeDataScience/docker
[aws]: https://github.com/GalvanizeDataScience/aws

<!-- Week 2 -->
[big-o]: https://github.com/GalvanizeDataScience/algorithmic-complexity
[c2.1.2]: https://github.com/GalvanizeDataScience/data-structures
[sql]: https://github.com/GalvanizeDataScience/sql
[py-sql]: https://github.com/GalvanizeDataScience/sql-python
[mongodb]: https://github.com/GalvanizeDataScience/mongo-db
[webscraping]: https://github.com/GalvanizeDataScience/web-scraping
[rdds]: https://github.com/GalvanizeDataScience/spark-rdds
[dfs]: https://github.com/GalvanizeDataScience/spark-dfs
[c2.5.1]:https://github.com/GalvanizeDataScience/Spark-Case-Study/tree/g92

<!-- Week 3 -->
[prob]:https://github.com/GalvanizeDataScience/probability-distributions
[binom]:https://github.com/GalvanizeDataScience/binomial-tests
[sampling]: https://github.com/GalvanizeDataScience/sampling-distributions-dev/blob/master/assignment.md
[lln]: https://github.com/GalvanizeDataScience/law-of-large-numbers
[clt]:https://github.com/GalvanizeDataScience/central-limit-theorem-dev/blob/master/assignment.md
[mle]:https://github.com/GalvanizeDataScience/maximum-likelihood
[hyp]: https://github.com/GalvanizeDataScience/hypothesis-testing-dev/blob/master/assignment.md
[c3.4.2]: https://github.com/GalvanizeDataScience/statistical-power
[132.0]:  https://github.com/Esaslow/FlaskWebsite



<!-- Week 4 -->


<!-- Week 5 -->
[c5.1.1]: https://github.com/GalvanizeDataScience/knn
[c5.1.2]: https://github.com/GalvanizeDataScience/cross-validation/tree/knn
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

<!-- Assessments -->
<!-- Week 1 -->
[a0]: https://github.com/gschool/dsi-assessment-day1
[learn0]: https://learn-2.galvanize.com/cohorts/858

<!-- Readings -->
<!-- Week 1 -->
[workflow]: notes/workflow.md
[pairing]: notes/pairing.md
[r-unix]:http://www.ee.surrey.ac.uk/Teaching/Unix/
[r-unixfords]:http://www.gregreda.com/2013/07/15/unix-commands-for-data-science/
[r-py15]:http://www.greenteapress.com/thinkpython/html/thinkpython016.html
[r-intro-nb]:https://nbviewer.jupyter.org/github/jvns/pandas-cookbook/blob/master/cookbook/A%20quick%20tour%20of%20IPython%20Notebook.ipynb
[r-10-pandas]:http://pandas.pydata.org/pandas-docs/stable/10min.html
[r-pandas-top]:http://manishamde.github.io/blog/2013/03/07/pandas-and-python-top-10/
[r-eda-pandas]:http://nbviewer.ipython.org/github/cs109/content/blob/master/labs/lab3/lab3full.ipynb
[r-data-wrangling-pandas]:http://nbviewer.ipython.org/github/cs109/content/blob/master/lec_04_wrangling.ipynb
[r-matplot1]:http://matplotlib.org/users/pyplot_tutorial.html
[r-matplot2]:https://matplotlib.org/users/artists.html
[r-linalg-numpy]:https://github.com/gSchool/precourse/blob/master/Chapter_2_Linear_Algebra/notes.md
[r-linalg-review]:http://cs229.stanford.edu/section/cs229-linalg.pdf
[r-multiproc]:https://www.youtube.com/watch?v=X2mO1O5Nuwg
[r-intro-parallel]:http://sebastianraschka.com/Articles/2014_multiprocessing.html
[r-intro-threading]:http://pymotw.com/2/threading/

<!-- Week 2 -->
[r-intro-alg]:http://ressources.unisciel.fr/algoprog/s00aaroot/aa00module1/res/%5BCormen-AL2011%5DIntroduction_To_Algorithms-A3.pdf
[r-mongo]:http://openmymind.net/mongodb.pdf
[r-web-scraping]:https://medium.freecodecamp.org/how-to-scrape-websites-with-python-and-beautifulsoup-5946935d93fe
[r-sqlzoo]:http://sqlzoo.net/wiki/Main_Page
[r-sql-join]:http://blog.codinghorror.com/a-visual-explanation-of-sql-joins/
[r-spark]:https://drive.google.com/file/d/0B1cm3fV8cnJwc2ZnMFJmT2RLOXM/view?usp=sharing

<!-- Week 3 -->
[r-prob]:http://cs229.stanford.edu/section/cs229-prob.pdf
[r-clt]:https://www.khanacademy.org/math/ap-statistics/sampling-distribution-ap/sampling-distribution-mean/v/central-limit-theorem
[r-mle]:https://www.youtube.com/watch?v=I_dhPETvll8
[r-ztest]:https://www.youtube.com/watch?v=5ABpqVSx33I
[r-hypo]:https://www.youtube.com/watch?v=-FtlH4svqx4
[r-power]:https://www.youtube.com/watch?v=lHI5oEgNkrk
[r-bootstrap]:https://www.youtube.com/watch?v=_nhgHjdLE-I


<!-- Week 4 -->
[r-knn]:https://learn.galvanize.com/cohorts/1341/units/8278
[r-mlia]:https://drive.google.com/file/d/0B1cm3fV8cnJwcUNWWnFaRWgwTDA/view?usp=sharing
[r-bias]:https://learn.galvanize.com/cohorts/1341/units/8274
[r-cv]:https://learn.galvanize.com/cohorts/1341/units/8275
[r-regu]:https://learn.galvanize.com/cohorts/1341/units/8276
[r-islr]:http://www-bcf.usc.edu/~gareth/ISL/ISLR%20Sixth%20Printing.pdf
[r-prac-reg]:https://cran.r-project.org/doc/contrib/Faraway-PRA.pdf
