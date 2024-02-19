# BGP Router

High-level Approach: Upon receiving any message, add it to a routing table and keep a copy of it in history then check for aggregation. Based on the type, we will perform the relevant functions to apply the wanted function. At the end of a run, return the current table

Challenges: I had troubles understanding how the router and neighbor relationships work at first. And then the data message also confuse me a lot and took me quite some time debugging. Also, the aggregation/disaggregfation part was really hard.

List of properties/features: 
Sending update message
Sending data message
Sending withdraw message 
Support aggregation.
Support handling similar routes

Overview of testing: 
Running the configs file from the starter code
Running the code on Gradescope submission