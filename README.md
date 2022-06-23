# Wildfire Acres Burned YTD

### To grab the data: 

I used data from the [National Interagency Fire Center](https://www.nifc.gov/fire-information/nfn) for this project, which was updated on June 21, 2022 at the time of download. I made the assessment that it would be quicker to copy and paste the YTD statistics table into an Excel spreadsheet and quickly clean it using Pandas, rather than to scrape it. The script to do so, along with detailed notes, can be found [here](https://github.com/jessieblaeser/Wildfire-Acres-Burned-YTD/blob/main/etl/Clean%20YTD%20Table.ipynb). 

### To analyze the data: 

In [this notebook](https://github.com/jessieblaeser/Wildfire-Acres-Burned-YTD/blob/main/analysis/YTD%20Fire%20-%20Stat%20Review.ipynb) I did some number-crunching. In order to judge whether or not wildfire acres burned year-to-date in 2022 is “abnormal.” As the notebook shows, while the 2022 YTD numbers are higher than any other year since 2012, it's still too early to conclude from the data alone that 2022 will be an anomaly compared to the last decade. 

I calculated a few additional elements, including things like acres burned to-date per fire and percent change between each of my existing columns. I also grabbed data from the NIFC on total acres burned per year from 2012 to 2021 in order to contextualize acres burned by the start of summer, which helped when creating a data visualization of this information. 
