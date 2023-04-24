# Proptech - enabling quick purchasing decisions with the use of technology
*Capabilities include an instant, one-click service for people to buy properties and then rent them.*
*This technology will enable viewers to see housing trends broadly through San Francisco overtime and then view by neighborhoods.*
*We will be evaluating housing units, price per square foot and gross rents from 2010 to 2016 in roughly 30 neighborhoods in San Franscisco.*

---

## *Technologies*

- **Programming Language:** Python
- **Libraries:** Hvplot - a Python library for data visualization and Geoviews - a library for visualizing geographical datasets.
- **Software Development Kit:** none
- **Framework:** JupyterLab, can also use VS Code
- **Operating Systems:** Mac OS, Microsoft Windows

---

## *Installation Guide*
1. Confirm installation of libraries: "conda list hvplot", "conda list geoviews"
2. Pip install: if not installed or up-to-date, "conda install -c pyviz hvplot geoviews".
    
---

## *Usage*

#### Calculate and Plot the Housing Units Per Year
It is clear from the graph below that there is steady growth in the San Franscisco area:
<img width="452" alt="1a_units" src="https://user-images.githubusercontent.com/126728866/234129774-1cc14fdc-84da-4e69-9c26-aa943aa3faf3.png">

#### Calculate and Plot the Average Sale Prices (per sqft)
You can see that on average there is a steady incline in prices but from 2010 to 2011, there was a slight decrease in prices. This can perhaps be attributed to the tailend of the housing crisis that happened in this time. However, gross rents had a much more aggressive push upwards.
<img width="541" alt="1_overall" src="https://user-images.githubusercontent.com/126728866/234130122-c9ee4448-129b-417c-bfd5-b527a271c3ac.png">

#### Compare the Average Sale Prices by Neighborhood
If you use the dropdown menu to select neighborhoods, you can view the different growth trajectories for each neighborhood.
<img width="767" alt="2_by_neighborhood" src="https://user-images.githubusercontent.com/126728866/234130237-599d752d-9ac5-41ad-bd9c-325b1e50174a.png">

#### Build an Interactive Map of San Franscisco Neighborhoods
View the interactive map below. The size of each dot represents the sale prices (per sqft) and there is a hover capability to get the exact data for the neighborhoods that it represents
<img width="660" alt="3_geomap" src="https://user-images.githubusercontent.com/126728866/234131156-4c4223b9-66b8-40cb-8a9f-52f090cd9662.png">

#### Conclusions:
There's a lot of factors that go into real estate purchases. However given the data we have for the years 2010-2016, here are my observations:

1. In general, SFO is a growing city with increasing prices to purchase and rent.
2. Gross rental rates are growing at a faster rate then price per square foot - but those are two different metrics.
3. As you can see in Exhibit 5 below, the cities with the fast growing prices are: Russian Hill 1.826949 Twin Peaks 1.925857 Downtown 1.972553 Outer Richmond 2.539050 Van Ness/ Civic Center 4.116078
4. One would have to compare the total cost verus the gross rent to understand the ROI on investments or the rent per square foot versus the cost per square foot.

---

## *Contributor*

- Michelle Silver
- Email: supersilver1978@gmail.com

---

## *License*

This software is licensed under GNU General Public License v3.0. 
