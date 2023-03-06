# Iphone Sales Analysis Project
In this project I aimed at getting some insights about iPhone sales in India. 

## Dataset
I used a small dataset made up of 62 rows and 11 columns saved in a *csv* file named *apple_products.csv*.

# Procedure
After I read the dataset and analyzed a bit more its structure and the informations contained in it, I tried to answer 3 questions:
* Which are the most sold devices? 
In order to get the answer I sorted the rows by considering the feature *Star rating* in descending order and by taking only the devices appearing in the top 10. The rank is available in the following graph:
<img src="https://github.com/dav7deRouge/Portfolio-projects/blob/main/Iphone%20Sales%20Analysis/Graph_images/IphoneRank.png" alt="" width="200" height="200" />

I also decided to plot the graph representing the number of ratings that each device got:

<img src="https://github.com/dav7deRouge/Portfolio-projects/blob/main/Iphone%20Sales%20Analysis/Graph_images/RatingsPerIphoneModel.png" alt="" width="250" height="300" />

After I plotted the device I chose to *normalize* the rating by dividing it for the number of ratings received, the new rank is the following:
<img src="https://github.com/dav7deRouge/Portfolio-projects/blob/main/Iphone%20Sales%20Analysis/Graph_images/NewIphoneRank.png" alt="" width="200" height="200" />