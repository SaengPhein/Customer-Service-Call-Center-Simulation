# Customer-Service-Call-Center-Simulation
This is a baseline simulation model I designed for a specific company using the student version of ProModel.
Due to limitations of the student version of the software, I decided to split 1 week of simulation into 5 sub - models, 1 for
each of the work day during the week (Monday - Friday). 8 shift schedules were taken into consideration, with the addition of
in - call hold time and probabilities. All process times used a triangular distribution, and the inter-arrival rate of calls were 
random with a range of (0,16). I designed the arrival of customers to arrive continuously using a dummy infinite while loop.
The simulation runs for 12 hours, which represents operation hours of 6 am - 6pm. This simulation uses downtimes to dictate 
shift schedules, servers to represent a specific shift, and capacity of server to represent the number of representatives who 
work during that specific shift. This model was validated and was 99% accurate to historical data obtained from the company for which
this baseline mode was created to replicate their existing call center system.
