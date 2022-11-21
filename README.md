# Data-for-DRL-TO

Passenger flows for paper "Deep Reinforcement Learning based dynamic optimization of bus timetable"

Label：乘客唯一标志码 （passengers' label）
Boarding time：上车时间（第几分钟）（boarding time， 391 means "6:31", i.e., hour*60+minute）
Boarding station：上车站点（boarding station）
Alighting station：下车站点 （alighting station）
Arrival time：到站时间 ( time of arrival at the boarding station)
				
Note that the "Boarding time" is the Passenger's swiping time, which is collected through the payment system.

The "Arrival time" refers to the time when passengers arrive at the boarding station. It is estimated by the departure interval of the manual departure timetable and card swiping time.

In the simulation environment,  the "Label", "Boarding station", "Alighting station" and "Arrival time" are used to mimic real-time passenger flow.

The bus station distance indicates the distance between each station and the next station, which is measured in meters.
