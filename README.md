## About This Data
This dataset is downloaded from Kaggle: https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata?resource=download <br/>
We also up the file zip of data [here](https://github.com/vthuhien/Airbnb_Data/blob/main/Airbnb_Open_Data.7z) in Github. And if you want to see directly or are lazy to unzip this file, [here](https://drive.google.com/file/d/11k6K0WwlkmGl3pg82v29taFKAae7qSIh/view?usp=drive_link) is good for y.</br>

Airbnb is an American company that operates an online marketplace for lodging, primarily homestays for vacation rentals, and tourism activities. Airbnb does not own any of the listed properties; instead, it profits by receiving commission from each booking. The company was founded in 2008. Airbnb is a shortened version of its original name, AirBedandBreakfast.com.</br>

Since 2008, guests and hosts have used Airbnb to travel in a more unique, personalized way. As part of the Airbnb Inside initiative, this dataset describes the listing activity of homestays in New York City. The following Airbnb activity is included in this New York dataset:
* Listings, including full descriptions and average review score Reviews
* Including unique id for each reviewer and detailed comments Calendar
* Including listing id and the price and availability for that day

## Description
The description about data - [Here](https://docs.google.com/spreadsheets/d/1b_dvmyhb_kAJhUmv81rAxl4KcXn0Pymz) is file with full description of data

| Name col     | Details |
| ----------- | ----------- |
| host_id      | A unique ID for house owner. When you register about the apartment rental in Airbnb, this company will assign you an ID.   |
| country   | Region of your house        |
| host_identity_verified   | The owner has been identified, hasn't ? or virtual business address     |
| minimum nights   | The minimum nights that the owner allow to hire       |
| license   | Seem to business License      |
| last review   | Last reviewed date      |

## Visualization
### 1. Neighbourhood group - barchart
![image](https://github.com/user-attachments/assets/8908cf2a-1f7b-416f-b751-e5ac956aabff)
This chart analysis based on the zoned region. As we can see, the neighborhoods of Williamsburg and Bedford - Stuyvesant that have the numbers of homestay high are extremely. This indicates that in New York, this company mobilizes a large number of customers who are letting their property. The total quantity is focused on high the Williamsburg and Bedford-Stuyvesant areas.</br>


Through that, we suggest that the Airbnb company has a good campaign to promote their revenue. However, It seems to be distributed unevenly and less than to the right . </br>
The right skew shows that the management just focus in the Williamsburg and Bedford-Stuyvesant areas but neglect other areas, leaving them severely deficient.

### 2. Scatter Mapbox 
![image](https://github.com/user-attachments/assets/5c5cf6d9-5a50-4d5d-bcb8-5dcbeee082f3)
We use this chart to compare the price rely on the neighborhood groups. With longitude and latitude, we distribute them on a real openstreet map to analyze easily. The chart clearly shows the prices clearly at each address and each street. </br>
As we can see, in the Brooklyn, Manhattan and Queens neighborhood groups, the distribution is largest, densest and most even with a wide range of price levels from low to high. However, further away from these areas, the distribution becomes more discrete, uneven, and less abundant.

### 3. Piechart - Construction Year
![image](https://github.com/user-attachments/assets/1ca965ab-6894-4dc3-9bf0-f70e39c12c09)
### 4. Line Chart
![image](https://github.com/user-attachments/assets/bcef0580-aae2-4bb9-96f8-b3b79bc0f8f9)
