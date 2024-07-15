<h4>Assumptions</h4>
These assumptions guide the design and implementation of the Railway Management System Database, ensuring a structured and comprehensive approach to managing railway operations and data.

<ul>
 <li> <b>Passenger Information:</b> Each passenger can have a unique name, age, gender, and contact information. Passengers are uniquely identified by their name and contact information.</li>
 <li> <b>Station Information:</b> Each station has a unique station ID, station name, and station type. Stations are uniquely identified by their station ID. </li>
 <li><b>Train Information:</b> Each train has a unique train number, train name, start 
time, and end time. Trains are uniquely identified by their train number. 
Start and end times are stored as timestamps to accurately represent 
departure and arrival times.</li>
 <li><b>Route Information:</b> Each route has a unique route ID and sequence 
number. Each route corresponds to a specific train, station, arrival time, 
departure time, and distance from the origin station. Routes are uniquely 
identified by their combination of route ID and sequence number. </li>
 <li><b>Class Information:</b> Each class has a unique class ID, associated train 
number, and number of seats per coach. Classes are uniquely identified 
by their combination of class ID and associated train number.  </li>
 <li><b>Train Fare Information:</b> Each train fare entry corresponds to a specific 
train, class, fixed charge, and distance charge. Train fares are uniquely 
identified by their combination of train number and class ID.   </li>
 <li><b>Coach Information:</b> Each coach has a unique coach number, associated 
train number, and class ID. Coaches are uniquely identified by their 
combination of coach number, associated train number, and class ID.</li>
 <li><b>Login Details:</b> Each user has a unique username, name, and mobile 
number. Users are uniquely identified by their username. </li>
 <li><b>Ticket Information:</b> Each ticket has a unique PNR (Passenger Name 
Record), date of travel, boarding station, destination station, associated 
train number, fare, username, and class ID. Tickets are uniquely identified 
by their PNR.  </li>
 <li><b>Payment Information:</b> Each payment has a unique payment ID, 
associated PNR, payment date, payment amount, and payment mode. 
Payments are uniquely identified by their payment ID. </li>
 <li><b>Passenger Booking Information:</b> Each passenger booking entry 
corresponds to a specific PNR, passenger name, age, gender, mobile 
number, and booking status. Passenger bookings are uniquely identified 
by their combination of PNR and passenger name. </li>
<li><b>Waiting List Information:</b> Each waiting list entry corresponds to a 
specific PNR, passenger name, and waiting number. Waiting list entries 
are uniquely identified by their combination of PNR and waiting number.</li>
</ul>