##Test Plan for Prac 6: Jayden Roberts – robe0635
Baggage Handling System for a Major Airport: Denver Airport Baggage Handling System
Any further information on the Denver Airport Baggage Handling System can be found at http://calleam.com/WTPF/?page_id=2086
##Design Analysis
This test plan will be focussed on the baggage handling system for the Denver Airport, the purpose of the baggage handling system is to automate the handling of baggage throughout the entire airport. This system begins at the check-in point, where the bag would be sent throughout the airport to the to the arrivals point with virtually no human interaction, this in turn would reduce flight delays and minimise time spent at the baggage pick up area.
Components of this design
The components of this design can be broken down into three parts, 

* Check-in: baggage is weighed, and then is labelled with its final destination and flight number.
* Conveyor system: The conveyor belt system is used to transport the baggage to and from the terminals.
 *System Software: This software is used to run the conveyor systems and uses a database to store the baggage information.

##Drawbacks of this design

* Misidentification of Baggage: this can cause difficulties in determining where the baggage is located .
* Mechanical Failure: this could be the cause of many major delays if there isnt a human element on stand when an issue occurs.
* Misdirection of Luggage: this could occur when a item of baggage is not labelled correctly at any stage in the process.

There are many small risks in using this design, with the largest area that would be prone to failure being based at the Check-in area, if there happens to be any errors in the labelling of the bags this would go on to cause major issues with the final destination of the luggage i.e. if there is misreading of the labels at the Check-in point, there is a higher chance of an incorrect reading of the label while the baggage is on the conveyor system causing the bag to be sent to the wrong area or even placed on the wrong flight, thus causing the system to lose baggage and cause flight delays.

##Testing Methods
Integration Testing: This testing method will be performed to ensure all the internal systems from all the airlines can recognise and swap data between the systems, and also be able to read and understand the data sent between one another.

* Stress Testing: Utilising this testing method would benefit the system by checking if the database, and the manual conveyor systems can handle a set amount of traffic. This would ensure that the system can function correctly during peak times and also just run under heavy traffic.
* End-to-end testing: This testing method would ensure that in an everyday situation that the systems would function to specifications, this would enhance all processes that need to have a human interaction. i.e.  Checking in and picking up luggage.
* Recovery Testing: This testing method would mainly take place at the conveyor systems, for example, if the conveyor belt system failed this can cause large delays for flights and slow all other processes. Due to the fact that one of the largest advantages of this new system is its new baggage handling system, the system should undergo rigorous testing to insure that the system runs to all of its specifications.

###Secondary Testing Methods
* Black Box Testing: This testing method was found to be insufficient due to the fact that any piece of baggage could be sent to any of the 88 airport gates, thus causing this method to be extremely time consuming and due to the large amount of gates this type of testing would be unsuitable to assure a correct test.
* Usability Testing: This testing method was found to be possibly useful in the later stages of the test plan, but there needs to be a strong base and system before this testing should take place.  
* System Testing: This testing method was found to be redundant due to the fact that a comprehensive unit test will be previously completed before this method would be used, In conjunction with the system being so large, there is no assurance that the whole system would be sufficiently tested correctly due to the many scenarios that would need to be tested thus defeating the purpose of this test.

