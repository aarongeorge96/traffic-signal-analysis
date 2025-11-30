\# Traffic Signal Analysis - Zurich Intersection



Analysis of traffic signal and vehicle detection data from a fully actuated intersection in Zurich, Switzerland.



\## Key Findings



\### Traffic Patterns

\- \*\*Peak hour:\*\* 4 PM (16:00)

\- \*\*Busiest day:\*\* Saturday

\- \*\*Busiest time:\*\* Saturday 3 PM (shopping/leisure traffic)

\- \*\*Quietest time:\*\* 3-4 AM



\### Signal Behavior

\- \*\*Night mode (2-4 AM):\*\* All signals switch to flashing yellow

\- \*\*Most green time:\*\* sg10 (43%)

\- \*\*Least green time:\*\* sg11/sg12 - tram signals (5%)

\- \*\*Signals adapt:\*\* Green time increases during peak hours



\### Tram Priority

\- Tram signals active 9.7% of the time

\- Dedicated signals (sg11, sg12) only activate when trams arrive



\### Efficiency Analysis

\- \*\*Most efficient approach:\*\* d10 (39% wait at red)

\- \*\*Least efficient approach:\*\* d2 (98% wait at red)

\- Side streets (d2, d3) have lowest priority



\## Visualizations



\### Hourly Traffic

!\[Hourly Traffic](output/hourly\_traffic.png)



\### Daily Traffic

!\[Daily Traffic](output/daily\_traffic.png)



\### Traffic Heatmap

!\[Heatmap](output/traffic\_heatmap.png)



\### Peak vs Off-Peak Signal Timing

!\[Peak vs Off-Peak](output/peak\_vs\_offpeak.png)



\### Wait Percentage by Approach

!\[Wait Percentage](output/wait\_percentage.png)



\### Detector Activity

!\[Detector Totals](output/detector\_totals.png)



\## Dataset



\- \*\*Source:\*\* ETH Zurich Research Collection

\- \*\*Location:\*\* Urban intersection in Zurich, Switzerland

\- \*\*Period:\*\* January - February 2019

\- \*\*Resolution:\*\* 1 second

\- \*\*Records:\*\* 5,076,422



\### Data Structure

\- \*\*10 loop detectors (d1-d10):\*\* Detect vehicle presence

\- \*\*12 traffic signals (sg1-sg12):\*\* Signal states (0=red, 1=green, 8=yellow)

\- \*\*sg11, sg12:\*\* Tram priority signals



\## Tech Stack



\- Python

\- pandas

\- Plotly



\## References



\- \[Dataset: ETH Research Collection](https://www.research-collection.ethz.ch/handle/20.500.11850/556642)

\- \[Paper: A traffic signal and loop detector dataset](https://www.sciencedirect.com/science/article/pii/S2352340923002366)

