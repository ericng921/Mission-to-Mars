# Mission-to-Mars
## Overview of the Mission-to-Mars
### Purpose of the analysis

In the module we had scraped the Mars fact and Mars's images on our flask apps and put the data in the dataframe.

In the challenge we added all four of the hemisphere images in our Mars site by scraping from "marshemispheres.com". We also included the titles of those images for the full-resolution images of Mars's hemisppheres. In addition we stored the scraped data on our Mongo database.

## Resources

- **Program codes Files:** app.py, scraping.py, index.html, Mission_to_Mars_Challenge.ipynb

- **Data tools and libary:** splinter, beautifulsoup, pandas, ChromeDriverManager    

- **Application:** Python 3.9.7, Jupyter Notebook 6.4.5, Flask 2.1.2

## Result

![mars_hemi](https://user-images.githubusercontent.com/100378319/167528069-c6d4ceaf-f4cd-4cc2-a235-6d5d43ecf3a3.png)

As picture above shown it displays 4 full-resolution Mars hemisphere image URL and title.

--------------------------------------

![dbmongo](https://user-images.githubusercontent.com/100378319/167528093-00d08fd5-1f11-4cd5-acd1-86ec2f3f1d33.png)

As picture above shown Mongo database is updated to contain image URL and title for each hemisphere.

--------------------------------------

![mobile_grid](https://user-images.githubusercontent.com/100378319/167528083-18e692b7-f282-49e4-bc37-ae8b1c1ea79a.png)

As picture above shown I have added three additional Bootstrap 3 components:

1. Updated inde.html so website is mobile-responsive

2. Table with border

3. Button colour showing as green
