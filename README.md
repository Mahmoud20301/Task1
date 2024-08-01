# **ROS Service**
_A ROS service is a client/server system ,in our system we have topics to communicate with  two nodes ,first node called ***server*** (publisher) which wants to send data to second node with a request and second node called ***client*** (subscriber) which wants to receive data from first node and send a response back to the server._
# **Example**
_Let’s assume that we have a weather service online which can give us weather after we send our location In that example the weather service online is the server and you are the client. You will be able to access the server through an **HTTP request**, with a URL. Think as the HTTP URL as a ***ROS service***._ <br>
_First of all, your computer will send a request to the server. The request will contain a message, in this case your location. The server will then process the request, and send a response. The response will also contain a message._
_Keep in mind that the client's request must contain a location in order for the server to process the data and initiate communication. Additionally, if the server doesn't return a weather, the client won't understand  what's the response._

![image](https://github.com/user-attachments/assets/c31a0d25-7f66-4e5e-9965-c44c437e1120)

2.
https://app.diagrams.net/#HMahmoud20301%2FTask1%2Fmain%2Frobots.drawio#%7B%22pageId%22%3A%22C5RBs43oDa-KdzZeNtuy%22%7D

![Uploading image.png…]()


