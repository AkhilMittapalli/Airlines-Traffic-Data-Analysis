# Airlines Passenger and Freight Analysis (2015-2017)

## Overview
This project analyzes airlines' passenger and freight data from 2015 to 2017, focusing on carriers operating in India. The dataset provides monthly information on the number of passengers and freight transported to and from India. Using this dataset, we validate hypotheses about passenger trends, airline performance, and seasonal travel patterns.

## Dataset Information
- **Source**: [Data World](https://data.world/rajanand/international-air-traffic-from-and-to-india)
- **Size**: 2334 rows, 9 columns, 131 KB
- **Columns**:
  - **YEAR**: Year of record.
  - **MONTH**: Month of record (dropped during analysis).
  - **QUARTER**: Quarter of the year.
  - **AIRLINE NAME**: Airline identifier.
  - **CARRIER TYPE**: Domestic or international (dropped during analysis).
  - **PASSENGERS TO INDIA**: Number of passengers arriving in India.
  - **PASSENGERS FROM INDIA**: Number of passengers departing from India.
  - **FREIGHT TO INDIA**: Freight volume to India (in tons).
  - **FREIGHT FROM INDIA**: Freight volume from India (in tons).

## Objectives
1. Validate four hypotheses:
   - Hypothesis 1: More passengers leave India than arrive.
   - Hypothesis 2: Most travel occurs during Q2 and Q4.
   - Hypothesis 3: Air India competes strongly with international airlines in terms of passengers and freight.
   - Hypothesis 4: Identify the best-performing airline in all quarters in terms of growth.
2. Visualize trends in passenger and freight traffic.
3. Identify the top-performing airlines for passengers and freight growth.

## Tools and Libraries
- **Pandas**: For data manipulation and cleaning.
- **Matplotlib & Seaborn**: For data visualization.

## Findings

### **Hypothesis 1: More Passengers Leave India Than Arrive**
#### Observations:
- **Total Passengers (2015-2017):**
  - Passengers to India: 57,076,633
  - Passengers from India: 59,135,099
- **Conclusion**:
  - The hypothesis is true; more passengers leave India than arrive. However, the difference is minimal (3.5%).

#### Supporting Visualization:
- **Bar Graph**: Annual passengers traveling to/from India show consistent growth for both categories.
- **Pie Chart**: Distribution confirms a slightly higher share for passengers leaving India.

---

### **Hypothesis 2: Most Travel Occurs During Q2 and Q4**
#### Observations:
- Quarter-wise Passenger Data:
  - **Q2**: 25,450,336 passengers
  - **Q4**: 26,459,046 passengers
  - **Q1 & Q3 Combined**: 25,303,714 passengers
- **Conclusion**:
  - The hypothesis is false. Passengers traveling during Q1 & Q3 slightly exceed those traveling in Q2 & Q4, but the difference is minimal.

#### Supporting Visualization:
- **Bar Chart**: Shows passenger distribution across all quarters for 2015 and 2016.
- **Pie Chart**: Highlights comparable passenger volumes between Q1 & Q3 vs. Q2 & Q4.

---

### **Hypothesis 3: Air India Competes Strongly with International Airlines**
#### Observations:
- **Passenger Metrics:**
  - **Top Airlines (Passengers):** Jet Airways, Air India, Emirates Airlines.
  - Air India is the second-highest in passenger market share (domestic and international combined).
- **Freight Metrics:**
  - **Top Airlines (Freight):** Emirates Airlines, Cathay Pacific, Jet Airways.
  - Air India remains among the top performers but is not the leader.

#### Supporting Visualization:
- **Bar Graphs**:
  - Total passengers for each airline.
  - Total freight handled by each airline.

---

### **Hypothesis 4: Best-Performing Airlines in Terms of Growth**
#### Observations:
- **Passenger Growth:**
  - Top Performer: Mega Maldives Airlines (350% average growth).
- **Freight Growth:**
  - Top Performer: Aerologic Airlines (290% average growth).

#### Supporting Visualization:
- **Bar Graphs**: Top 10 airlines by passenger and freight growth.

---

## Conclusion
### Summary of Hypotheses
1. **Hypothesis 1**: True — More passengers leave India than arrive.
2. **Hypothesis 2**: False — Passenger volume is slightly higher in Q1 & Q3 than Q2 & Q4.
3. **Hypothesis 3**: True — Air India is a strong competitor, ranking second in passengers and maintaining a significant presence in freight.
4. **Hypothesis 4**: Top-performing airlines:
   - **Passengers**: Mega Maldives Airlines.
   - **Freight**: Aerologic Airlines.

### Key Insights
- Air India demonstrates strong competitiveness, especially in the passenger segment.
- Freight transport is dominated by international carriers like Emirates and Cathay Pacific.
- Passenger travel trends are relatively balanced across all quarters, with Q4 showing slightly higher volumes for inbound travel.

### Future Work
1. Analyze additional years to validate trends over a longer period.
2. Incorporate regional or seasonal data for granular insights.
3. Investigate the impact of economic factors (e.g., fuel prices, policy changes) on passenger and freight volumes.

### References
- [Data Source](https://data.world/rajanand/international-air-traffic-from-and-to-india)
- Additional research on aviation growth and market trends.

