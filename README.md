# Hotel Booking & Revenue Analysis

An end-to-end data analytics project exploring hotel bookings, cancellations, customer segments, booking channels, stay patterns, and revenue. The project follows a practical analytics workflow: data cleaning in Microsoft Excel, data analysis using SQL, and business intelligence reporting in Power BI.

# Tools & Technologies

- Microsoft Excel -	Data cleaning and preparation
- SQL -	Data querying, aggregation, and analysis
- Microsoft Power BI -	Data modelling, DAX, data visualisation, and dashboard development

# Project / Business Requirement

Hotel businesses need to understand not only how many bookings they receive, but also when customers book, which channels they use, how often bookings are cancelled, and which customer segments and channels contribute the most revenue.

This project analyses hotel booking data to identify patterns in booking behaviour, cancellations, customer loyalty levels, booking channels, and revenue. The results are presented through a set of Power BI dashboards designed to make key business metrics and trends easy to explore.

# Project Workflow

**1. Data Cleaning** — Microsoft Excel
Prepared the raw dataset for analysis by carrying out data-cleaning and preparation tasks.
- Reviewed the dataset for data-quality issues.
- Cleaned and prepared the data for querying.
- Organised the data for the analysis workflow.

**2. Data Analysis** — SQL
Used SQL to investigate booking performance and answer the business questions.

The analysis covers:
- Confirmed and cancelled booking counts.
- Cancellation rates.
- Booking volumes by loyalty level and booking channel.
- Booking lead-time patterns.
- Booking and stay trends over time.
- Revenue by customer segment and booking channel.
- Room-rate and cancellation patterns.
  
The SQL scripts used for the analysis are available in the [`sql/`](sql/) folder.

**3. Data Visualisation** — Power BI
Developed Power BI dashboards to present the results in a clear, business-focused format.

The report is organised into three analytical sections:

**Executive Overview**
A high-level view of hotel performance, including:
- Total revenue
- Total bookings
- Confirmed bookings
- Cancellation percentage
- Average room rate
- Average length of stay
- Monthly booking patterns
- Revenue distribution by loyalty level
- Room rate and cancellation relationship
- Booking statistics by customer segment and channel

**Booking Analysis**
Examines booking outcomes and customer booking behaviour through:
- Confirmed vs. cancelled bookings by loyalty level
- Booking distribution by channel
- Cancellation lead time
- Customer booking statistics by loyalty level and channel

**Timeline Analysis**
Explores when customers make bookings and when they stay:
- Booking lead time
- Booking month vs. actual stay month
- Monthly booking trends
- Monthly stay trends
- Booking distribution by day of the week
- Average length of stay

**Revenue Analysis**
Investigates revenue distribution across customer segments and booking channels:
- Revenue by loyalty level
- Revenue by booking channel
- Revenue trends over time
- Revenue distribution across customer segments
- Room rate and cancellation patterns


# Key Findings

The following observations are based on the metrics and visualisations displayed in the Power BI report -

1. Booking cancellations are a significant part of booking activity. The reported cancellation rate is 28.72%.
2. Non-members contribute the largest share of revenue by loyalty segment, at approximately $346.46K, followed by Essential members at approximately $216.75K.
3. At-the-hotel bookings account for the largest share of bookings by channel at 29.46%, followed by Velora.com at 23.06% and GDS at 20.85%.
4. Bookings made more than a month in advance have the highest cancellation count among the displayed lead-time categories, with 694 cancellations.
5. Thursday has the highest booking count in the day-of-week comparison, with 579 bookings.
6. Booking activity increases substantially around September and October 2024 in the timeline visualisations.
7. The room-rate scatter plot shows a positive association between room rate and the displayed cancellation measure. This is an observed pattern, not evidence that higher room rates cause cancellations.
