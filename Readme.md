# Hotel Booking Demand Analysis & Insights Generation

##  Objective

This project aims to analyze hotel booking behaviors and uncover trends in cancellations, customer types, and pricing strategies. With growing interest in tourism data and online reservation patterns, the analysis helps identify seasonal peaks, guest demographics, and financial implications. Using Python, the data was cleaned, analyzed, and structured to derive insights that can support hotel business decisions and planning.

##  About the Dataset

The dataset contains hotel booking records from two types of hotels—City Hotel and Resort Hotel. It includes 33 columns with information such as reservation status, arrival dates, guest composition (adults, children, babies), country of origin, customer types, and average daily rate (ADR). The dataset spans multiple years and provides a comprehensive view of booking behavior. Missing values were handled, and key columns were formatted for analysis, such as combining year, month, and day into a proper `arrival_date` column. All insights were generated from non-canceled bookings to reflect actual check-ins.

##  Guidelines to Use the Script

1. Clone or download the repository to your local machine.
2. Open the notebook `HotelBooking.ipynb` in Google Colab.
3. Run the cells sequentially to:
   - Load and clean the data
   - Analyze cancellations and ADR patterns
   - Explore seasonal trends and guest distribution
   - Merge country codes and identify top booking sources
4. Outputs include summary tables and data transformations that are ready for dashboard visualization.

##  Conclusion

The analysis revealed that approximately 37% of hotel bookings were canceled, with City Hotels experiencing a higher cancellation rate than Resort Hotels. Seasonal booking trends varied, with City Hotels peaking in August and Resort Hotels in July. Transient customers consistently paid the highest average daily rates, especially in City Hotels. The average number of guests per reservation was 2, and the maximum reached up to 55 guests. Country-wise insights showed a concentration of bookings from a few key regions. Overall, this data-driven approach provides valuable information for strategic hotel management, pricing, and operational planning.
