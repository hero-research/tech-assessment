<!-- ABOUT THE PROJECT -->
## Overview

This is an ETL exercise to demonstrate Data modeling and API development skills.

### Estimated time to Complete: ~2-3 Hours

This task is meant to be completed at home. We appreciate your time devoted to this technical assessment, and we 
will review the submission together during the follow-up interview where you may be asked reasons behind your
methodology, or any next-steps for remaining unwritten code that was not completed within the estimated allotment of time.


<!-- GETTING STARTED -->
### Getting Started

You are provided a list of Venues that host events. The dataset contains the 
time ranges of events on a given weekday, as well as the Category of the event at a particular location.

#### `Task 1`:
 Cleanse data, define rudimentary Data Model to prepare an Import into Database (Database is left to developer's choice)
 - format timeranges (Timezones are split into separate column already)
 - split categories by delimiter (semicolon ;)
 - init db, ensure schema is generated in startup event(s)

#### `Task 2`:
 Create endpoints to Query the events
 - Query by Category (pagination optional)
 - Query by Day of the Week (pagination optional)
 - Query by Events Happening Now (based on current Time of Day, and provide attribute showing time until close)

#### `Task 3`:
Options to Export your submission, Prepare for Discussion
 - Compress/Zip all files, send to Point of Contact
 - Private Github repo link or Git bundle
 - Include step-by-step docs to ensure code is able to run, and reproduce results from Endpoints


#### Requirements
 - We are evaluating your Data Engineering skills using Python and SQL... Other frameworks you chose to help demonstrate your abilities are welcome, but will be evaluated with less priority.
 - Provide a README file containing clear, simple instructions to execute code (and any tests you may have included).
 - Use any libraries of your choice, (caveat: If you do not submit virtual environment or Docker Container with start-up instructions the submission will be evaluated accordingly)
 - This sample test set is a subset of many other Time Ranges that may or may not follow the schema, so ensure that your code coverage is not over-fitted to this set.
 - Provide Comments/Docstrings to explain methods/functions.
 - Speed vs. Accuracy is a trade-off in many industries, but Attention to Detail is a major component of any role within a Data Career, especially within Data Engineering. Please keep this in mind for each task, from cleaning data to developing the endpoints.


#### What we Evaluate
This task is derived from real-world data to evaluate your ability to problem-solve and communicate effectively.
Please feel free to ask questions regarding the task if anything is unclear before getting started; however, the goal within the allotment of suggested time to complete the task
is for you to get as far as you can on your own, and have a plan for next-steps and action items prepared during the discussion of your work.
