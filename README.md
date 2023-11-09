# Hotel_Booking_Analysis

# Introduction

Analysing the data of Hotel Booking. This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data.

We will perform exploratory data analysis with python to get insight from the data.

# Problem Statement

Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? This hotel booking dataset can help you explore those questions!

Explore and analyze the data to discover important factors that govern the bookings.

# Dataset 

Hotel: H1= Resort Hotel, H2= City Hotel
is_canceled : If the booking was canceled(1) or not(0)
lead_time : Number of days that elapsed between the entering date of the booking into the PMS(Property Management System) and the arrival date
arrival_date_year : Year of arrival date.
arrival_date_month : Month of arrival date.
arrival_date_week_number : Week number for arrival date.
arrival_date_day_of_month: Which day of the months guest is arriving.
stays_in_weekend_nights: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel.
stays_in_week_nights: Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel.
adults : Number of adults.
children : Number of children.
babies : Number of babies.
meal: kind of meal opted for.
country : Country code.
market_segment: Which segment customer belongs to.
distribution_channel : How the customer accessed the stay- Corporate Booking/Direct/TA.TO
is_repeated_guest : The values indicating if the booking name was from a repeated guest (1) or not (0).
previous_cancellations : Was there a cancellation before.
previous_bookings_not_canceled : Count of previous bookings not cancelled.
reserved_room_type : Code of room type reserved.
assigned_room_type : Code for the type of room assigned to the booking.
booking_changes : Count of changes made to booking.
deposit_type : Deposit type.
agent : If the booking happens through agents or not.
company : If the booking happens through companies, the company ID that made the booking or responsible for paying the booking.
days_in_waiting_list : Number of days the booking was on the waiting list before the confirmation to the customer.
customer_type : Type of customer.
adr : Average Daily Rates that described via way of means of dividing the sum of all accommodations transactions using entire numbers of staying nights.
required_car_parking_spaces : How many parking areas are necessary for the customers.
total_of_special_requests : Total unique requests from consumers.
reservation_status: The last status of reservation, assuming one of three categories: Canceled – booking was cancelled by the customer; Check-Out;No-Show.
reservation_status_date: The last status date.

# Tools and Libraries Used

We have used Python 3 to its following packages:
1. Pandas
2. Matplotlib
3. Seaborn

# Conlusion

1. City hotels are the most preferred hotel type by the guests.

2. 27.5 % bookings were got cancelled out of all the bookings.

3. BB( Bed & Breakfast) is the most preferred type of meal by the guests.

4. "Online TA" and "Offline TA/TO" are the more preferred booking channels.

5. Most of the bookings for City hotels and Resort hotel were happened in 2016.

6. In August, the maximum number of bookings for both city hotels and resort hotels was observed.

7. Optimal stay in both the type hotel is less than 7 days.

8. The months of June,July and August show higher Average Daily Rates (ADR) for Resort hotels compared to City hotels.

9. In week 32,33 and 34 the maximum number of bookings for both city hotels and resort hotels was observed.

10. City Hotels has longer waiting period than the Resort Hotels. Thus we can say that City Hotels are much busier than the Resort Hotels.
