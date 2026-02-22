#### Project Overview:
###### This project analyzes hotel booking data to identify factors driving cancellations and estimate revenue loss. The goal is to reduce booking cancellations and improve overall revenue performance.

#### Objective:
###### To analyze booking patterns and identify high-risk segments in order to reduce cancellations and minimize revenue loss.

#### Tools Used:
###### Pandas 

#### Dataset Description:
###### The dataset contains hotel booking records including:
###### Lead time
###### Market segment
###### Deposit type
###### Customer type
###### ADR (Average Daily Rate)
###### Stay duration
###### Reservation status
###### Cancellation indicator

#### Data Cleaning:
###### Handled missing values
###### Corrected data types
###### Converted date columns
###### Removed unnecessary columns

#### Feature Engineering
###### Created total_nights
###### Calculated lost_revenue
###### Created booking categories (e.g., lead time category)
###### Identified family bookings.

#### EDA
###### Calculated cancellation rate
###### Used groupby() to analyze segments
###### Used value_counts()
###### Used crosstab()
###### Compared cancellation by deposit type
###### Compared cancellation by lead time
###### Identified high-risk segments
###### Calculated revenue loss
