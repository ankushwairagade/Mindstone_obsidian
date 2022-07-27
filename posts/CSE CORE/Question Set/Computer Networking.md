 >Stop and Wait Protocol  Question

Question . If the bandwidth of the line is 1.5 Mbps, RTT is 45 msec and packet size is 1 KB, then find the link utilization in stop and wait.                      
sol- 10.8 %

Question.  A channel has a bit rate of 4 Kbps and one way propagation delay of 20 msec. The channel uses stop and wait protocol. The transmission time of the acknowledgement frame is negligible. To get a channel efficiency of at least 50%, the minimum frame size should be-

a.  80 bytes
b.  80 bits
c.  160 bytes
d.  160 bits        --> correct

Question.  What is the throughput achievable in stop and wait protocol by a maximum packet size of 1000 bytes and network span of 10 km.

Assume the speed of light in cable is 70% of the speed of light in vaccum.
sol - 10.5MBps

Question. If the packet size is 1 KB and propagation time is 15 msec, the channel capacity is 109 b/sec, then find the transmission time and utilization of sender in stop and wait protocol.
Sol-   0.00341 %

Question. Consider a MAN with average source and destination 20 Km apart and one way delay of 100 μsec. At what data rate does the round trip delay equals the transmission delay for a 1 KB packet?
sol- Bandwidth = 5.12 MBps or 40.96 Mbps

Question.  Consider two hosts X and Y connected by a single direct link of rate 106 bits/sec. The distance between the two hosts is 10,000 km and the propagation speed along the link is 2 x 108 m/sec. Host X sends a file of 50,000 bytes as one large message to host Y continuously. Let the transmission and propagation delays be p milliseconds and q milliseconds respectively.

Then the value of p and q are-
1.  p = 50 and q = 100
2.  p = 50 and q = 400
3.  p = 100 and q = 50
4.  p = 400 and q = 50    -> correct

Question. The values of parameters for the stop and wait ARQ protocol are as given below-

-   Bit rate of the transmission channel = 1 Mbps
-   Propagation delay from sender to receiver = 0.75 ms
-   Time to process a frame = 0.25 ms
-   Number of bytes in the information frame = 1980
-   Number of bytes in the acknowledge frame = 20
-   Number of overhead bytes in the information frame = 20

Assume that there are no transmission errors. Then the transmission efficiency (in %) of the stop and wait ARQ protocol for the above parameters is ___________ . (correct to 2 decimal places)

sol --> 88.33%

Question. A sender uses the stop and wait ARQ protocol for reliable transmission of frames. Frames are of size 1000 bytes and the transmission rate at the sender is 80 Kbps. Size of an acknowledgement is 100 bytes and the transmission rate at the receiver is 8 Kbps. The one way propagation delay is 100 msec.

Assuming no frame is lost, the sender throughput is __________ bytes/sec.
Sol--> 2500 bytes/sec

Question.  Using stop and wait protocol, sender wants to transmit 10 data packets to the receiver. Out of these 10 data packets, every 4th data packet is lost. How many packets sender will have to send in total?

Sol-->   The lost packets are- 4, 7 and 10.

Thus, sender will have to send 13 data packets in total.




> Sliding Window Protocol -


Question. 
A 3000 km long trunk operates at 1.536 Mbps and is used to transmit 64 byte frames and uses sliding window protocol. If the propagation speed is 6 μsec / km, how many bits should the sequence number field be?
sol --> 7bits

Question.
Compute approximate optimal window size when packet size is 53 bytes, RTT is 60 msec and bottleneck bandwidth is 155 Mbps.
Sol --> 21938.84

Question. 
A sliding window protocol is designed for a 1 Mbps point to point link to the moon which has a one way latency (delay) of 1.25 sec. Assuming that each frame carries 1 KB of data, what is the minimum number of bits needed for the sequence number?
Sol --> 9 bits

Question. 
Host A is sending data to host B over a full duplex link. A and B are using the sliding window protocol for flow control. The send and receive window sizes are 5 packets each. Data packets (sent only from A to B) are all 1000 bytes long and the transmission time for such a packet is 50 μs. Acknowledgement packets (sent only from B to A) are very small and require negligible transmission time. The propagation delay over the link is 200 μs. What is the maximum achievable throughput in this communication?

1.  7.69 x 106 Bps
2.  11.11 x 106 Bps     --> correct
3.  12.33 x 106 Bps
4.  15.00 x 106 Bps


Question.
Station A uses 32 byte packets to transmit messages to station B using a sliding window protocol. The round trip delay between A and B is 80 msec and the bottleneck bandwidth on the path between A and B is 128 Kbps. What is the optimal window size that A should use?

1.  20
2.  40    --> correct
3.  160
4.  320




> Go Back N Protocol

Question.
A 20 Kbps satellite link has a propagation delay of 400 ms. The transmitter employs the “go back n ARQ” scheme with n set to 10.

Assuming that each frame is 100 bytes long, what is the maximum data rate possible?

