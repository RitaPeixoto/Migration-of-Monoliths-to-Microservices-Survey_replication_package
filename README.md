# Migration of Monoliths to Microservices - Survey replication package

This repository contains the replication package of a study of how the migration from monoliths to microservices is performed.
## Description
To assess how the process of refactoring to microservices is undertaken, the tools and the
evaluation methods used currently in the industry, we conducted a survey among software companies
and professionals from this field, focusing on how teams select and apply refactorings. We obtained a total of 66 responses.

## Research Questions
* RQ1. What is the refactoring process that they follow?
* RQ2. What tools do they use? 10
* RQ3. How do they evaluate the result from the decomposition?
## Content

* `Migration of Monoliths to Microservices Survey - V3.csv`
    - Corresponds to the raw results retrieved from Google Forms
* `Migration of Monoliths to Microservices Survey - V3 (Responses) - Form Responses 1_2.csv`
    - Corresponds to the results after data preparation was performed (mostly manually).
* `industry_survey.ipynb`
    - Corresponds to the Jupyter Notebook with the analysis of the data collected.
* `study1.pdf`
    - Corresponds to the survey from the Google Forms created.

<!-- charm_acm_checklist.pdf - checklist of the ACM Empirical Standards "Questionnaire Surveys"-->

## Procedure
The study was performed through an online survey using *Google Forms* with an estimated time of *30 minutes* to complete.


## Findings
* Practitioners plan the migration mostly to be interspersed with the product evolution
* They mainly focus on web resources and other practitioners’ experiences to guide their migration.
* Software documentation and development process data are
used as data sources to decide how to decompose the monolith into microservices.
* They mainly focus on decomposing by business
capability or subdomain.
* Strangler Fig, UI Compo- 12
sition, Parallel Run, Branch by Abstraction, and Change code dependency to service call are the
most used techniques to split the monolith.
* When decomposing the database,
Change Data Ownership is clearly more used than the other techniques.
* Challenges faced during the migration process are database migration and data store splitting, consistency, and ensuring reliability.
* A large share of practitioners does not use any tools to assist their migration.
* They find
that tools for deciding service boundaries, regression testing, microservice API design and refatoring code are needed. 
* Refactoring tools should be easy to use, provide multiple decomposition alternatives and provide visualization.
* Most of the respondents, when asked how they usually evaluate the result of the decomposition, mentioned that they did not do it, it was not worth the effort, or only sometimes, and some specifically said it is based on intuition.
* Maintainability, Performance and Scalability are the quality attributes most assessed.
* The assessment is performed in multiple environments, mostly during development and using more functional tests than production input or simulation.



