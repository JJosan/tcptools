<h1>Using "ping" (3 pts)</h1>
    
<h2>What were the min/avg/max/stddev statistics for each?</h2>

|Company    |Min    |Avg    |Max    |Stddev |
|---        |---    |---    |---    |---    |
|Amazon     |10ms   |10ms   |11ms   |0.577  |
|Google     |17ms   |19ms   |24ms   |4.041  |
|Microsoft  |12ms   |16ms   |19ms   |3.786  |

<h2>Was there any packet loss on any of the pings?</h2>
no packet losses for any website

<h2>Did the IP address change for a given website between pings?</h2>
yes, the IP address changes every so often


<h1>Using "tracert" (2 pts)</h1>
<h2>What was the target server's IP address?</h2>

|Company    |Target IP Address                      |
|---        |---                                    |
|Amazon     |2600:9000:24ec:1a00:7:49a5:5fd2:8621   |           
|Google     |2607:f8b0:400a:805::2004               |
|Microsoft  |2001:559:19:28a8::356e                 |

<h2>How many hops were needed to reach the target?</h2>

|Company    |Hops   |
|---        |---    |
|Amazon     |16     |           
|Google     |12     |
|Microsoft  |8      |

<h2>Can you identify your ISP from the intermediate server DNS names?</h2>
sometimes, somes of the nodes are named ...seattle.wa.seattle.comcast.net which indicates that I am using comcast as my ISP. However, the microsoft trace route does not have a clear indication of my ISP because all the IPs don't say a provider

<h2>Identify the "class" of IP address for each major step in the trip</h2>