1.  5 Kbps
2.  10 Kbps    --> correct
3.  15 Kbps
4.  20 Kbps

Question.
Consider the Go back N protocol with a sender’s window size of ‘n’. Suppose that at time ‘t’, the next inorder packet the receiver is expecting has a sequence number of ‘K’. Assume that the medium does not reorder messages.

Answer the following questions-

What are the possible sets of sequence numbers inside the sender’s window at time ‘t’. Assume the sender has already received the ACKs.

1.  [K-1, K+n-1]
2.  [K, K+n-1]     --> correct
3.  [K, K+n]
4.  [K+n, K-1]

If acknowledgements are still on their way to sender, what are all possible values of the ACK field in the messages currently propagating back to the sender at a time ‘t’?

1.  [K-n, K-1]
2.  [K-1, K-n]
3.  [K, K-n]    --> correct
4.  [K-n, K+1]


Question.
Station A needs to send a message consisting of 9 packets to station B using a sliding window (window size 3) and go back n error control strategy. All packets are ready and immediately available for transmission.

If every 5th packet that A transmits gets lost (but no ACKs from B ever get lost), then what is the number of packets that A will transmit for sending the message to B?

1.  12
2.  14
3.  16   --> correct
4.  18

Question.
In Go back 4, if every 6th packet that is being transmitted is lost and if total number of packets to be sent is 10, then how many transmissions will be required?

Question.
A 1 Mbps satellite link connects two ground stations. The altitude of the satellite is 36504 km and speed of the signal is 3 x 108 m/sec. What should be the packet size for a channel utilization of 25% for a satellite link using go back 127 sliding window protocol?

1.  120 bytes    --> Correct
2.  60 bytes
3.  240 bytes
4.  90 bytes


Question.
  
Consider a network connecting two systems located 8000 km apart. The bandwidth of the network is 500 x 106 bits per second. The propagation speed of the media is 4 x 106 meters per second. It is needed to design a Go back N sliding window protocol for this network. The average packet size is 107 bits. The network is to be used to its full capacity.

Assume that processing delays at nodes are negligible. Then, the minimum size in bits of the sequence number field has to be ______ ?   
sol---> 8bits



> Selective Repeat Protocol

Question.
The maximum window size for data transmission using the selective repeat protocol with n bit frame sequence numbers is-

1.  2n
2.  2n-1  --> c
3.  2n-1
4.  2n-2

Question.
In SR protocol, suppose frames through 0 to 4 have been transmitted. Now, imagine that 0 times out, 5 (a new frame) is transmitted, 1 times out, 2 times out and 6 (another new frame) is transmitted.

At this point, what will be the outstanding packets in sender’s window?

1.  341526
2.  3405126   --> c
3.  0123456
4.  654321


Question.
The selective repeat protocol is similar to Go back N except in the following way-

1.  Frame Formats are similar in both the protocols
2.  The sender has a window defining maximum number of outstanding frames in both the protocols
3.  Both uses piggybacked acknowledgements where possible and does not acknowledge every frame explicitly.
4.  Both uses piggyback approach that acknowledges the most recently received frame

Question.
Consider a 128 x 103 bits/sec satellited communication link with one way propagation delay of 150 msec. Selective Retransmission (repeat) protocol is used on this link to send data with a frame size of 1 KB. Neglect the transmission time of acknowledgement. The minimum number of bits required for the sequence number field to achieve 100% utilization is ________ .
sol--> 4



> Flow Control Protocol

Question.
In what protocols is it possible for the sender to receive an acknowledgement for a packet that falls outside its current window?

1.  Stop and Wait
2.  Selective Repeat
3.  Go back N
4.  All of the above  -> c

Question.
On a wireless link, the probability of packet error is 0.2. A stop and wait protocol is used to transfer data across the link. The channel condition is assumed to be independent from transmission to transmission. What is the average number of transmission attempts required to transfer 100 packets?

1.  100
2.  125   -> c
3.  150
4.  200


Question.
Compute the fraction of the bandwidth that is wasted on overhead (headers and retransmissions) for a protocol on a heavily loaded 50 Kbps satellite channel with data frames consisting of 40 bits header and 3960 data bits. Assume that the signal propagation time from the earth to the satellite is 270 msec. ACK frames never occur. NAK frames are 40 bits. The error rate for data frames is 1% and the error rate for NAK frames is negligible.

1.  1.21 %
2.  2.12 %
3.  1.99 %  --> c
4.  1.71 %

Question.
Consider 1 Mbps error free line. The maximum frame size is 1000 bits. New packets are generated about 1 sec apart. The time out interval is 10 msec. If the ack timer is eliminated. How many times the average message be transmitted?

1.  Only once
2.  Twice
3.  Thrice
4.  Can’t say   -->c

Question.
What is the effect on line utilization if we increase the number of frames for a constant message size?

1.  Lower line efficiency
2.  Higher line efficiency
3.  No change in line efficiency
4.  No relation between line efficiency and frame size