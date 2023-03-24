# NetSec_wireshark



## Description

So in our network we have two subnets 100.10.10.0/24 and 100.10.20.0/24 we want to sniff and analyse the packets using wireshark.

![image](https://user-images.githubusercontent.com/73224547/227597100-e2d929ca-e09f-4607-871c-5066e5419e05.png)


So after we create our virtual machines and give each machine an ip address we test with a ping and we sniff using wireshark.

![image](https://user-images.githubusercontent.com/73224547/227598915-41a5ee09-5674-43c7-ba2c-8f9bfb58f92d.png)

Wireshark is a network protocol analyzer that allows you to capture and inspect network traffic. To sniff a simple ping from 100.10.10.2 to 100.10.20.2 using Wireshark.

Source and Destination IP Addresses: The source IP address would be 100.10.10.2 and the destination IP address would be 100.10.20.2.

![image](https://user-images.githubusercontent.com/73224547/227598951-1af1b017-a9a6-4d63-9adc-509bdce487b8.png)


If you were to capture a ping from 100.10.10.2 to 100.10.20.2 using a network protocol analyzer such as Wireshark.

![image](https://user-images.githubusercontent.com/73224547/227600884-08181cdf-4f55-45db-8374-111ed5f9d147.png)

ICMP Message Type: The ICMP message type would be an "Echo Request" (type 8) message. This is the message sent by the device originating the ping to request a response from the destination device.

ICMP Message Type: The ICMP message type would be an "Echo Request" (type 8) message. This is the message sent by the device originating the ping to request a response from the destination device.

ICMP Message Code: The ICMP message code for an Echo Request message is usually 0.

Timestamps: The ping packet may include timestamps indicating when the packet was sent and received.

Packet Length: The length of the ping packet in bytes.


![image](https://user-images.githubusercontent.com/73224547/227601545-7d68034f-e6f2-4620-8c4b-618a987e437a.png)

![image](https://user-images.githubusercontent.com/73224547/227602112-5b124d45-41ed-46e2-ba57-9ff0fafe00d0.png)


Other details: The ping packet may include other details such as the time-to-live (TTL) value, which indicates how many hops the packet can take before it is discarded, as well as any additional data included in the ping packet.


![image](https://user-images.githubusercontent.com/73224547/227602407-e7dd011e-2dee-45d6-a279-82de159fa2a4.png)




Overall, when capturing a ping from 100.10.10.2 to 100.10.20.2, you would be able to see the source and destination IP addresses, the ICMP message type and code, timestamps, packet length, and any additional details included in the ping packet

