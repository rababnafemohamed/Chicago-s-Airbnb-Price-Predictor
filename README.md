### Motivation ###
As people try to get into new businesses to increase their income after a hard year, we
found that there is no way to predict how much someone should charge for an Airbnb listing. To
make that transition easier we want to create a model that can predict the price of the market for
a new place taking into account its characteristics. This model then could be used to create web
applications or mobile apps and help people to get into the Airbnb business.

### Data ###
Source: This dataset belongs to Inside Airbnb. Specifically, we will use Chicago's dataset posted
on December 20th, 2020. It can be found at http://insideairbnb.com/chicago/.
Description: As will use a raw dataset from Inside Airbnb, then we will have to spend a lot of
time cleaning it. The data consists of 16 columns and 6523 rows.
Attributes information: Id, name, host_id, host_name, neighbourhood_group, neighbourhood,
latitude,longitude, room_type, price,minimum_nights, number_of_reviews, last_review,
reviews_per_month, calculated_host_listings_count, and availability_365

Dimensions: On figure 1, we can observe that the dataset has 16 columns and 6523 rows. There is an
empty column neighbourhood_group and 1285 missing values from last_review and review_per_month.
![Screenshot 2025-02-21 5 41 45 PM](https://github.com/user-attachments/assets/de0f0747-6967-450e-807d-a28b1fc629e0)

Figure 1 - Columns, entries and data types.
Discussion: The data is not pre-processed. It has some missing values and five categorical

Discussion: The data is not pre-processed. It has some missing values and five categorical
attributes (see figure 3). We would need to do some processing as one-hot encoded, labeling and
data cleaning
![Screenshot 2025-02-21 5 43 15 PM](https://github.com/user-attachments/assets/f7cf3463-af7e-4dd4-9776-414304a183f4)

![Screenshot 2025-02-21 5 44 12 PM](https://github.com/user-attachments/assets/4a0502e3-ddef-4d73-85a8-1d94131d2fbf)

Visualizations of some Airbnb Characteristics
The pie Chart in Figure 4 shows percentage of each room type in the data set. And as observed
we can see that 69.14 % Entire home, 1.44% Shared room, 1.09 % Hotel room and 28.33 %
Private room
![Screenshot 2025-02-21 5 45 53 PM](https://github.com/user-attachments/assets/2cd696d8-20f1-4347-bd4d-cb03496ff3d3)

The box plot in Figure 5 is a visualization of number_of_reviews values, and the data is
right-skewed with some outliers.
![Screenshot 2025-02-21 5 46 58 PM](https://github.com/user-attachments/assets/de367b53-2db2-40fd-b32c-067b2ce5d2bd)


