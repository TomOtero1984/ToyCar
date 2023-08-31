# ToyCar

### Overview
Hobby project to build a DIY Toy Car. 

The car will be mostly 3D printed, with the cheapest motors and mechanical parts I can find. It's likely going to be an ESP32 or RPi brain (TBD). The control interface will be through an ASP.NET web app. It'd be nifty AF to have a little webcam attached to the car so the user could see a video stream on the web app.


### Currently Working On...

Developing the ASP.NET application. Both the front and backend will be constructed in the ASP.NET. Data storage will likely be cached in Redis and stored long term in Sqlite.

- Determine the design patterns to be used in this application
- Diagram the the different layers breaking down what actually needs to interact with what
- Develop the various components of the application
- Create a simple client websocket for testing purposes

To test this application, a simple websocket will be created on a local host. The local client will output the commands received and send back error and debug messages

The actual websocket to be used on the Toy Car is future work. However if the simple websocket is sufficient and can be used on the Toy Car it may be used

### High Level Future Work
- Develop the mechanical design
- Develop the electrical schematics
- Build a websocket reciever on whichever microcontroller/processor I decide on...
- Decide on a microcontroller/processor
- Develop a client websocket for the Toy Car
- Develop a controller on the Toy Car to handle the commands from the server

