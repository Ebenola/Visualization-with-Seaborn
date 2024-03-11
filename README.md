**<h1>Car Brands and Listings Dataset</h1>**

**<h2>Project Overview</h2>**

This repository contains a simple dataset that lists various car brands and their corresponding listings. 

The goal is to visualize key insights using Python and Seaborn.

**<h3>Visualizations</h3>**

Visualizations was created using Seaborn:

**1. Bar Chart: Car Brands vs. Listings Count**

Shows the number of listings for each car brand.
<pre>plt.figure(figsize = (9, 6))

plt.xticks(rotation = 45, fontsize = 13)

plt.bar(x = df_used_cars["Brand"],
       height = df_used_cars["Cars Listings"], color = "midnightblue")
plt.yticks(fontsize = 13)
plt.title("Cars Listings by Brand", fontsize = 13, fontweight = "bold")
plt.ylabel("Number of Listings", fontsize = 13)

plt.show()

plt.savefig("Cars Listings Bar.png")</pre>

![image](https://github.com/Ebenola/Visualization-with-Seaborn/assets/104829299/de7a64c6-2eab-438f-8dfc-cf2d139e84e8)

**2. Horizontal Bar Chart**
<pre>plt.figure(figsize =(9, 6))
plt.barh(y = Used_Car_Data["Brand"], width = Used_Car_Data["Cars Listings"], color = "midnightblue")
plt.xticks(fontsize = 13)
plt.yticks(fontsize = 13)
plt.xlabel("Number of Listings", fontsize = 13)
plt.title("Cars Listings by Brand", fontsize = 16, fontweight = "bold")
plt.tight_layout()
plt.show()
plt.savefig("Used Car hBar.png")</pre>

![image](https://github.com/Ebenola/Visualization-with-Seaborn/assets/104829299/fdb048a7-1b3a-4130-8ace-8957c1c9f862)

