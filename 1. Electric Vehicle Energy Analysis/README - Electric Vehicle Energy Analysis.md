## Overview 
* Dataset: Rideshare data from 3 trips
* Duration: 60 minutes 33 seconds
* Distance: 20.4 miles 
* Analysis: Electric vs Gas power cost comparison.
* Analysis: Energy consumption per acceleration and velocity rates. 
## See Full Report 
[![Watch the video](link to thumbnail img)](link to vid)
## Data points
* Distance 
* Velocity 
* Acceleration 
* Energy
* mi/Kw
## Dataset Considerations 
* Power data collected excludes regeneration.
* All calculations use actual power collected from dash or per trip actual power collected from dash. 
* Per trip KWh regeneration is approximated at 38% of recorded trip energy usage. [ -10% ]
* Per trip regeneration approximation is used to approximate actual per trip energy usage. 
* Average Energy Drain calculation only includes times when energy is actively being consumed.
* Average Velocity and Power Consumption include times when the vehicle is idle during each trip but not idle times between trips.
* Average Acceleration does not include times when vehicle is idle, at a constant speed, or decelerating.
## Notable Observations
* At 26 miles per gallon, every $100 spent on gas is about $30 bucks for EV charging.
* 8% of max battery life is expended after completing all three trips. 
* Trips 1 & 3 show highway data where velocity approaches 80MPH.
* Trip 2 illustrates city street stop and go traffic. 
* Driving Style: At higher velocities acceleration rates are less.
* Trip Comparison
	#### Trip 1
		* Uses the most power.
		* Trip 1 and Trip 3 were similar distances but trip 1 consumes 44% more power than trip 3. 
		* Trip 1 has higher average acceleration Than trip 3. 
	#### Trip 2
		* Uses the least amount of power.
		* Short trip duration
		* Low average velocity
		* Greatest per trip average acceleration
	#### Trip 3
		* Most efficient trip in terms of miles per KWh
		* Had the lowest average acceleration. 
## Analytical Considerations 
* Traveling at slower speeds and accelerating less will reduce power consumption, however, it will take longer to reach the destination.
## Figures 
1. Figure 1 Battery vs Gas Power consumption  
2. Figure 1.1 Gas Tank vs Battery Pack cost comparison  
3. Figure 2 Complete Data Set Chart  
4. Figure 2.1 Velocity, Acceleration, and Energy Plot  
5. Figure 2.2 Battery Life Pie Chart  
6. Figure 2.3 Average Velocity, Acceleration & Energy Bar Graph  
7. Figure 2.4 Average Power per Velocity Range  
8. Figure 2.4.1 Average Power per Acceleration Range 
9. Figure 2.5 Velocity and Acceleration vs Energy Analysis (Bar Graph)  
10. Figure 2.6 Velocity and Acceleration vs Energy Analysis (Line Graph)  
11. Figure 3 Isolated Trip Data  
12. Figure 3.1 Trip 1 Analysis  
13. Figure 3.2 Trip 2 Analysis  
14. Figure 3.3 Trip 3 Analysis  
15. Figure 3.4 Trip 1 - 45[s] interval  
16. Figure 3.5 Trip 1 - 1[min] 30[s] interval  
17. Figure 3.6 Trip 1 - 0.75[s] interval  
## Screenshots
#### 1. Figure 1 Battery vs Gas Power consumption  
![Alt Text](raw_url)
#### 2. Figure 1.1 Gas Tank vs Battery Pack cost comparison  
![Alt Text](raw_url)
#### 3. Figure 2 Complete Data Set Chart  
![Alt Text](raw_url)
#### 4. Figure 2.1 Velocity, Acceleration, and Energy Plot  
![Alt Text](raw_url)
#### 5. Figure 2.2 Battery Life Pie Chart  
![Alt Text](raw_url)
#### 6. Figure 2.3 Average Velocity, Acceleration & Energy Bar Graph  
![Alt Text](raw_url)
#### 7. Figure 2.4 Average Power per Velocity Range  &   #### 8. Figure 2.4.1 Average Power per Acceleration Range Range  
![Alt Text](raw_url)
#### 9. Figure 2.5 Velocity and Acceleration vs Energy Analysis (Bar Graph)  
![Alt Text](raw_url)
#### 10. Figure 2.6 Velocity and Acceleration vs Energy Analysis (Line Graph)  
![Alt Text](raw_url)
#### 11. Figure 3 Isolated Trip Data  
![Alt Text](raw_url)
#### 12. Figure 3.1 Trip 1 Analysis  
![Alt Text](raw_url)
#### 13. Figure 3.2 Trip 2 Analysis  
![Alt Text](raw_url)
#### 14. Figure 3.3 Trip 3 Analysis  
![Alt Text](raw_url)
#### 15. Figure 3.4 Trip 1 - 45[s] interval  
![Alt Text](raw_url)
#### 16. Figure 3.5 Trip 1 - 1[min] 30[s] interval  
![Alt Text](raw_url)
#### 17. Figure 3.6 Trip 1 - 0.75[s] interval  
![Alt Text](raw_url)