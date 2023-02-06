# Lab 2
[Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repo and clone it to your machine to get started!

## Team Members
- team member 1
- team member 2

## Lab Question Answers
Question 1: How did the reliability of UDP change when you added 50% loss to your local environment? Why did this occur?

Answer for Question 1: 	
With a 50% loss, the reliability of the UDP decreased as every other sequence was dropped when it was communicated (does not send or recover). This occurs because by design, the UDP is unreliable as it sends the packet of information once without needing acknowledgement that the information was receieved. Only half of the messages are printed server side --> 50% chance of being drop 


Question 2: How did the reliability of TCP change? Why did this occur?

Answer for Question 2:
TCP reliability will mostly remain unchanged as it will send all of the sequence but at a slower rate with the loss. TCP waits for an acknowlegdment that a packet is received.


Question 3: How did the speed of the TCP response change? Why might this happen?

Answer for Question 3: 
With a 50% loss, the speed of the TCP response was slower as every sequence was sent when it was prompted. More had to be sent due to packet loss. 
