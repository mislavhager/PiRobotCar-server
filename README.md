# PiRobotCar-server
Server in node.js for getting android app sensor data to control robotic vehicle, it runs on the raspberry pi to get direction values from the [android app here](https://github.com/mkovacek07/PiRobot-car-andriod-app).

According to the direction given by the android app(received using socket.io), server sends GPIO commands to move the car accordingly.

# Technology used
  1. [Node.js](https://nodejs.org/)
  2. [socket.io](https://socket.io)
  3. [Express](https://expressjs.com/)
  4. [Johnny-Five](http://johnny-five.io/)
