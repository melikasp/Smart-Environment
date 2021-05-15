# Smart-Environment

first challenge:
In the dataset you have the packets received gateways which are placed in different areas (indoor, outdoor, etc.). The positioning of the gateways will influence how many packets they receive and their radio indicators such as RSSI and SNR.

Moreover, in LoRa the Spreading Factor (SF) parameter controls the time-on-air of a packet. The higher SF is, the more probable is for a gateway to receive a packet.

- Derive the distribution of the RSSI and SF for each gateway

second challenge:
Some packets could be dropped by the network for various reasons: collisions, interference, etc…

- Compute the ratio of lost packets

third challenge:
The packets of a device could be heard by more than one gateway, in order to use the services provided by LoRaWAN as best as possible.

We are interested in seeing how a device distributes its messages and with each frequence a device interacts we the same server.

- Derive the distribution of gateways seen by each device and find the interarrival time between packets sent by a given device to a given gateway

In order to solve this challenge let's consider that each device address identifies a unique device.

