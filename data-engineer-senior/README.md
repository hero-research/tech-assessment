<!-- ABOUT THE PROJECT -->
## Overview

This is an take-home assesment to demonstrate general Data Engineering & Analytics skills as well as system architecture approach to handling API development tasks.

### Estimated time to Complete: ~2 Hours

This task is meant to be completed at home. We appreciate your time devoted to this technical assessment, and we 
will review the submission together during the follow-up interview where you may be asked reasons behind your
methodology, or any next-steps for remaining unwritten code that was not completed within the estimated allotment of time.


<!-- GETTING STARTED -->
### Getting Started

You are provided a list of roughly 10,000 "Social Media Accounts" abstracted with a respective UUID that is tracked over the span of 2 years in terms of Followers/Subscriber Count growth or decay. The dataset contains a datetime for each point in time in which the Followers/Subscriber Count was measured for each account, as well as a few category tags per each account that help filter and sort the data in a later step.

Keep in mind, we only care about Accounts that have a Followers/Subscriber Count above 1000.

#### `Task 1`:
  Normalize the data found in the file `sample_accounts.parquet`, define rudimentary Data Model to prepare an Import into Database (Database is left to developer's choice)
 - ensure consistent format of timestamps
 - handle categories, split by delimiter (semicolon ;)
 - init db, ensure schema is generated in startup event(s)

#### `Task 2`:
  Insert the data provided in the file `add_accounts.parquet`, using the schema defined in `Task 1`
 - Use any means to input this Data, using POST request, using a crontab Script, using a DAG etc.

#### `Task 3`:
 Create endpoints to Query the Accounts
 - Query by Category (pagination optional)
 - Query by Subscriber Count > 1 million (pagination optional)
 - Query by Subscriber Growth within last 1 Month, Greater than 10% (pagination optional)

#### `Prep for Follow Up Discussion`:
Options to Export your submission, Prepare for Discussion (options for submitting deliverables)
 - Compress/Zip all files, send to Point of Contact: `data@hero.io`
 - Private Github repo link or Git bundle
 - Include step-by-step docs/README.md to ensure code is able to run, and reproduce results from Endpoints


#### Requirements
 - We are evaluating your Data Engineering skills using Python and SQL... Other frameworks you chose to help demonstrate your abilities are welcome, but will be evaluated with less priority.
 - Provide a README file containing clear, simple instructions to execute code (and any tests you may have included).
 - Use any libraries of your choice, (caveat: If you do not submit virtual environment or Docker Container with start-up instructions the submission will be evaluated accordingly)
 - The `add_accounts.parquet` is a simple test of handling more subscriber growth datapoints at scale, keep this in mind when providing a solution to extend the database table beyond the sample set for future measurements for these accounts.
 - Provide Comments/Docstrings to explain methods/functions.
 - Speed vs. Accuracy is a trade-off in many industries, but Attention to Detail is a major component of any role within a Data Career, especially within Data Engineering. Please keep this in mind for each task, from cleaning data to developing the endpoints.


#### What we Evaluate
This task is inspired by real-world data, though it is random and is not directly linked to any actual Social Media Platform or set of accounts. It is generated simply to evaluate your ability to problem-solve and communicate effectively, and see the strategy for next steps for tasks within this takehome that you are not able to complete within the alloted 2 hours.
Please feel free to ask questions regarding the task if anything is unclear before getting started; however, the goal within the allotment of suggested time to complete the task
is for you to get as far as you can on your own, and have a plan for next-steps and action items prepared during the discussion of your work.
