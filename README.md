<h1>Using "ping" (3 pts)</h1>
    
<h2>What were the min/avg/max/stddev statistics for each?</h2>

|Company    |Min    |Avg    |Max    |Stddev |
|---        |---    |---    |---    |---    |
|Amazon     |11ms   |13ms   |15ms   |1.700  |
|Google     |12ms   |13ms   |14ms   |0.816  |
|Microsoft  |12ms   |15ms   |20ms   |3.399  |

<h2>Was there any packet loss on any of the pings?</h2>
no packet losses for any website

<h2>Did the IP address change for a given website between pings?</h2>
yes, the IP address changes every so often


<h1>Using "tracert" (2 pts)</h1>
<h2>What was the target server's IP address?</h2>

|Company    |Target IP Address  |
|---        |---                |
|Amazon     |18.172.169.208     |           
|Google     |142.251.33.100     |
|Microsoft  |23.44.161.156      |

<h2>How many hops were needed to reach the target?</h2>

|Company    |Hops   |
|---        |---    |
|Amazon     |16     |           
|Google     |11     |
|Microsoft  |12     |

<h2>Can you identify your ISP from the intermediate server DNS names?</h2>
most of the time, somes of the nodes are named ...seattle.wa.seattle.comcast.net which indicates that I am using comcast as my ISP. Sometimes however, the IP addresses don't have a clear indication of what the ISP is.

<h2>Identify the "class" of IP address for each major step in the trip</h2>
<h3>Amazon</h3>

|IP Address         |Class  |
|---                |---    |
|192.168.0.1        |C      |
|100.92.123.67      |A      |
|24.153.87.25       |A      |
|69.139.164.81      |A      |
|69.139.160.249     |A      |
|24.124.128.121     |A      |
|68.86.93.13        |A      |
|96.110.39.230      |A      |
|75.149.228.150     |A      |
|Request timed out. |NA     |
|Request timed out. |NA     |
|Request timed out. |NA     |
|Request timed out. |NA     |
|Request timed out. |NA     |
|15.230.247.0       |A      |
|18.172.169.208     |A      |

<h3>Google</h3>

|IP Address         |Class  |
|---                |---    |
|192.168.0.1        |C      |
|100.92.123.66      |A      |
|24.153.87.17       |A      |
|69.139.160.198     |A      |
|69.139.164.81      |A      |
|69.139.160.249     |A      |
|24.124.128.121     |A      |
|50.218.57.26       |A      |
|142.251.50.43      |B      |
|142.251.50.175     |B      |
|142.251.33.100     |B      |

<h3>Microsoft</h3>

|IP Address         |Class  |
|---                |---    |
|192.168.0.1        |C      |
|100.92.123.66      |A      |
|24.153.87.17       |A      |
|69.139.160.198     |A      |
|69.139.164.81      |A      |
|69.139.160.249     |A      |
|24.124.128.121     |A      |
|68.86.93.9         |A      |
|96.110.32.234      |A      |
|23.30.207.90       |A      |
|23.203.145.137     |A      |
|23.44.161.156      |A      |

<h1>Extra credit: Using "ngrok" (2 pts)</h1>
<img src="ngrok/Capture.jpg">

<h1>Extra credit: Using packet-capture tools (2 pts)</h1>
<img src="wireshark/Capture.jpg">

<h1>Extra credit: Insecure web server (2 pts)</h1>
<img src="insecurewebserver/Capture.jpg">