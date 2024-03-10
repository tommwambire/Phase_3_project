# Tanzania Water Point Classification System


## Introduction
Access to water and sanitation are recognized as human rights by the United Nations. The right to water entitles everyone to access sufficient, safe, acceptable, physically accessible, and affordable water for personal and domestic use. Access to clean water opens lots of possibilities in a community and improves the quality of life and standards of living of a people. Access to clean water enables for proper development of adults, children, and livestock and thus increases their survival rate. Access to clean water also improves the sanitation efforts of a community and this in turn helps lower infection and disease rates of a people. In addition, access to clean water affords a community a chance to boost their economic output since they are more capable of growing crops and rearing livestock and they can start manufacturing and processing industries which most rely on the availability of water. As we have seen from the cases above water is a vital necessity. However, billions of people across the world are still living without safely managed water and sanitation.

Third-world countries account for the huge percentage of people who do not have access to water. The United Nations estimates that around one billion people in developing countries have inadequate access or lack access to clean and reliable water sources. As of October 2022, about 226 million people in Eastern and Southern Africa did not have access to basic water services. The situation is worse in rural areas than in cities. Nine countries (Angola, Democratic Republic of Congo, Ethiopia, Kenya, Madagascar, Mozambique, Sudan, Tanzania, and Uganda) are home to 80% of underserved people in the region.

In Tanzania, for instance out of its population of 65 million people, 58 million people (88% of the population) lack access to safe water, and 49 million people (74%) lack access to a safe toilet. This greatly affects the quality of life of the people since they have to travel great distances to get access to clean water. The national government of Tanzania is aware of these troubling metrics and is working to make clean water more available. The national government of Tanzania through the Tanzania Ministry of Water has set bold and ambitious plans to double clean water accessibility in the next 10 years. It is working together with international organizations such as the United Nations, the World Bank, and the International Monetary Fund and is more than willing to engage with Non-Governmental Organizations.

Addressing people’s need for water and sanitation is vital in improving economic growth and more importantly, improving the lives and health of people and it ensures that their most vital and basic human rights are met. To address these challenges, we need to unite, come up with innovative solutions, and work together to make the lives of other people better. 

## Problem Statment
Dutch Water Limited (DWL) is a world-leading organization that produces and sells affordable, healthy, and purified water to all people. They are experts in water purification and making water accessible to many people. They are partnered with 2 European companies whose expertise is making water pumps and filtration systems. They have looked at current United Nations studies and have visited the country (Tanzania) and they feel like they can make a considerable effort in alleviating some of the water accessibility crisis felt in Tanzania. 

They have engaged the national government of Tanzania through the Tanzania Ministry of Water and they have decided to help the government and its citizens by repairing the waterpoints throughout the country. This is in line with their expertise and that of their partners. The ministry has provided data on all the water points with many different metrics but it is incomplete. 

DWL needs to come up with a relevant strategy to analyze the data and use it to help them predict the functioning status of the waterpoints to maximize their efforts ensure efficiency and ensure they can do the most.

## Objectives

### Main Objective
To analyze the various data that have been made available to them by the Ministry of Water in Tanzania and come up with a machine learning model that can predict the functioning status of a waterpoint given certain factors.

### Specific Objectives
To gain insight into the various operating states of the waterpoints throughout the country and their frequencies.

To gain a greater insight into the water points throughout the various regions of the country. This is to understand which regions need the most attention so that they can be given higher priority.

To gain a better understanding of how the water points are managed come up with strategies on how to guide the maintenance of the waterpoints.

To gain the operating environments of the waterpoints. This mainly includes the state or condition of the water at the water points. To decide which technology or type of pumps to bring in and use.

## Notebook Structure
Reading the data

Data Wrangling and Cleaning

Exploratory Data Analysis

Modelling

Conclusions

Recommendations

## Data Understanding
The data used in this project was aquired from Tanzania Ministry of Water and Taarifa which is the leading provider of business management solutions and online data storage for businesses in Tanzania. It contains various data and information on the water points and the environment which they operate in and status of whether they are functional, non functional or functional but needs repair.

The entire data used in the project is contained in 2 datasets. The datasets contain the following features:

amount_tsh - Total static head (amount water available to waterpoint)

date_recorded - The date the row was entered

funder - Who funded the well

gps_height - Altitude of the well

installer - Organization that installed the well

longitude - GPS coordinate

latitude - GPS coordinate

wpt_name - Name of the waterpoint if there is one

num_private - Indicates whetherthe well is private

basin - Geographic water basin

subvillage - Geographic location

region - Geographic location

region_code - Geographic location (coded)

district_code - Geographic location (coded)

lga - Geographic location

ward - Geographic location

population - Population around the well

public_meeting - True/False

recorded_by - Group entering this row of data

scheme_management - Who operates the waterpoint

scheme_name - Who operates the waterpoint

permit - If the waterpoint is permitted

construction_year - Year the waterpoint was constructed

extraction_type - The kind of extraction the waterpoint uses

extraction_type_group - The kind of extraction the waterpoint uses

extraction_type_class - The kind of extraction the waterpoint uses

management - How the waterpoint is managed

management_group - How the waterpoint is managed

payment - What the water costs

payment_type - What the water costs

water_quality - The quality of the water

quality_group - The quality of the water

quantity - The quantity of water

quantity_group - The quantity of water

source - The source of the water

source_type - The source of the water

source_class - The source of the water

waterpoint_type - The kind of waterpoint

waterpoint_type_group - The kind of waterpoint

status_group - (target variable) contains information on whether the water point is functional, non functional and functional needs repair.


## Methodology

### Combining Data Sets
This is where the 2 different data sets are going to be combined or merged to form 1 big data set that is going to be used for the rest of the project.

### Data Wrangling and Cleaning
Null or missing values were also dropped or filled with suitable alternatives to ensure the integrity of the data. Data was also converted into different data types to enable us to draw meaningful information from it. New features are also created here.

### Exploratory Data Analysis
Here we visualize the cleaned data to gain more information about the data we are using and we see whether we can answer or meet our objectives.

### Modelling
Here we compare various different models and come up with the best model for the data that will meet our objectives and will give us the best accuracy. We also tune the model to ensure maximum possible performance.

### Conclusion

### Recommendations