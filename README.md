## Phase 2 Project

## Project Overview

For this project, you will use regression modeling to analyze house sales in a northwestern county.

### The Data

This project uses the King County House Sales dataset, which can be found in  `kc_house_data.csv` in the data folder in this repo. The description of the column names is given below:

# Column Names and descriptions for Kings County Data Set
* **id** - unique identified for a house
* **dateDate** - house was sold
* **pricePrice** -  is prediction target
* **bedroomsNumber** -  of Bedrooms/House
* **bathroomsNumber** -  of bathrooms/bedrooms
* **sqft_livingsquare** -  footage of the home
* **sqft_lotsquare** -  footage of the lot
* **floorsTotal** -  floors (levels) in house
* **waterfront** - House which has a view to a waterfront
* **view** - An index of the from 0 - 4 and shows if the house has been viewed
* **condition** - How good the condition is ( Overall )
* **grade** - overall grade given to the housing unit, based on King County grading system
* **sqft_above** - square footage of house apart from basement
* **sqft_basement** - square footage of the basement
* **yr_built** - Built Year
* **yr_renovated** - Year when house was renovated
* **zipcode** - zip
* **lat** - Latitude coordinate
* **long** - Longitude coordinate
* **sqft_living15** - The square footage of interior housing living space for the nearest 15 neighbors
* **sqft_lot15** - The square footage of the land lots of the nearest 15 neighbors

# Key concerning some columns
* **Grade** - Represents the construction quality of improvements. Grades run from grade 1 to 13. Generally defined as:

		1-3 Falls short of minimum building standards. Normally cabin or inferior structure.

		4 Generally older, low quality construction. Does not meet code.

		5 Low construction costs and workmanship. Small, simple design.

		6 Lowest grade currently meeting building code. Low quality materials and simple designs.

		7 Average grade of construction and design. Commonly seen in plats and older sub-divisions.

		8 Just above average in construction and design. Usually better materials in both the exterior and interior finish 		work.

		9 Better architectural design with extra interior and exterior design and quality.

		10 Homes of this quality generally have high quality features. Finish work is better and more design quality is 			seen in the floor plans. Generally have a larger square footage.

		11 Custom design and higher quality finish work with added amenities of solid woods, bathroom fixtures and more 			luxurious options.

		12 Custom design and excellent builders. All materials are of the highest quality and all conveniences are present.

		13 Generally custom designed and built. Mansion level. Large amount of highest quality cabinet work, wood trim, 			marble, entry ways etc.
	# source: https://info.kingcounty.gov/assessor/esales/Glossary.aspx?type=r

## Business understanding
Home prices are continually changing. The reality of not knowing whether the price for a potential house is going to increase or not, makes it very challenging for future homeowners to plan, be prepared and ready, timely and financially. This factor plays into the role of influencing the assumption of how hard it is to buy a house since home seekers need to have a long checklist of what is required to buy a house. Being able to predict the fluctuation of home prices should not be one of the tasks in that checklist. In fact, not only future homeowners are ones who are interested; renters, investors, and businesses will all be benefited from the outcome of this project. Predicting house price is not an easy task. It is very challenging and requires the exploration of many factors to be able to come up with the findings. For this project, I’m using a single dataset (kc_data.csv). This dataset contains house sale prices for King County, which includes Seattle, between May 2014 and May 2015. My goal is to explore the correlation between home price and other in the dataset to come up with the final findings and prediction. Additionally, I’m not taking into consideration any potential unique events in the real estate world or any macroeconomics factors since it is out of scope and I don’t have the right resources for this task.

## Task
I have to build a simple linear regression that can help to predict the value of the house King county, WA houses. I’ve applied variables necessary to running a graphical analysis before I jumped into the model. Displaying the information will provide insight that could be correlated, with the primary goal of determining if these variables impact each other or just move in the same direction.

Regression Models:
    • Linear regression 
		correlation between sale price and other variables
