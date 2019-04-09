# Advanced Software Engineering  

```
This project was undertaken as a module at  
Trinity College Dublin : MSc Computer Science  
```

# Links:
Test Manager: [Test Quality](https://tcd-ase.testquality.com/project/5897)  
Android: [Client - Android Application](https://github.com/tcdayush/DirectMe)  
Server:  [Server - Spring Boot Microservices](https://github.com/manohajx/ASE_Server_Side_Logic)

## The Team

| College ID  | Surname  | First Name | Mail ID | Github Handle
| :--------:    |:---------------:| :------:| :--------------: | :--------------: |
| 18300592      | BHATIA          | SNEHAL  |  BHATIAS@TCD.IE  | [snehal08](https://github.com/snehal08)
| 18301411      | MISHRA          | AYUSH   |  MISHRAAY@TCD.IE | [tcdayush](https://github.com/tcdayush)
| 18314752      | MANOHAR LINCOLN | JOHN PRASHANTH GNANIAH     | MANOHARJ@TCD.IE | [manohajx](https://github.com/manohajx)
| 18315700 	    | RAMESH 	        | SUPRITH | RAMESHSU@TCD.IE  | [SuprithRamesh](https://github.com/SuprithRamesh)
| 18316477 	    | MANDA 	        | SHILPA  | MANDAS@TCD.IE    | [mandashilpa26](https://github.com/mandashilpa26)
| 17316106 	    | MANI NAIR 	    | MANJIMA | MANINAIM@TCD.IE  | [maninaim](https://github.com/maninaim)

## Project Description

### Project Name
Dynamic Sustainable Wayfinding

### Goal
The goal of this project is to provide real-time wayfinding for travellers that improves the reliability of the mobility experience across all transportation modes. It will build intelligence at the edges of the network (i.e., decentralised), while providing real-time decision-making and decision support to very large numbers of travellers, across a wide range of transportation modes (including pedestrian, bike, car, bus, tram, train and taxi) tailored to their individual priorities (pollution avoidance, emissions reduction, speed, reliability, comfort etc.). A single trip may involve multiple modes of transport, which may be modified en-route, given changes in the environment, e.g., congestion, noise pollution, crowded and so on.

### Challenges
Some of the main challenges include identifying when a user’s interests are likely to conflict with sustainability goals, how a user can be incentivised to choose a more sustainable travel plan, and when to trigger an adaptation of the travel plan in line with users’ preferences

### Requirements

#### Be multi-modal
The options presented to the traveller should include three or more modes, and the demonstration of the overall system should illustrate multiple different routes, with all mode options (listed above) used at least once. Real-time data should be used, when available. Where real-time data is not available, options should be simulated;

#### Be adaptive
The system should illustrate capability to adapt the route AFTER the traveller has started. This is likely to require simulation of some event that has a negative impact on the previously identified route (e.g., unexpected closure of a road, or tree on the Luas line), requiring the traveller to change modes, in real time.

#### Be highly available
The system must be fault tolerant. The system should execute even when off-line. The system must react favourably even if data from heterogeneous sources are not available.

#### Provide low latency for mobile users
This means that a decentralised architecture is likely to be most appropriate

#### Be secure
The system should be secure from attack.
