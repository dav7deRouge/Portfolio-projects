# Iphone Sales Analysis Project
In this project I aimed at getting some insights about iPhone sales in India. 

## Dataset
I used a small dataset made up of 62 rows and 11 columns saved in a *csv* file named *apple_products.csv*.

# Procedure
After I read the dataset and analyzed a bit more its structure and the informations contained in it, I tried to answer 3 questions:
* **Which are the most sold devices?**
In order to get the answer I sorted the rows by considering the feature *Star rating* in descending order and by taking only the devices appearing in the top 10. The rank is available in the following graph:
<img src="https://github.com/dav7deRouge/Portfolio-projects/blob/main/Iphone%20Sales%20Analysis/Graph_images/IphoneRank.png" alt="" width="600" height="350" />

I also decided to plot the graph representing the number of ratings that each device got:

<img src="https://github.com/dav7deRouge/Portfolio-projects/blob/main/Iphone%20Sales%20Analysis/Graph_images/RatingsPerIphoneModel.png" alt="" width="900" height="400" />

After I plotted the device I chose to *normalize* the rating by dividing it for the number of ratings received, the new rank is the following:
<img src="https://github.com/dav7deRouge/Portfolio-projects/blob/main/Iphone%20Sales%20Analysis/Graph_images/NewIphoneRank.png" alt="" width="600" height="350" />

* **How much device's properties impact the sale price?**
To answer this question I created a couple of new columns by extracting informations about the memory and RAM of each device. Then I plotted a self explainatory graph:
<img src="https://github.com/dav7deRouge/Portfolio-projects/blob/main/Iphone%20Sales%20Analysis/Graph_images/BiggerDeviceHigherPrice.png" alt="" width="900" height="400" />

* **What's the optimal sale price range?**
For this last question I decided to plot another graph where I compared the number of ratings received by each device with its own sale price. 
<img src="https://github.com/dav7deRouge/Portfolio-projects/blob/main/Iphone%20Sales%20Analysis/Graph_images/LowerPriceEasierSale.png" alt="" width="900" height="400" />

The graph, as I expected, tells that devices with lower sale prices are sold more (95k+ devices sold at the lowest price recorded compared to only 542 sold at the highest price recorded). Does this say more about the country's economic situation? 