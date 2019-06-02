
# Capstones: High Level Overview

----

### Capstone 1: Dry Run
_Week 4_

A low-stakes way to practice your tools so far and get a feel for the capstone proposal process. If you get started on an idea you love, you can build on capstone 1 in the following capstones.

### Capstone 2: Commit to final proposal
_Week 8_

A guided process for locking in the topic for Capstone 2 & 3. A specific deliverable will be expected at the end of Capstone 2.

### Capstone 3: Make something amazing
_Week 11, 12_

A wealth of time to work very independently on making something amazing that builds on Capstone 2.

----


## Rough Schedule For Capstone I

The rough process for this is:
* **Friday, Weekend, Tuesday**:
    * Identify your interests (should've done this already)
    * Locate related data sources
* **Tuesday**:
    * Explore your data sources
    * Think if questions you could answer with the data
      * Scope your question to be answerable in one week
      * This might take more than one try
* **Wednesday, Thursday**:
    * Struggle to answer the question
* **Friday**:
    * [Deliverables: What you owe us](capstone1_deliverables.md)


## Learning objectives: What you owe yourself

By the end of the week you should have increased your skill in:
* Obtaining data sources
* Converting your interests + data sources -> a specific question
* Scoping a project to fit within a certain amount of time
  * (No one is good at this)
* Attending daily checking meetings 
   * check for [schedule](capstone1_deliverables.md)
* Using many of the following tools:
  * Basic tools: `unix`, `bash`, `python`, `docker`, `aws`
  * Data storage: `mongo`, `postgresql`
  * Data science tools: `spark`, `numpy`, `pandas`, `matplotlib`, `seaborn`
* Practice old ideas in data science ways:
  * Linear algebra
  * Algorithmic complexity
  * Probablity
  * Hypothesis testing

This is not something we do for you. This is something that you do for yourself, by way of achieving the deliverables.


## Example Run-Down

Here's a sample of what this might look like:

### Friday

Interests and data sources:
* Weather radar data: https://www.ncdc.noaa.gov/data-access/radar-data/noaa-big-data-project
* Magic: The Gathering card prices: https://www.mtggoldfish.com/prices/paper/standard
* Rideshare popularity: https://movement.uber.com/?lang=en-US
* The details on everyone's commute: https://lehd.ces.census.gov/data/
* The shapes and locations of buildings: https://blogs.bing.com/maps/2018-06/microsoft-releases-125-million-building-footprints-in-the-us-as-open-data
* Income in different areas: https://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml?pid=ACS_17_5YR_S1901&prodType=table

### Tuesday:
* Downloaded rideshare data from Uber and looked at the tables in raw text format and quickly read the data documentation.
* Tried to download the data on Magic but discovered I'd have to webscrap them.
* Downloaded the map of every building, but it was very big, and couldn't figure out how to extract information
* Decided to load Uber information into Pandas, and explore tables, and make a few graphs

### Wednesday:
* Decided on a question: Do rich people leave work earlier? In order to answer this, I need to identify if rush hour Uber trips to more wealthy neighborhood have a rush our peak earlier than to less wealthy neighborhoods.
* This will involve getting neighborhood-level census data, and using it to associate each uber trip with the affluence of the destination neighborhood. Once that is found, I can come up with a distribution of uber trips under the null hypothesis ("no connection between affluency and departure time"), and see if the data is so unlikely under that assumption that I should reject the null hypothesis.

### Thursday:
* This will take all day, and I probably won't be able to finish.

### Friday:
* I wasn't able to finish but I did find a way to merge census + Uber data, but I couldn't figure out a hypothesis test.
* Midday, stop working and start building a slide deck.

----


## Relationship to CRISP-DM

The CRoss-Industry Standard Process for Data Mining (CRISP-DM) lays out six steps in a data science project:

1. Business Understanding
1. Data Understanding
1. Data Preparation
1. Modeling
1. Evaluation
1. Deployment

CRISP-DM is executed in a _loop_. Once you finish with Deployment, you go back to Business Understanding.

The central idea of CRISP-DM is the **interplay** between your data project and its environment. You interact with the **real world** by proceeding in **loops**.

You can simplify to this:

1. Check in with the real world
1. Import a problem into the extremely literal environment of data science, and build something.
1. Push that something back into the real world.
1. GOTO 1.

Just as the goal of CRISP-DM is to **close a loop**, the goal of Capstone 1. is **also** to close a loop. We do this by:

1. Identify something we find interesting, in general terms.
1. Getting data and exploring it.
1. Asking a specific question.
1. Reporting on what we learned back to the real world.

This way we don't just float off into infinity; rather, we can impact and improve the real world. Furthermore, we find ourselves on solid footing to proceed with the next project.
