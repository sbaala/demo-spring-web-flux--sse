# SpringWebFluxServerEvent

Spring reactive web flux server event is like a websocket. Whenever you receive some events server side immediately you can send the data to dashboard or another event or service. 

This example will demonstrate if you receive the send resource action immediately it will send the data to events api.

Import this project as maven project then start the server. Netty server started in the port 8443.

Enter the below url in browser

http://localhost:8443/freebies/events


Then hit the below url in another tab or through rest client

http://localhost:8443/freebies/send

Another use case you can pass any parameter in the below URL

http://localhost:8443/freebies/request?param1="Bala"

you will get the output in the events tab 

data:Your input "Bala"

then you see the response in the events tab. Client side you can use EventSource to implement the real time data to the dashboard

This project is like sample how it works with server side events. The same way you can pass any object send to the dashboard.

Any doubts mail me @ balachandar.bdu@yahoo.com
