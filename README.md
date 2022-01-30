# Practical-Data-Science

1. Classification: ExtraaLearn is an initial stage startup that offers programs on cutting-edge technologies to students and professionals to help them upskill/reskill. With a large number of leads being generated on a regular basis, one of the issues faced by ExtraaLearn is to identify which of the leads are more likely to convert so that they can allocate resources accordingly.

Tasks performed-
    - Analyze and build an ML model to help identify which leads are more likely to convert to paid customers,
    - Find the factors driving the lead conversion process
    - Create a profile of the leads which are likely to convert
    
Data Description-
The data contains the different attributes of leads and their interaction details with ExtraaLearn. The detailed data dictionary is given below.

Data Dictionary

ID: ID of the lead
age: Age of the lead
current_occupation: Current occupation of the lead. Values include 'Professional','Unemployed',and 'Student'
first_interaction: How did the lead first interact with ExtraaLearn. Values include 'Website', 'Mobile App'
profile_completed: What percentage of the profile has been filled by the lead on the website/mobile app. Values include Low - (0-50%), Medium - (50-75%), High (75-100%)
website_visits: How many times has a lead visited the website
time_spent_on_website: Total time spent on the website
page_views_per_visit: Average number of pages on the website viewed during the visits.
last_activity: Last interaction between the lead and ExtraaLearn.

Email Activity: Seeking details about the program through email, Representative shared information with a lead like a brochure of program, etc.
Phone Activity: Had a Phone Conversation with a representative, Had a conversation over SMS with a representative, etc.
Website Activity: Interacted on live chat with a representative, Updated profile on the website, etc.
print_media_type1: Flag indicating whether the lead had seen the ad of ExtraaLearn in the Newspaper.

print_media_type2: Flag indicating whether the lead had seen the ad of ExtraaLearn in the Magazine.
digital_media: Flag indicating whether the lead had seen the ad of ExtraaLearn on the digital platforms.
educational_channels: Flag indicating whether the lead had heard about ExtraaLearn in the education channels like online forums, discussion threads, educational websites, etc.
referral: Flag indicating whether the lead had heard about ExtraaLearn through reference.
status: Flag indicating whether the lead was converted to a paid customer or not

2. Time Series: Amazon.com, Inc. engages in the retail sale of consumer products and subscriptions in North America as well as internationally. This dataset consists of monthly average stock closing prices of Amazon over a period of 12 years from 2006 to 2017. We have to build a time series model using the AR, MA, ARMA and ARIMA models in order to forecast the stock closing price of Amazon.

Data Description: 
  - date: Date when the price was collected
  - close: Closing price of the stock
