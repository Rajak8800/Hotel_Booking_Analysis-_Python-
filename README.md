# Hotel_Booking_Analysis-_Python-
Hotel Booking Cancellation data analysis using Python and its libraries

# Overview
This project analyzes hotel booking data to uncover insights, trends, and actionable recommendations for business strategy.

It explores patterns in booking cancellations, seasonal trends, customer preferences, and revenue metrics like the Average Daily Rate (ADR).
## 1. Reservation Status Count
Visual: Bar Chart - Count of Canceled vs. Not-Canceled Reservations
Insight:

The data reveals that 63% of reservations were not canceled, while 37% were canceled.
This indicates that nearly one-third of all bookings fail to convert, which is a significant opportunity for improvement.
rd of all bookings fail to convert, which is a significant opportunity for improvement.
Actionable Note: Consider revisiting the cancellation policy or offering discounts for early confirmations.

## 2. Reservation Status in Different Hotels
Visual: Count Plot - Reservation Status (Canceled vs. Not-Canceled) for City and Resort Hotels
Insight:

City Hotels have a higher cancellation rate (41.7%) compared to Resort Hotels (27.9%).
Resort Hotels are better at retaining bookings, which may be linked to customer satisfaction or stricter policies.
Actionable Note: Investigate why City Hotels face higher cancellations. Conduct customer surveys or analyze booking conditions.

## 3. Average Daily Rate (ADR) Trends
Visual: Line Chart - ADR Trends for City and Resort Hotels Over Time
Insight:

ADR fluctuates throughout the year, with City Hotels consistently showing higher ADR compared to Resort Hotels.
The spikes in ADR correspond to peak travel seasons, indicating higher demand.
Actionable Note: Use dynamic pricing strategies to maximize revenue during peak months while maintaining competitive rates during off-peak seasons.

## 4. Reservation Status Per Month
Visual: Bar Chart - Monthly Reservation Status (Canceled vs. Not-Canceled)
Insight:

The highest number of cancellations occurs in July and August, aligning with the summer travel season.
Lower cancellations are observed in the winter months (e.g., January, February).
Actionable Note: Strengthen retention strategies during the summer, such as prepayment discounts or flexible rescheduling options.

## 5. ADR Per Month (Canceled Reservations)
Visual: Bar Plot - ADR for Canceled Reservations by Month
Insight:

Higher ADR values are associated with canceled reservations in certain months, potentially due to customers canceling expensive bookings.
Actionable Note: Analyze whether price sensitivity leads to cancellations and offer personalized discounts to high-value customers.

## 6. Top 10 Countries by Reservation Cancellations
Visual: Pie Chart - Top Countries Contributing to Cancellations
Insight:

Guests from Portugal, the UK, and the USA represent the majority of cancellations.
This indicates potential mismatches between customer expectations and the offerings for these regions.
Actionable Note: Enhance communication and tailor offers to these regions to reduce cancellations.

## 7. Market Segment Analysis
Visual: Bar Chart - Distribution of Market Segments and Cancellation Rates
Insight:

Online Travel Agents (OTAs) contribute the most bookings (47%) but also show the highest cancellation rates.
Direct bookings have lower cancellation rates, making them more reliable revenue sources.
Actionable Note: Encourage direct bookings through loyalty programs, exclusive offers, and better customer engagement.

## 8. ADR Trends for Canceled and Not-Canceled Reservations
Visual: Line Chart - Comparison of ADR for Canceled vs. Not-Canceled Reservations Over Time
Insight:

Not-canceled reservations have a steady ADR trend, whereas canceled reservations show irregular spikes.
This suggests that high-value bookings are more prone to cancellations.
Actionable Note: Consider targeting high-value bookings with incentives like flexible payment options or value-added services.


# Key Objectives

Understand the overall booking and cancellation trends.
Compare performance metrics between City Hotels and Resort Hotels.
Analyze ADR fluctuations and identify peak periods.
Examine the impact of market segments and regional distribution on cancellations.
Provide actionable recommendations to reduce cancellations and improve revenue.

# 🛠️ Tools and Technologies

## Programming Language: Python

### Libraries:
pandas

numpy

matplotlib

seaborn

Dataset: Contains ~119,390 records of hotel bookings from 2015 to 2017.

# 🗂️ Project Structure
bash
Copy code
.
├── data/

│   └── hotel_bookings.csv  # Dataset used for analysis
├── visuals/

│   └── *.png                    # Visualizations created during the analysis
├── analysis.ipynb               # Jupyter Notebook with the Python code
├── README.md                    # This file

# 🔍 Analysis and Insights

1. Cancellation Rate
37% of bookings were canceled.
City Hotels experienced a higher cancellation rate (41.7%) compared to Resort Hotels (27.9%).

3. ADR Trend  ADR was consistently higher for City Hotels than Resort Hotels.

4.Seasonal peaks in ADR were observed during summer months (June–August).

5. Market Segment Insights
6. Online Travel Agents (OTAs) contributed the highest bookings (47%) but had a high cancellation rate.
Direct bookings were more reliable, with fewer cancellations.
7. Top Countries by Cancellations
Guests from Portugal, UK, and USA had the highest cancellation rates.

# 📈 Visualizations
Reservation Status Count: A bar chart comparing canceled and not-canceled bookings.

Average Daily Rate: Line chart showing ADR trends for City and Resort Hotels.

Monthly Cancellation Trends: Bar chart visualizing cancellations by month.

Market Segments: Distribution and cancellation rates across booking channels.

Top 10 Countries: Pie chart of countries contributing the most to cancellations.

All visuals are available in the visuals/ directory.

# ✅ Key Recommendations
### Reduce Cancellations:
Enforce stricter policies for peak seasons.
Offer discounts for early confirmations.
### Optimize ADR:
Implement dynamic pricing strategies based on demand.
### Enhance Customer Retention:
Investigate feedback and preferences of City Hotel customers.
### Encourage Direct Bookings:
Promote loyalty programs and exclusive offers for direct customers.

# ⚙️ How to Use
Clone the repository:
bash
Copy code
git clone https://github.com/YourUsername/Hotel-Booking-Data-Analysis.git
Navigate to the project directory:
bash
Copy code
cd Hotel-Booking-Data-Analysis
Open analysis.ipynb in Jupyter Notebook to explore the analysis.

# 🖇️ References
Dataset: Kaggle - Hotel Booking Demand Dataset

📬 Contact
If you have any questions or feedback, feel free to contact me at [shaikrajak8800@gamil.com]
.














C
