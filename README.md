# Airline-Passenger-Satisfaction
Power BI dashboard analyzing 130K+ airline passenger records to identify key drivers of dissatisfaction and build a customer retention-risk framework.

### Key Steps
Unpivoted 14 individual service rating columns using Power Query to enable cross-attribute comparison.
Built DAX measures (`CALCULATE`, `AVERAGE`, `SWITCH`, `DISTINCTCOUNT`, `DIVIDE`) to calculate a "rating gap" — the difference in average rating between satisfied and dissatisfied passengers — for each service factor.
Segmented findings by flight distance (binned) and customer type (Returning vs. First-Time) to compare service priorities across passenger segments.

### Key Findings
Online Boarding showed the largest rating gap, making it the strongest driver of dissatisfaction overall.
In-flight service factors were consistently rated higher than on-ground service factors across most flight distances, with the gap narrowing sharply on the longest flights.
Returning and First-Time customers showed different top dissatisfaction drivers, suggesting the airline needs segment-specific service priorities to protect customer retention.
