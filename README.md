# Welcome 

Welcome to the Galvanize Data Science Immersive Program! On this page you'll find information you about the program as a whole as well as links to daily readings and assignments.  You'll be working with this page everyday; please bookmark it in your web browser. 


#  Weekly overview
The Data Science Immersive (DSI) has 8 instructional weeks, 3 capstone weeks, and the final showcase/career week.  Most instructional weeks begin with a 1 hour assessment on Monday and end with a group case study on Friday. 

The capstone weeks are reserved for your capstone projects (see below).  You will scrum with your peers during this time, participate in mock job interiews, and at the end of the week present your project to your peers and instructors (capstones 1 & 2), or to the data science community on a demo day (capstone 3).

The final week is reserved for capstone III, demo day, completing Career Services deliverables, mock interviews, and graduating.

To jump to a week of interest, click on the link. 

| Week | Date | Topic |
| --- | --- | --- |
| 1 | 12/02/19 | [Programming](#week-1-programming-for-data-science) |
| 2 | 12/09/19 | [Big Data](#week-2-big-data) |
| 3 | 12/16/19 | [Statistical Inference](#week-3-statistical-inference) |
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
* [Morning Warmups](https://github.com/GalvanizeDataScience/morning-warmups).
* [Solutions](https://github.com/GalvanizeDataScience/solutions-g109) for warmups, assignments, and assessments will be added to this repository.  If a solution is missing, please bug an instructor!
* [Weekly feedback (TBF)]() Every Friday you'll be given some time to reflect on the week and be given a chance to let us know how you're doing.  Then let us know how well you think we taught the material.  We'll use your contstructive criticism to adapt as the course proceeds.
* [Previous student capstone projects](https://github.com/GalvanizeDataScience/project-proposals/blob/master/past_student_projects.md)  Whether you're looking for capstone ideas or resources to help you with your current capstone, take a look here.  The instructor voted most exemplary/helpful ones are marked with an astericks.

## Capstone Project
Capstone projects allow you to put into practice some of the knowledge you are gaining in the program on projects of your choosing.  They help build your Github portfolio, and give you specific skills to talk about during job interviews. You will submit capstone proposals to the instructors for approval before the capstone weeks begin. Very often capstone 3 builds on work done on capstone 2, and sometimes even capstone 1.

## Daily Outline
In the weekly tables below, each row represents a day.  Each row information and links on:
* __Day__ Day of the Week
* __Readings__ Readings for the day (to be completed the night before).
* __Repos__ The day's exercise(s). 
* __Lead Instructor__ The instructor who is the point person for the day.
* __Slides__ The day's lecture notes and slides

### Week 1: Programming for Data Science
| Day | Readings | Repos | Lead | Slides |
|:--:|:-----------------------------------------|:--|:--:|:--:|
| Monday | [**Register for AWS credit**][r-aws]<br/>[Development Workflow][workflow]<br/>  [Unix Tutorial][r-unix] <br/> [Unix for data science][r-unixfords] <br/> [Pair Programming][pairing] <br/> [**Git Remote**][gitremote] | [Readiness Assessment][learn0]<br/> [Unix Fundamental][unix]<br/>[Git][git] | Flora  | [AM][lec-fun]<br/>[PM][lec-git] |
| Tuesday  | [Linear Algebra and Numpy (precourse)][r-linalg-numpy] <br/> [Linear Algebra Review and Reference][r-linalg-review]| [Numpy][numpy]<br/>[Linear Algebra][linalg] |  Flora | [AM][lec-numpy]<br/>[PM][lec-lin]   |
| Wednesday | [10 minutes to Pandas][r-10-pandas]<br/> [Pandas Top 10][r-pandas-top] <br/> [EDA with pandas (Extra)][r-eda-pandas]<br/> [Data Wrangling with pandas (Extra)][r-data-wrangling-pandas]<br/> [matplotlib tutorial 1][r-matplot1]<br/> [matplotlib tutorial 2][r-matplot2]| [Pandas][pandas] <br/> [Matplotlib][matplotlib]  | Skylar | [AM][lec-pan]<br/>[PM][lec-mat]  |
| Thursday | [Think Python][r-py15] <br/> [**Python code style**][r-python]  | [OOP][oop]<br/>[Transformers][transformer]       | Mark | [AM][lec-oop-am]<br/> [PM][lec-oop-pm]|
| Friday | - | [EDA Case Study][cs-eda] | - | - | 


--

### Week 2: Big Data
| Day | Readings | Repos | Lead | Slides |
|:--:|:-----------------------------------------|:--|:--:|:--:|
| Monday    | [Multiprocessing in Python][r-multiproc] <br/> [Intro to Parallel Processes][r-intro-parallel]<br/> [Intro to Threading][r-intro-threading] <br> [**Docker Getting Started**][r-docker](Do not re-install Docker!)<br>[**About AWS**][r-about-AWS]<br>[**Getting Started on AWS**][r-start-AWS] | [Assessment 1][learn0]<br/> [Docker][docker]<br/>[AWS][aws] |  Mark  |  [AM][lec-docker]<br>[PM][lec-aws]|
| Tuesday |[SQLZOO (tutorial: 1-9)][r-sqlzoo] <br/> [Visual Explanation of Joins][r-sql-join] | [SQL][sql]<br>[Python SQL][py-sql] |  Skylar  | [AM][lec-sql]<br/>[PM][lec-sql-python] |
| Wednesday   |[Little book of MongoDB][r-mongo] <br/> [Basic Web Scaping][r-web-scraping] | [Mongo DB][mongodb]<br/>[Web Scraping][webscraping] |  Mark  | [AM][lec-web] |
| Thursday  |[Learning Spark ][r-spark](ch 1--2, pg 1--22) <br/> Optional: [Learning Spark][r-spark] (ch 11: MLlib, pg 183--212)| [Spark RDDs][rdds]<br/>[Spark SQL][dfs] |  Flora  | [AM][lec-spark-intro]<br/>[PM][lec-spark-df] |
| Friday    | - | [Spark EDA Case Study][cs-spark]     |  -   |  |

--

### Week 3: Statistical Inference
| Day | Readings | Repos | Lead  | Slides |
|:--:|:-----------------------------------------|:--|:--:|:--:|
| Monday  | [Review of Probability Theory][r-prob] | [Assessment 2][learn0]<br/>[Probability][prob]<br/>[Binomial Tests][binom]        |  Flora  | [AM][lec-prob]<br/>[PM][lec-binom] |
| Tuesday | [Bootstrapping Intro][r-bootstrap] | [Sampling Distributions][sampling]<br/>[Law of Large Numbers][lln]  |  Skylar  | [AM][lec-sampling]<br/>[PM][lec-tlln] |
| Wednesday | [Central Limit Theorem][r-clt] <br/> [MLE][r-mle] | [Central Limit Theorem][clt]<br/>[Maximum Likelihood Estimation][mle] |  Skylar  | [AM][lec-clm]<br/>[PM][lec-mm] |
| Thursday | [z-test VS t-test][r-ztest] <br/> [Hypothesis Testing][r-hypo] <br/> [Power Analysis][r-power]| [Hypothesis Testing][hyp]<br/>[Power Calculation][power]         |  Flora  | [AM][lec-hypothesis]<br/>[PM][lec-power] |
| Friday | -  | [Bayesian Inference][bayes-inf]<br/>[Bayesian Testing][bayes-testing] | Mark | [AM][lec-bys]<br/>[PM][lec-bysabtest]  | 

--

### Week 4: Unit 1 Capstone 
| Day  | Repos | Lead | Slides |
|:--:|:--|:--:|:--:|
| Monday    | [Assessment 3][learn0]<br/> Discuss and kickoff capstone 1 | - | - |
| Tuesday   | Group Check-in <br/> Continue to Capstone |  -  | - |
| Wednesday | Group Check-in <br/> Back to Work! | - | - |
| Thursday  | Group Check-in <br/> MORE WORK!!!! | - | - |
| Friday    | Presentation at 3PM | - | - |

--

### Week 5: Supervised Learning and Regression
| Day |  Readings | Repos | Lead | Slides |
|:--:|:--|:--|:--:|:--:|
| Monday | [KNN][r-knn] <br/> Optional: [Machine Learning in Action][r-mlia] (2.1, pg 18-24)] <br/> [Bias-Variance Tradeoff][r-bias], [Cross-Validation][r-cv] <br/> [StatLearning][r-islr]: Cross Validation(5-5.1.4, pg 175-184)| [KNN][c5.1.1]<br/>[Cross Validation][c5.1.2] | Flora | [AM][lec-knn] <br/> [PM][lec-cv] |
| Tuesday | [StatLearning][r-islr]: Linear Regression cont'd] (3.3-3.4, pg 82-104) <br/>[Practical Regression][r-prac-reg]<br/>[Machine Learning in Action][r-mlia](5, pg 83--90)  | [Predictive Linear Regression][pred-lin-reg]<br/>[Gradient Descent][c6.4.1] |  Skylar  | [AM][lec-lin-reg]<br/>[PM][lec-grad-des] |
| Wednesday | [Regularized Regression][r-regu] <br/> [StatLearning: Shrinkage Methods][r-islr] (6.2, pg 214-228) (optional: pg 203-214)  |  [Regularized Regression][reg-reg]<br/>[Inferential Regression][inf-reg] |  Mark  | [AM][lec-regularization]<br/>[PM][lec-inf] |
| Thursday | [StatLearning][r-islr]: Classification (4-4.4, pg 127-137) <br/> [Machine Learning in Action][r-mlia] (section 7.7, pg 142-148) | [Logistic Regression][log-reg]<br/>[Classification Measures of Effectiveness][decision-rules] |  Skylar  | [AM][lec-log-reg] |
| Friday | | [Regression Case Study][cs-reg] |  -  | - |

--
  


### Week 6: Nonlinear Supervised Learning
| Day | Readings |  Repos | Lead | Slides |
|:--:|:----|:--|:--:|:--:|
| Monday | Holiday (MLK) | - | - | - | 
| Tuesday |[Introduction to Algorithms][r-intro-alg](ch 2, pg 16-37)<br/>[Decision Trees][r-dec-tree] <br/> [Machine Learning in Action][r-mlia] (section 3.1, pg 37--48) <br/> Optional: [Recursion][r-recursion] <br/> Optional: [StatLearning: trees][r-islr](8.1 pg 303--316) <br/> [Decision Tree Visual Explanation][r-dec-tree-visual] <br/> | [Assessment 4][learn0]<br/>[Algorithmic Complexity][big-o]<br/>[Decision Trees][c6.1.2] | Skylar | [AM][lec-bigo] <br/>[PM][lec-dt] |
| Wednesday | [StatLearning: ensembles][r-islr] (8.2, pg 316--321) | [Random Forests Implementation][c6.2.1]<br/>[Random Forests Application][c6.2.2] |  Flora   | [AM][lec-bg]<br/>[PM][lec-rf] |
| Thursday |[StatLearning][r-islr] (8.2.3, pg 321--324) <br/> Optional (more depth)[Elements of Stats Learning][r-esl](10--10.6, pg 337--350)  | [Gradient Boosted Regressors][c6.3.1]<br/>[Gradient Boosted Classifiers][c6.3.2] |  Mark | [AM][lec-boosting] |
| Friday | - | [Supervised Learning Case Study][c6.5.1]  |  - | - |


--

### Week 7: NLP and Unsupervised Learning
| Day | Readings | Repos | Lead | Slides |
|:--:|:-------:|:--|:--:|:--:|
| Monday | Text feature extraction (tf-idf) [I][r-tfe-1], [II][r-tfe-2], [III][r-tfe-3]<br/> [Scalability of Semantic Analysis in NLP][r-sem-ana] (Sections 1.1--1.7) <br/> [NLP in Python][r-nlp](3.6, pg 107-108) | [Assessment 5][learn0]<br/>[NLP Intro][nlp]<br/>[Text Classification][txt-clf] | Mark | [AM][lec-nlp] |
| Tuesday | [StatsLearning][r-islr] (ch 10.2 pg 374-385) <br/> [Mining Massive Datasets][r-mmd](ch 11) |  [PCA][pca]<br/>[SVD][svd] |  Skylar   | [AM][lec-pca] <br/> [PM][lec-svd]|
| Wednesday | [StatsLearning][r-islr](pg 385--400) <br/> [NMF in Python][r-nmf-py] | [Clustering][clustering]<br/>[NMF][nmf] |  Mark  | [AM][lec-clustering] <br/> [PM][lec-nmf] |
| Thursday |[Forecasting: principles and practice][r-forecasting](ch 1, 2, & 6-8) <br/> [Time Series Analysis and Its Applications][r-time-series] (ch 1-3) <br/> [ARIMA models in Python][r-arima]| [Sequence Analysis][seq-ana] |  Flora   | [AM][lec-time-series] |
| Friday | - | [NLP Case Study][nlp-case-study] | - | - |


--

### Week 8: Unit 2 Capstone 
| Day |  Repos | Lead | Slides |
|:--:|:--|:--:|:--:|
| Monday | [Assessment 6][learn0] <br/> Capstone 2 Kick-Off <br/> Work | - | - |
| Tuesday | Group Check-in <br/> Back to work |  -  | - |
| Wednesday | Group Check-in  <br/> Back to work | - | - |
| Thursday | Group Check-in  <br/> Back to work| - | - |
| Friday | Capstone Presentations PM | - | - |

--

### Week 9: Advanced Topics 1
| Day | Readings |Repos | Lead | Slides |
|:--:|:-------|:--|:--:|:--:|
| Monday | [Andrew Ng Notes][r-ng-note] (pg 1--7, 16--19) <br/> [Neural Network Basics (Part 1--3)][r-nn] | [Basic Neural Networks][c6.4.2] | Flora | [AM][lec-nn]| 
| Tuesday | [Bayesian AB and Multi-Arm Bandit][r-mab] | [Multi-Armed Bandit][mab] <br/>[Markov-Chain Monte Carlo][mcmc] |  Skylar | [AM][lec-mab] <br/> [PM][lec-mcmc] |
| Wednesday | [Machine Learning in Action][r-mlia](14.4--14.5, pg 286--295) <br/> [Mining Massive Datasets][r-mmd](9.1--9.2, pg 307--320)|  [Content Based Recommenders][cont-recom]<br/>[Similarity Based Recommenders][sim-recom] |  Mark  | [AM][lec-recom] |
| Thursday | [Mining Massive Datasets][r-mmd](9.4--9.5) <br/> [Matrix Factorization Techniques for Recommender Systems][r-matrix-recom] <br/> [Graphlab: Choosing a recommender][r-graphlab]| [Matrix Factorization Recommenders][fac-recom] <br/> [Recommender Case Study][recom-case-study] |  Skylar  | [AM][lec-recom] |
| Friday | -  | [Recommender Case Study][recom-case-study]  |  -  | - |


--

### Week 10: Advanced Topics 2
| Day | Readings | Repos | Lead | Slides |
|:--:|:-------|:--|:--:|:--:|
| Monday | Holiday (president) | - | - | - | 
| Tuesday | [ConvNets][r-convnets] <br/> [Transfer Learning][r-transfer]| [ConvNets][convnets] <br/> [transfer learning][transfer] | Flora | [AM][lec-convnets] |
| Wednesday | [Auto-Encoders][r-autoencoder] <br/> [Word Embeddings][r-word-embedding] | [RNNs][rnns]<br/>[Autoencoding/Word Embeddings/Text Classification][autoencode] |  Mark   | [AM][lec-rnn]<br/>[PM][lec-autoencoder] |
| Thursday | [Social Network Analysis][r-sna](ch 2 pg 19--38) <br/> [Mining Massive Datasets][r-mmd] (ch 10.1--10.2 pg 343--356)|[Graphs Introduction and Searching][graphs-searching]<br/>[Graphs Centrality and Communities][graphs-communities] |  Skylar  | [AM][lec-graph] |
| Friday | - | [Fraud Case Study][fraud-case-study]<br/> Kick off Capstone III|  -  | - | 


--

### Week 11: Unit 3 Capstone 
| Day | Repos | Lead | Slides |
|:--:|:--|:--:|:--:|
| Monday | group check-in <br/> Work | - | - |
| Tuesday | group check-in <br/> Work   |  -   | - |
| Wednesday | group check-in <br/> Work  |  -  | - |
| Thursday | group check-in <br/> Work |  -  | - |
| Friday | group check-in <br/> Work |  -  | - |

--

### Week 12: Showcase 
| Day | Readings | Repos | Lead  | Slides |
|:--:|:--:|:--|:--:|:--:|
| Monday |[120 Questions][r-120-Qs](work on these all week) <br/> [Polya’s Problem Solving Techniques][polya]| group check-in <br/> work | - | - |
| Tuesday | [Tackling the takehome][r-takehome] |  Career's Week <br/> Code freeze (EOD) |  -   | - |
| Wednesday | [Business Analytics][r-business] | Presentations <br/>    Career's Week  |  -  | - |
| Thursday | [Model Comparison Guide][r-model-comp] | Career's Week |  -  | - |
| Friday | - | Career's Week <br/> Graduation |  -  | - |


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
[lec-git]:https://github.com/GalvanizeDataScience/lectures/tree/LA/git
[lec-fun]:https://github.com/GalvanizeDataScience/lectures/tree/LA/unix
[lec-pan]:https://github.com/GalvanizeDataScience/lectures/tree/LA/pandas
[lec-mat]:https://github.com/GalvanizeDataScience/lectures/tree/LA/matplotlib
[lec-numpy]:https://github.com/GalvanizeDataScience/lectures/tree/LA/numpy
[lec-lin]:https://github.com/GalvanizeDataScience/lectures/tree/LA/linear-algebra
[lec-oop-am]:https://github.com/GalvanizeDataScience/lectures/tree/LA/oop/
[lec-oop-pm]:https://github.com/GalvanizeDataScience/lectures/tree/LA/oop/
[lec-docker]:https://github.com/GalvanizeDataScience/lectures/tree/LA/docker/
[lec-aws]:https://github.com/GalvanizeDataScience/lectures/tree/LA/aws
[cs-eda]:https://github.com/GalvanizeDataScience/Pandas-EDA-Case-Study

<!-- Week 2 -->
[lec-bigo]:https://github.com/GalvanizeDataScience/lectures/tree/LA/big-o
[lec-bst]:https://github.com/GalvanizeDataScience/lectures/tree/LA/search-trees
[lec-web]:https://github.com/GalvanizeDataScience/lectures/tree/LA/web-scraping
[lec-sql]:https://github.com/GalvanizeDataScience/lectures/tree/LA/sql
[lec-sql-python]:https://github.com/GalvanizeDataScience/lectures/tree/LA/sql-python
[lec-spark-intro]:https://github.com/GalvanizeDataScience/lectures/blob/LA/spark/spark-rdds.ipynb
[lec-spark-df]:https://github.com/GalvanizeDataScience/lectures/blob/SF/spark/spark-sql.ipynb

<!-- Week 3 -->
[lec-prob]:https://github.com/GalvanizeDataScience/lectures/tree/LA/probability
[lec-binom]:https://github.com/GalvanizeDataScience/lectures/tree/LA/binomial-test
[lec-sampling]:https://github.com/GalvanizeDataScience/lectures/tree/LA/sampling-distribution
[lec-tlln]:https://github.com/GalvanizeDataScience/lectures/tree/LA/the-law-of-large-numbers
[lec-clm]:https://github.com/GalvanizeDataScience/lectures/tree/LA/central-limit-theorem
[lec-mm]:https://github.com/GalvanizeDataScience/lectures/tree/LA/maximum-likelihood
[lec-hypothesis]:https://github.com/GalvanizeDataScience/lectures/tree/LA/hypothesis-testing
[lec-power]:https://github.com/GalvanizeDataScience/lectures/tree/LA/statistical-power

<!-- Week 5 -->
[lec-knn]:https://github.com/GalvanizeDataScience/lectures/tree/LA/knn
[lec-cv]:https://github.com/GalvanizeDataScience/lectures/tree/LA/cross-validation
[lec-lin-reg]:https://github.com/GalvanizeDataScience/lectures/tree/LA/linear-regression
[lec-regularization]:https://github.com/GalvanizeDataScience/lectures/tree/LA/regularized-regression
[lec-inf]:https://github.com/GalvanizeDataScience/lectures/tree/LA/inferential-linear-regression
[lec-log-reg]:https://github.com/GalvanizeDataScience/lectures/tree/LA/logistic-regression/

<!-- Week 7 -->
[lec-dt]:https://github.com/GalvanizeDataScience/lectures/tree/LA/decision-tress
[lec-svm]:https://github.com/GalvanizeDataScience/lectures/tree/LA/svm
[lec-bg]:https://github.com/GalvanizeDataScience/lectures/tree/LA/random-forests
[lec-rf]:https://github.com/GalvanizeDataScience/lectures/tree/LA/random-forests
[lec-boosting]:https://github.com/GalvanizeDataScience/lectures/tree/LA/gradient-boosting
[lec-grad-des]:https://github.com/GalvanizeDataScience/lectures/tree/LA/gradient-descent
[lec-nn]:https://github.com/GalvanizeDataScience/lectures/tree/LA/neural-networks

<!-- Week 8 -->
[lec-nlp]:https://github.com/GalvanizeDataScience/lectures/tree/LA/nlp/
[lec-pca]:https://github.com/GalvanizeDataScience/lectures/tree/LA/pca
[lec-svd]:https://github.com/GalvanizeDataScience/lectures/tree/LA/svd
[lec-clustering]:https://github.com/GalvanizeDataScience/lectures/tree/LA/clustering
[lec-nmf]:https://github.com/GalvanizeDataScience/lectures/tree/LA/nmf
[lec-graph]:https://github.com/GalvanizeDataScience/lectures/tree/LA/graph

<!-- Week 10 -->
[lec-bys]:https://github.com/GalvanizeDataScience/lectures/tree/LA/bayesian-inference
[lec-bysabtest]:https://github.com/GalvanizeDataScience/lectures/tree/LA/bayesian-testing
[lec-mab]:https://github.com/GalvanizeDataScience/lectures/tree/LA/multi-armed-bandit
[lec-mcmc]:https://github.com/GalvanizeDataScience/lectures/tree/LA/mcmc/
[lec-recom]:https://github.com/GalvanizeDataScience/lectures/tree/LA/recommendations
[lec-matrix-recom]:https://github.com/GalvanizeDataScience/lectures/tree/LA/recommendations/matrix-factorization-for-recommendation.ipynb


<!-- Week 11 -->
[lec-convnets]:https://github.com/GalvanizeDataScience/lectures/tree/LA/convnets
[lec-rnn]:https://github.com/GalvanizeDataScience/lectures/tree/LA/rnn
[lec-autoencoder]:https://github.com/GalvanizeDataScience/lectures/tree/LA/autoencoders
[lec-time-series]:https://github.com/GalvanizeDataScience/lectures/tree/LA/time-series

<!-- Assignments -->
<!-- Week 1 -->
[unix]: https://github.com/GalvanizeDataScience/unix
[git]:https://github.com/GalvanizeDataScience/git-intro
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
[cs-spark]:https://github.com/GalvanizeDataScience/spark-case-study/tree/master

<!-- Week 3 -->
[prob]:https://github.com/GalvanizeDataScience/probability-distributions
[binom]:https://github.com/GalvanizeDataScience/binomial-tests
[sampling]: https://github.com/GalvanizeDataScience/sampling-distributions-dev/blob/master/assignment.md
[lln]: https://github.com/GalvanizeDataScience/law-of-large-numbers
[clt]:https://github.com/GalvanizeDataScience/central-limit-theorem-dev/blob/master/assignment.md
[mle]:https://github.com/GalvanizeDataScience/maximum-likelihood
[hyp]: https://github.com/GalvanizeDataScience/hypothesis-testing-dev/blob/master/assignment.md
[power]: https://github.com/GalvanizeDataScience/statistical-power
[132.0]:  https://github.com/Esaslow/FlaskWebsite



<!-- Week 4 -->


<!-- Week 5 -->
[c5.1.1]: https://github.com/GalvanizeDataScience/knn
[c5.1.2]: https://github.com/GalvanizeDataScience/cross-validation/tree/knn
[lin-reg-eda]:https://github.com/GalvanizeDataScience/linear-regression-eda
[pred-lin-reg]:https://github.com/GalvanizeDataScience/predictive-linear-regression
[reg-reg]: https://github.com/GalvanizeDataScience/regularized-regression
[inf-reg]: https://github.com/GalvanizeDataScience/inferential-regression
[log-reg]: https://github.com/GalvanizeDataScience/logistic-regression
[decision-rules]: https://github.com/GalvanizeDataScience/decision-rules
[cs-reg]: https://github.com/GalvanizeDataScience/regression-case-study

<!-- Week 6-->
[c6.1.1]: https://github.com/GalvanizeDataScience/search-trees
[linear-splines]:https://github.com/GalvanizeDataScience/linear-splines
[svm]:https://github.com/gschool/dsi-svm
[c6.1.2]: https://github.com/GalvanizeDataScience/decision-trees
[c6.2.1]: https://github.com/GalvanizeDataScience/random-forests-implementation
[c6.2.2]: https://github.com/GalvanizeDataScience/random-forests-application
[c6.3.1]: https://github.com/GalvanizeDataScience/gradient-boosted-regression
[c6.3.2]: https://github.com/GalvanizeDataScience/gradient-boosted-classification
[c6.4.1]: https://github.com/GalvanizeDataScience/gradient-descent
[c6.4.2]: https://github.com/GalvanizeDataScience/perceptrons/tree/Denver
[c6.5.1]: https://github.com/GalvanizeDataScience/supervised-learning-case-study/

<!-- Week 8 -->
[nlp]:https://github.com/GalvanizeDataScience/nlp
[txt-clf]:https://github.com/GalvanizeDataScience/text-classification
[pca]:https://github.com/GalvanizeDataScience/pca
[svd]:https://github.com/GalvanizeDataScience/svd
[clustering]:https://github.com/GalvanizeDataScience/clustering
[nmf]:https://github.com/GalvanizeDataScience/topicmodeling
[graphs-searching]: https://github.com/GalvanizeDataScience/graphs-searching
[graphs-communities]: https://github.com/GalvanizeDataScience/graphs-communities
[graph]:https://github.com/GalvanizeDataScience/graphs
[nlp-case-study]:https://github.com/GalvanizeDataScience/nlp_case_study
[autoencode]:https://github.com/GalvanizeDataScience/autoencoders/tree/Denver


<!-- Week 9 -->
[bayes-inf]:https://github.com/GalvanizeDataScience/bayes-intro
[bayes-testing]:https://github.com/GalvanizeDataScience/bayes-testing
[mab]:https://github.com/GalvanizeDataScience/multi-armed-bandit
[mcmc]:https://github.com/GalvanizeDataScience/mcmc
[recom-case-study]:https://github.com/GalvanizeDataScience/recommender-case-study

<!-- Week 10 -->
[convnets]:https://github.com/GalvanizeDataScience/convolutional-neural-nets
[transfer]:https://github.com/GalvanizeDataScience/transfer-learning
[image]:https://github.com/GalvanizeDataScience/image-processing/blob/seattle-g91/individual.md
[seq-ana]:https://github.com/GalvanizeDataScience/time-series
[rnns]:https://github.com/GalvanizeDataScience/recurrent-neural-nets
[fraud-case-study]:https://github.com/GalvanizeDataScience/fraud-detection-case-study
[transfer-learning]: https://github.com/GalvanizeDataScience/transfer-learning
[sim-recom]:https://github.com/GalvanizeDataScience/similarity_based_recommenders
[cont-recom]:https://github.com/GalvanizeDataScience/content_based_recommender
[fac-recom]:https://github.com/GalvanizeDataScience/factorization_recommender
[flask]:https://github.com/GalvanizeDataScience/data-products


<!-- Week 11 -->


<!-- Assessments -->
<!-- Week 1 -->
[learn0]: https://learn-2.galvanize.com/cohorts/1505

<!-- Readings -->
<!-- Week 1 -->
[workflow]: notes/workflow.md
[pairing]: notes/pairing.md
[gitremote]:https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes
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
[r-linalg-numpy]:https://github.com/gSchool/dsi-precourse/blob/master/Chapter_2_Linear_Algebra/notes.md
[r-linalg-review]:http://cs229.stanford.edu/section/cs229-linalg.pdf
[r-multiproc]:https://www.youtube.com/watch?v=X2mO1O5Nuwg
[r-intro-parallel]:http://sebastianraschka.com/Articles/2014_multiprocessing.html
[r-intro-threading]:http://pymotw.com/2/threading/
[r-aws]:notes/setup_aws.md
[r-python]:https://docs.python-guide.org/writing/style/#general-concepts 
[r-docker]: https://docs.docker.com/get-started/
[r-start-AWS]: https://aws.amazon.com/start-now/
[r-about-AWS]: https://aws.amazon.com/about-aws/

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
[r-knn]:https://learn-2.galvanize.com/cohorts/1505/blocks/244/content_files/knn/README.md
[r-mlia]:https://drive.google.com/file/d/0B1cm3fV8cnJwcUNWWnFaRWgwTDA/view?usp=sharing
[r-bias]:https://learn-2.galvanize.com/cohorts/1505/blocks/244/content_files/bias-variance/readme.md
[r-cv]:https://learn-2.galvanize.com/cohorts/1505/blocks/244/content_files/cross-validation/readme.md
[r-regu]:https://learn-2.galvanize.com/cohorts/1505/blocks/244/content_files/regularized-regression/readme.md
[r-islr]:http://www-bcf.usc.edu/~gareth/ISL/ISLR%20Sixth%20Printing.pdf
[r-prac-reg]:https://cran.r-project.org/doc/contrib/Faraway-PRA.pdf


<!-- Week 7 --> 
[r-dec-tree]:https://learn-2.galvanize.com/cohorts/1505/blocks/244/content_files/dec_tree/README.md
[r-recursion]:http://interactivepython.org/runestone/static/pythonds/index.html#recursion
[r-recu-prac]:https://github.com/gSchool/dsi-welcome/blob/19-01-DS-SF-g88/readings/recursion
[r-dec-tree-visual]:http://www.r2d3.us/visual-intro-to-machine-learning-part-1/
[r-esl]:https://web.stanford.edu/~hastie/ElemStatLearn/download.html
[r-nn]:https://www.youtube.com/watch?v=bxe2T-V8XRs
[r-ng-note]:http://cs229.stanford.edu/notes/cs229-notes1.pdf


<!-- Week 8 -->
[r-tfe-1]:http://blog.christianperone.com/?p=1589
[r-tfe-2]:http://blog.christianperone.com/?p=1747
[r-tfe-3]:http://blog.christianperone.com/?p=2497
[r-sem-ana]:https://radimrehurek.com/phd_rehurek.pdf
[r-nlp]:http://www.datascienceassn.org/sites/default/files/Natural%20Language%20Processing%20with%20Python.pdf
[r-mmd]:http://infolab.stanford.edu/~ullman/mmds/book.pdf
[r-nmf-py]:http://www.quuxlabs.com/blog/2010/09/matrix-factorization-a-simple-tutorial-and-implementation-in-python/
[r-sna]:http://www.asecib.ase.ro/mps/Social%20Network%20Analysis%20for%20Startups%20[2011].pdf


<!-- Week 9-->
[r-mab]:http://stevehanov.ca/blog/index.php?id=132

<!-- Week 10-->
[r-forecasting]:https://www.otexts.org/fpp
[r-time-series]:https://github.com/GalvanizeDataScience/course-outline/blob/19-02-DS-SF-g92/notes/TimeSeries.pdf
[r-arima]:http://conference.scipy.org/proceedings/scipy2011/pdfs/statsmodels.pdf
[r-matrix-recom]:https://datajobs.com/data-science-repo/Recommender-Systems-%5BNetflix%5D.pdf
[r-graphlab]:https://turi.com/learn/userguide/recommender/choosing-a-model.html

<!-- Week 11-->
[r-autoencoder]:http://ufldl.stanford.edu/tutorial/unsupervised/Autoencoders/
[r-word-embedding]:https://arxiv.org/pdf/1301.3781.pdf
[r-convnets]:https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/
[r-transfer]:https://machinelearningmastery.com/transfer-learning-for-deep-learning/
[r-flask]:http://flask.pocoo.org/
[r-flask-tutorials]:http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world
[r-get-post]:http://www.w3schools.com/tags/ref_httpmethods.asp

<!-- Week 13-->
[r-120-Qs]:https://github.com/GalvanizeDataScience/course-outline/blob/19-02-DS-SF-g92/interview-prep/120_Interview_Questions.pdf
[r-takehome]:https://github.com/GalvanizeDataScience/course-outline/blob/19-02-DS-SF-g92/interview-prep/takehome/take-home-guide.md
[r-model-comp]:https://github.com/GalvanizeDataScience/course-outline/blob/19-02-DS-SF-g92/interview-prep/review/Model_Comparison_Guide.md
[r-business]:https://github.com/GalvanizeDataScience/course-outline/blob/19-02-DS-SF-g92/interview-prep/business/business_analytics_reading.md
[polya]:https://math.berkeley.edu/~gmelvin/polya.pdf
