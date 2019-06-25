# Welcome 

Welcome to the Galvanize Data Science Immersive Program.  On this page, you'll find all the information you need to know about the day to day activities in the program.

# Handy Resources

* [Lecture material](https://github.com/gSchool/DSI_Lectures/) 
  * there's a lot of it, see the readme for tips on downloading it. Don't fork this repo, just clone it
* [Morning warmup exercises](https://github.com/gschool/dsi-warmups)
* [Feedback form](https://docs.google.com/forms/d/e/1FAIpQLSeh2TqggE5jisWBh2coL6KHdEfSelEdP2MaU2DXeTnA-1GsUQ/viewform)
* [Previous student capstone projects](https://github.com/gSchool/dsi-project-proposals/blob/master/past_student_projects.md)
  * [Project proposal tips & schedule](TODO
  * [Project proposal google folder](TODO): make a folder with your name, submit your proposals as a google doc

# Notes

In the notes folder, you'll find these things:

* [Pairing](notes/pairing.md): Notes on how to pair program
* [Using Git](notes/using_git.md): How to use git with the Galvanize curriculum
* [Workflow](notes/workflow.md): Notes on programming workflow
* [Docker Setup](notes/docker_setup.md): how to install & use Docker
* [Docker Setup - Postgres](notes/docker_postgres.md): how to use PostgresSQL with Docker & Python
* [Docker Setup - MongoDB](notes/docker_mongodb.md): how to use MongoDB with Docker & Python
* [Docker Setup - Spark](notes/docker_spark.md): how to use Spark with Docker & Python


# Course Outline
This is the outline for the course.  Each row represents a day, readings are to be completed before class on the given day.

The [nighly readings](notes/readings.md) are maintained in a separate file.  Many students find it useful to read ahead a bit on the weekends.

* __Day:__ Day of the Week
* __Repo:__ The repo contains the day's exercise(s). You should be able to complete this in the time allotted (you will not have access until the day of).
* __Lead Instructor:__ The instructor who is the point person for the day.
* __Slides:__ The day's lecture notes and slides

# Schedule
| Week | Date | Topic |
| --- | --- | --- |
| 0 | 4/29/19 | Week 0 Prep |
| 1 | 5/06/19 | [Programming](#week-1-programming-for-data-science) |
| 2 | 5/13/19 |  [Big Data](#week-2-big-data) |
| 3 | 5/20/19 | [Statistical Inference](#week-3-statistical-inference) |
| 4 | 5/28/19 | [**Capstone 1**](#week-4-unit-1-capstone) |
| 5 | 6/03/19 | [Regression](#week-5-supervised-learning-and-regression) |
| - | 6/10/19 | Solo Week |
| 6 | 6/17/19 | [Supervised Learning](#week-6-nonlinear-supervised-learning) |
| 7 | 6/24/19 | [Unsupervised Learning](#week-7-nlp-and-unsupervised-learning)|
| 8 | 7/01/19 | [**Capstone 2**](#week-8-unit-2-capstone) |
| 9 | 7/08/19 | [Advanced Topics 1](#week-9-advanced-topics-1) |
| 10 | 7/15/19 | [Advanced Topics 2](#week-10-advanced-topics-2) |
| 11 | 7/22/19 | [**Capstone 3**](#week-11-unit-3-capstone) |
| 12 | 7/29/19 | [Career Week](#week-12-career-week) |

## Weekly Structure
During all instructional weeks, every Monday will begin with an assessment.  Assessments are the primary mechanism instructors have to ensure that the material is being absorbed.  The assessments primarily focus on the material from the previous week.

During instructional weeks, every Friday will be a capstone where the material that had been covered during the week will be put to use in a more open ended application of the knowledge.

## Capstones
Capstone projects are designed to be showcases of the diverse skill set that you aquire over this challenging course of study.  In addition to building machine learnign models, capstones should feature fundamental skills like data collection and cleaning (which employers find very attractive).

--

### Week 1: Programming for Data Science
| Day | Topic | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|
| Monday | [Readiness Assessment][a0]<br><br>[Unix Fundamental][c1.1.1] |  Jack  | [Unix][slide-unix] |
| Tuesday |  [Pandas][c1.2.1] <br/> [Matplotlib][c1.2.2] |  Jack  | [Pandas][slide-pandas] <br/> [Matplotlib][slide-matplotlib] |
| Wednesday | [OOP][c1.3.1] |  Brandon  | [OOP][slide-oop]  |
| Thursday |  [Linear Algebra][c1.4.1]<br/>[Numpy][c1.4.2] |  Matt  | [Linear Algebra][slide-linalg] |
| Friday |  [Mongo DB][c1.5.1]<br/>[Web Scraping][c1.5.2] |  Brandon  | [Mongo DB][slide-mongo] <br/> [Web Scraping][slide-webscraping]|

--

### Week 2: Big Data
| Day | Topic | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|
| Monday | [Assessment 1][-]<br/>[Algorithmic Complexity][c2.1.1]<br/>[Data Structures][c2.1.2] |  Brandon  | [Algorithmic Complexity][slides-bigo] |
| Tuesday | [Docker][c2.2.1]<br/>[AWS][c2.2.2]  |  Brandon | [Docker][slides-docker] <br/> [AWS][slides-aws] |
| Wednesday | [SQL][c2.3.1] |  Sharad  | [SQL][slides-sql] <br/> [Python SQL][slides-pysql]  |
| Thursday |  [Spark RDDs][c2.4.1]<br/>[Spark SQL][c2.4.2] |  Brandon  | [Spark][slides-spark] |
| Friday |  [Spark EDA Case Study][c2.5.1] | Brandon   |  |

--

### Week 3: [Statistical Inference](https://github.com/GalvanizeDataScience/matts-stats-week)
| Day | Topic | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|
| Monday | [Assessment][-]<br/>[Probability][c3.1.1]<br/>[Binomial Tests][c3.1.2] |  Matt  | [Probability][slides-prob] <br/> [Binomial Tests][slides-binom] |
| Tuesday |  [Sampling Distributions][c3.2.1]<br/>[Law of Large Numbers][c3.2.2] |  Matt  | [Sampling Dists][slides-sampledists] <br/> [Law of Large Numbers][slides-lln] |
| Wednesday |  [Central Limit Theorem][c3.3.1]<br/>[Maximum Likelihood Estimation][c3.3.2] |  Matt  | [Central Limit Theorem][slides-clt] <br/> [Maximum Likelihood Estimation][slides-mle] |
| Thursday |  [Hypothesis Testing][c3.4.1]<br/> |  Matt  | [Hypothesis Testing][slides-hyptest] |
| Friday | [Power Calculation][c3.4.2] <br/> [Discuss and kickoff capstone 1][c3.4.3] | Matt / Brandon   | [Power Calculation][slides-power] |

--

### Week 4: Unit 1 Capstone 
| Day  | Topic | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|
| Monday |   Holiday |  -   | - |
| Tuesday |   [Data Products][132.0] |  Jack   | [slides][-] |
| Wednesday |  Capstone 1 |  -  | - |
| Thursday |  Capstone 1 | - | - |
| Friday | Capstone Presentations PM | - | - |

--

### Week 5: Supervised Learning and Regression
| Day | Topic | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|
| Monday | [Assessment][-]<br/>[KNN][c5.1.1]<br/>[Cross Validation][c5.1.2] | Jack | [KNN][slides-knn] <br/> [Cross Validation][slides-crossval] |
| Tuesday |  [Predictive Linear Regression][c5.2.1] |  Brandon   | [Predictive Linear Regression][slides-linreg] |
| Wednesday |  [Regularized Regression][c5.3.1]<br/>[Inferential Regression][c5.3.2] |  Jack  | [Regularized Regression][slides-regreg] <br/> [Inferential Regression][slides-infreg] |
| Thursday | [Logistic Regression][c5.4.1]<br/>[Classification Measures of Effectiveness][c5.4.2] |  Jack  | [Logistic Regression][slides-logreg] <br/> [Classification Metrics][slides-classificationmetrics]|
| Friday | [Regression Case Study][c5.5.1] |  Brandon  | [slides][slides-regcasestudy] |

--
### Solo Week
Your priorities this week:
<ul>
<li>Study any material from the previous weeks.</li>
<li>Collect data for upcoming capstones</li>
<li>Recharge for the 2nd half of the course</li>
</ul>

--

### Week 6: Nonlinear Supervised Learning
| Day | Topic | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|
| Monday | [Assessment][-]<br/>[Search Trees][c6.1.1]<br/>[Decision Trees][c6.1.2] | Jack | [Search Trees][slides-searchtrees]<br/>[Decision Trees][slides-decisiontrees] |
| Tuesday |  [Random Forests][c6.2.1] |  Brandon  | [Random Forests][slides-randomforest] |
| Wednesday |  [Gradient Boosted Regressors][c6.3.1]<br/>[Gradient Boosted Classifiers][c6.3.2] |  Jack  | [Gradient Boosting][slides-gradientboosting] |
| Thursday | [Gradient Decent][c6.4.1]<br/>[Basic Neural Networks][c6.4.2] |  Brandon  | [Gradient Descent][slides-gradientdescent] <br/> [Neural Networks][slides-neuralnetworks] |
| Friday | [Supervised Learning Case Study][c6.5.1]  |  -  | [slides][slides-suplearncasestudy] |

--

### Week 7: NLP and Unsupervised Learning
| Day | Topic | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|
| Monday | [Assessment][-]<br/>[NLP Intro][c7.1.1]<br/>[Text Classification][c7.1.2] | Jack | [slides][-] |
| Tuesday |  [PCA][c7.2.1]<br/>[SVD][c7.2.2] |  Brandon   | [Curse of Dimensionality][slides-curse] <br> [PCA][slides-pca] <br> [SVD][slides-svd]|
| Wednesday |  [Clustering][c7.3.1]<br/>[NMF][c7.3.2] |  Brandon  | [slides][-] |
| Thursday | [Graphs Introduction and Searching][c7.4.1]<br/>[Graphs Centrality and Communities][c7.4.2] |  Jack  | [slides][-] |
| Friday | Discuss and kickoff capstone 2 |  -  | - |

--

### Week 8: Unit 2 Capstone 
| Day | Topic | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|
| Monday | Work on capstone 2 | - | - |
| Tuesday |  Work on capstone |  -  | - |
| Wednesday |  Work on capstone and present results | - | - |
| Thursday |  Holiday | - | - |
| Friday | Holiday | - | - |

--

### Week 9: Advanced Topics 1
| Day | Topic | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|
| Monday | [Assessment][-]<br/>[
ian Inference][-]<br/>[Bayesian Coin Flipping][-] | - | [slides][-] |
| Tuesday |  [Reinforcement Learning][-]<br/>[Multi-Armed Bandit][-] |  -   | [slides][-] |
| Wednesday |  [Similarity Based Recommenders][-]<br/>[Content Based Recommenders][-] |  -  | [slides][-] |
| Thursday | [Implicit Recommenders][-] |  -  | [slides][-] |
| Friday | [Recommender Case Study][-]  |  -  | [slides][-] |

--

### Week 10: Advanced Topics 2
| Day | Topic | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|
| Monday | [Assessment][-]<br/>[Image Analysis][-]<br/>[CNNs][-] | - | [slides][-] |
| Tuesday |  [Sequence Analysis][-]<br/>[RNNs][-] |  -   | [slides][-] |
| Wednesday |  [Autoencoding][-]<br/>[Transfer Learning][-] |  -  | [slides][-] |
| Thursday | [Fraud Case Study (day 1)][-] |  -  | [slides][-] |
| Friday | [Fraud Case Study (day 2)][-] |  -  | [slides][-] |

--

### Week 11: Unit 3 Capstone
Kickoff your unit 3 capstone projects.  You will have daily sprint checkins.  No presentations this week, as you'll have a demo evening next week.

--

### Week 12: Career Week
| Day | Topic | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|
| Monday |  | - | [slides][-] |
| Tuesday |   |  -   | [slides][-] |
| Wednesday |   |  -  | [slides][-] |
| Thursday | PM - Demo evening |  -  | [slides][-] |
| Friday | PM - Graduation |  -  | [slides][-] |

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

<!-- Content Repos (sprints and assessments) -->
<!-- Week 1 -->
[c1.1.1]: https://github.com/GalvanizeDataScience/unix
[c1.2.1]: https://github.com/GalvanizeDataScience/pandas
[c1.2.2]: https://github.com/GalvanizeDataScience/matplotlib
[c1.3.1]: https://github.com/GalvanizeDataScience/oop
[c1.3.2]: https://github.com/GalvanizeDataScience/transformers
[c1.4.1]: https://github.com/GalvanizeDataScience/linear-algebra
[c1.4.2]: https://github.com/GalvanizeDataScience/numpy
[c1.5.1]: https://github.com/GalvanizeDataScience/mongo-db
[c1.5.2]: https://github.com/GalvanizeDataScience/web-scraping

[slide-unix]: https://github.com/gSchool/DSI_Lectures/blob/master/fundamentals/jack_bennetto/unix.md
[slide-pandas]: https://github.com/gschool/DSI_Lectures/tree/master/pandas
[slide-matplotlib]: https://github.com/gschool/DSI_Lectures/tree/master/pandas-matplotlib
[slide-oop]: https://github.com/gSchool/DSI_Lectures/tree/master/OOP/brandon_ma
[slide-linalg]: https://github.com/gschool/DSI_Lectures/tree/master/linear-algebra-eda
[slide-webscraping]: https://github.com/gSchool/DSI_Lectures/blob/master/web-scraping/brandon_ma/scraping.ipynb
[slide-mongo]: https://github.com/gSchool/DSI_Lectures/blob/master/web-scraping/brandon_ma/mongo.ipynb


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

[slides-bigo]: https://github.com/gSchool/DSI_Lectures/blob/master/interview-week/brandon_ma/runtime_analysis.ipynb
[slides-docker]: https://github.com/gSchool/DSI_Lectures/blob/master/docker/brandon_ma/docker_setup.md
[slides-aws]: https://github.com/gSchool/DSI_Lectures/blob/master/high-performance-python/moses_marsh/aws_lecture.ipynb
[slides-sql]: https://github.com/gSchool/DSI_Lectures/tree/master/sql/jack_bennetto
[slides-pysql]: https://github.com/gSchool/DSI_Lectures/tree/master/sql/jack_bennetto/sql-python
[slides-spark]: https://github.com/gSchool/DSI_Lectures/blob/master/spark/brandon_ma/spark_fundamentals.ipynb

<!-- Week 3 -->
[c3.1.1]: https://github.com/GalvanizeDataScience/probability-distributions
[c3.1.2]: https://github.com/GalvanizeDataScience/binomial-tests
[c3.2.1]: https://github.com/GalvanizeDataScience/sampling-distributions
[c3.2.2]: https://github.com/GalvanizeDataScience/law-of-large-numbers
[c3.3.1]: https://github.com/GalvanizeDataScience/central-limit
[c3.3.2]: https://github.com/GalvanizeDataScience/maximum-likelihood
[c3.4.1]: https://github.com/GalvanizeDataScience/hypothesis-testing
[c3.4.2]: https://github.com/GalvanizeDataScience/statistical-power
[c3.4.3]: https://github.com/gSchool/DSI_Lectures/blob/master/capstone-kickoffs/capstone1/capstone-1.ipynb

[slides-prob]: https://github.com/GalvanizeDataScience/matts-stats-week/blob/master/probability-distributions.ipynb
[slides-binom]: https://github.com/GalvanizeDataScience/matts-stats-week/blob/master/binomial-tests.ipynb
[slides-sampledists]: https://github.com/GalvanizeDataScience/matts-stats-week/blob/master/sampling-distributions.ipynb
[slides-lln]: https://github.com/GalvanizeDataScience/matts-stats-week/blob/master/the-law-of-large-numbers.ipynb
[slides-clt]: https://github.com/GalvanizeDataScience/matts-stats-week/blob/master/central-limit-theorem.ipynb
[slides-mle]: https://github.com/GalvanizeDataScience/matts-stats-week/blob/master/maximum-likelihood.ipynb
[slides-hyptest]: https://github.com/GalvanizeDataScience/matts-stats-week/blob/master/hypothesis-testing.ipynb
[slides-power]: https://github.com/GalvanizeDataScience/matts-stats-week/blob/master/statistical-power.ipynb

<!-- Week 4 -->

[132.0]: https://github.com/GalvanizeDataScience/data-products

<!-- Week 5 -->
[c5.1.1]: https://github.com/GalvanizeDataScience/knn
[c5.1.2]: https://github.com/GalvanizeDataScience/cross-validation
[c5.2.1]: https://github.com/GalvanizeDataScience/predictive-linear-regression
[c5.3.1]: https://github.com/GalvanizeDataScience/regularized-regression
[c5.3.2]: https://github.com/GalvanizeDataScience/inferential-regression
[c5.4.1]: https://github.com/GalvanizeDataScience/logistic-regression
[c5.4.2]: https://github.com/GalvanizeDataScience/decision-rules
[c5.5.1]: https://github.com/GalvanizeDataScience/regression-case-study

[slides-knn]: https://github.com/gSchool/DSI_Lectures/tree/master/non-parametric-learners
[slides-crossval]: https://github.com/gSchool/DSI_Lectures/blob/master/regularized-regression/brandon_ma/morning-model-selection.ipynb
[slides-linreg]: https://github.com/gSchool/DSI_Lectures/tree/2e2b726f489a1e7f174c389444be0430f6d97feb/linear-regression
[slides-regreg]: https://github.com/gSchool/DSI_Lectures/blob/master/regularized-regression/brandon_ma/afternoon-reg-reg.ipynb
[slides-infreg]: https://github.com/gSchool/DSI_Lectures/blob/2e2b726f489a1e7f174c389444be0430f6d97feb/linear-regression/matt_drury/linear-regression-introduction.ipynb
[slides-logreg]: https://github.com/gSchool/DSI_Lectures/tree/master/logistic-regression
[slides-classificationmetrics]: ???
[slides-regcasestudy]: ???

<!-- Week 6-->
[c6.1.1]: https://github.com/GalvanizeDataScience/search-trees
[c6.1.2]: https://github.com/GalvanizeDataScience/decision-trees
[c6.2.1]: https://github.com/GalvanizeDataScience/random-forests
[c6.3.1]: https://github.com/GalvanizeDataScience/gradient-boosted-regression
[c6.3.2]: https://github.com/GalvanizeDataScience/gradient-boosted-classification
[c6.4.1]: https://github.com/GalvanizeDataScience/gradient-descent/tree/g91-sea
[c6.4.2]: https://github.com/GalvanizeDataScience/perceptrons/tree/g91-sea
[c6.5.1]: https://github.com/GalvanizeDataScience/supervised-learning-case-study/

[slides-searchtrees]: ???
[slides-decisiontrees]: https://github.com/gSchool/DSI_Lectures/blob/master/non-parametric-learners/jack_bennetto/decision-trees.ipynb
[slides-randomforest]: https://github.com/gSchool/DSI_Lectures/tree/master/random-forest 
[slides-gradientboosting]: https://github.com/gSchool/DSI_Lectures/tree/master/boosting
[slides-gradientdescent]: https://github.com/GalvanizeDataScience/lectures/blob/SF/gradient_descent/Gradient%20Descent.ipynb
[slides-neuralnetworks]: https://github.com/gSchool/DSI_Lectures/blob/master/neural-network/brandon_ma/multilayer_perceptron.ipynb
[slides-suplearncasestudy]: ???
<!-- Week 7-->
[c7.1.1]: https://github.com/GalvanizeDataScience/nlp
[c7.1.2]: https://github.com/GalvanizeDataScience/text-classification
[c7.2.1]: https://github.com/GalvanizeDataScience/pca
[c7.2.2]: https://github.com/GalvanizeDataScience/svd
[c7.3.1]: https://github.com/GalvanizeDataScience/clustering
[c7.3.2]: https://github.com/GalvanizeDataScience/topicmodeling
[c7.4.1]: https://github.com/GalvanizeDataScience/graphs-searching
[c7.4.2]: https://github.com/GalvanizeDataScience/graphs-communities
[c7.5.1]: https://github.com/GalvanizeDataScience/nlp_case_study

[slides-curse]:https://github.com/gSchool/DSI_Lectures/blob/master/dimensionality-reduction/brandon_ma/curse_of_dimensionality.ipynb
[slides-pca]:https://github.com/gSchool/DSI_Lectures/blob/master/dimensionality-reduction/brandon_ma/pca.ipynb
[slides-svd]:https://github.com/gSchool/DSI_Lectures/blob/master/dimensionality-reduction/brandon_ma/svd.ipynb

<!-- Week 9-->
[c9.1.1]: https://github.com/GalvanizeDataScience/bayes-intro
[c9.1.2]: https://github.com/GalvanizeDataScience/bayes-testing
[c9.2.1]: https://github.com/GalvanizeDataScience/multi-armed-bandit
[c9.2.2]: https://github.com/GalvanizeDataScience/mcmc
[c9.5.1]: https://github.com/GalvanizeDataScience/recommender-case-study

<!-- Week 10-->
[c10.1.2]: https://github.com/GalvanizeDataScience/convolutional-neural-nets
[c10.2.1]: https://github.com/GalvanizeDataScience/time-series
[c10.2.2]: https://github.com/GalvanizeDataScience/recurrent-neural-nets

[c10.3.2]: https://github.com/GalvanizeDataScience/transfer-learning
[c10.4.1]: https://github.com/GalvanizeDataScience/fraud-detection-case-study

<!-- Assessments -->
<!-- Week 1 -->
[a0]: https://github.com/gschool/dsi-assessment-day1

<!-- Readings -->
<!-- Week 1 -->
[r1.1.1]: notes/workflow.md
[r1.1.2]: notes/pairing.md


