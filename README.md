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
