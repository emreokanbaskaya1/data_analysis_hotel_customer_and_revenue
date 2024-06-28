# data_analysis_hotel_customer_and_revenue
Connected to a hotel data source and performed data cleaning, transformation, analysis, and visualization to provide insights into customer acquisition, retention, and revenue generation.
# Capstone Project: # Hotel Customer and Revenue

## Project Overview

In this capstone project, I analyzed hotel booking data, performed exploratory data analysis (EDA) and regular data analysis using Python, and visualized the results using Power BI. This project is documented and available on GitHub. The files included in the repository are:

- `dataset.csv`
- `dashboard.pbix`
- `eda.ipynb`
- `powerbi_analysis.png`

## Dataset Description

The dataset contains the following columns:

- **hotel:** Type of hotel (H1 = Resort Hotel or H2 = City Hotel)
- **is_canceled:** Indicates whether the booking was canceled (1 if canceled, 0 if not)
- **lead_time:** Number of days between the booking date and the arrival date
- **arrival_date_year:** Year of arrival date
- **arrival_date_month:** Month of arrival date
- **arrival_date_week_number:** Week number of the year of arrival date
- **arrival_date_day_of_month:** Day of the month of arrival date
- **stays_in_weekend_nights:** Number of weekend nights (Saturday or Sunday) the guests stayed or booked to stay at the hotel
- **stays_in_week_nights:** Number of week nights (Monday to Friday) the guests stayed or booked to stay at the hotel
- **adults:** Number of adults
- **children:** Number of children
- **babies:** Number of babies
- **meal:** Type of meal booked (Undefined/SC – no meal package; BB – Bed & Breakfast; HB – Half board (breakfast and one other meal); FB – Full board (breakfast, lunch, and dinner))
- **country:** Country where the booking was made (ISO 3155–3:2013 format)
- **market_segment:** Market segment designation (e.g., "TA" means Travel Agents, "TO" means Tour Operators)
- **distribution_channel:** Distribution channel designation (e.g., "TA" means Travel Agents, "TO" means Tour Operators)
- **is_repeated_guest:** Indicates if the booking is from a repeated guest (1) or not (0)
- **previous_cancellations:** Number of previous bookings that were canceled by the customer prior to the current booking
- **previous_bookings_not_canceled:** Number of previous bookings not canceled by the customer
- **reserved_room_type:** Code of room type reserved. Code is presented instead of designation for anonymity reasons.
- **assigned_room_type:** Code for the type of room assigned to the customer. Sometimes the assigned room type differs from the reserved room type due to operational reasons (e.g., overbooking) or customer request. Code is presented instead of designation for anonymity reasons.
- **booking_changes:** Number of changes/amendments made to the booking from the moment the booking was entered until the check-out or cancellation
- **deposit_type:** The type of deposit made by the customer to guarantee the booking. This variable can assume three categories: No Deposit – no deposit was made; Non Refund – a deposit was made with a non-refundable policy; Refundable – a deposit was made with a refundable policy.
- **agent:** ID of the travel agency that made the booking. ID is presented instead of designation for anonymity reasons.
- **company:** ID of the company/entity that made the booking or is responsible for the booking. ID is presented instead of designation for anonymity reasons.
- **days_in_waiting_list:** Number of days the booking was in the waiting list before it was confirmed to the customer
- **customer_type:** Type of customer, classified into four categories: Contract - when the booking has an allotment or other type of contract associated with it; Group – when the booking is associated with a group; Transient – when the booking is not part of a group or contract, and is mostly made up of individual bookings; Transient-party – when the booking is transient, but is associated with other transient bookings.
- **adr:** Average Daily Rate, as defined by dividing the sum of all lodging transactions by the total number of staying nights
- **required_car_parking_spaces:** Number of car parking spaces required by the customer
- **total_of_special_requests:** Number of special requests made by the customer (e.g., high floor, room with view)
- **reservation_status:** Reservation status, indicating the current status of the booking (Canceled - booking was canceled by the customer; Check-Out - customer has checked out; No-Show - customer did not check in and gave no indication of the reason)
- **reservation_status_date:** Date at which the last status was set. This variable is used in conjunction with the Reservation Status to determine when the status was last set.

## Project Files

- **dataset.csv:** The raw data used for analysis.
- **dashboard.pbix:** The Power BI dashboard file showcasing the visualized insights from the data.
- **eda.ipynb:** The Jupyter Notebook file containing both the exploratory data analysis (EDA) and regular data analysis performed 
