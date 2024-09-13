<!-- ABOUT THE PROJECT -->
## Overview

This task is a web-scraping Exercise to extract data from Businesses in LAS VEGAS, NEVADA, USA listed on Yelp
`https://www.yelp.com/search?find_desc=Restaurants&find_loc=Las+Vegas`


### Estimated time to Complete: 2 Hours

This task is meant to be completed at home. We appreciate your time devoted to this technical assessment, and we 
will review the submission together during the follow-up interview where you may be asked reasons behind your
methodology, or any next-steps for remaining unwritten code that was not completed within the estimated allotment of time.

<!-- GETTING STARTED -->
###  Getting Started

You are provided with a variety of attributes that need to be organized, The complexity increases per each Level, which will a rubric for evaluation of the approach and execution of methods used to define a scheam from unstructured data.

### Data to Collect:

#### Level 1 (General Business Info):
 - Name
 - Website
 - Phone
 - Email
 - Open Hours
 - Address

#### Level 2 (Categorical/Tag List):
 - Category of Food
 - Price Classification (i.e. `$$` vs `$$$`)
 - Health Score
 - Amenities
 - Highlights
 - Related Search Terms

#### Level 3A (Measurable):
 - Overall Rating
 - Overall Number of Reviews
 - Date of Establishment

#### Level 3B (Status):
 - Standalone (restaurant located within building vs. standalone brick & mortar)
 - Profile Status: (Claimed vs. Unclaimed)
 - Operational Status: (Permanently Closed vs. Operational vs. "coming soon")

#### Level 4 (Text):
 - About/Description
 - FAQs 
 - User Reviews
   + Rating of Review
   + Date of Review
   + Commentary/Text
   + Reviewer's Details

#### Level 5 (File):
 - Menu
 - Cover Image
 - Business Logo
 - Media Gallery


<!-- EVALUATION -->
 ### Evaluating Results
  - Results from Level 1-3 should be sent as `.csv` or `.xlsx`
  - Results from Level 4 should be sent as `.json`
  - Results from Level 5 may be sent as `.zip`  

  - Code to run Scraper will be evaluated, and may be submited as a link to a public github repo, or packaged in a docker container