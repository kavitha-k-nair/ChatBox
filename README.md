# ChatBox
Sending and receiving of messages between two systems that are connected under the same WiFi network.

## Working
As mentioned above it is designed to send and receive messages simultaneously between two systems which are connected with their IP address and are within the same WiFi network.
One system can request to start the conversation which can be accepted or denied by the other end-user who waits for any connections. The users can also speak out their messages which gets converted to text and then can be sent. If any amongst two users wish to leave the conversation he/she can do it so by clickig on exit button which immediately informs to the other user that the person has left. (working on updates)

## Connections
A peer-to-peer network through socket connection(using Socket module), where any user amongst the two can request(receive) or respond(send) meassages.
