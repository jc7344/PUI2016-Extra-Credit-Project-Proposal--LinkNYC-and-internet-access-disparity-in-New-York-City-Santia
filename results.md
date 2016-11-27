**Analysis:**
Are New Yorkers living in poverty, significantly more likely to be isolated from LinkNYC kiosk network, in comparison to New Yorkers living in low poverty?

For this analysis, I formed the following hypotheses:

**Null Hypothesis:**
The mean distance to LinkNYC kiosks for New Yorkers living poverty is the same or less than the mean distance to LinkNYC kiosks for New Yorkers in low poverty, significance level = 0.05.

**Alternative Hypothesis:**
The mean distance to LinkNYC kiosks for New Yorkers living poverty is more than the mean distance to LinkNYC kiosks for New Yorkers in low poverty, significance level = 0.05



All the data processing will be done with python and the majority of the mapping will be developed with ArcGIS. In order present exiting conditions, I will plot all currently installed LinkNYC kiosks (by zip code and/or community district) and the number households with no internet access (by community district). I will also create a 1/2mile buffer (which I defined as “walking distance”) around kiosks and analyze the percentage of the population in poverty living in a walking distance from the nearest kiosk. Lastly, I will generate centroids on the current location of LinkNYC kiosk in order to identify the average distance (in US feet) to residential units located in low and high poverty census tracts. 

