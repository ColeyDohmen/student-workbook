02/18/2021

What problems does the Observer Pattern seek to solve? It seeks to solve one-to-many, one-way, and event-driven data binding. 

What are the three mechanisms of the observer pattern? Subscribe, unsubscribe, and broadcast/notify.

Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom. 
It uses proxy objects, getters and setters, to access the data that we keep with the observer pattern. Proxy objects help us grab data on the observer pattern and use it throughout MVC.