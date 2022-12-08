# RedisIPThresholdBlocker
This code uses Redis to store and track IP addresses, and will block any IP address that exceeds a specified threshold.
This code isca simple script for monitoring incoming network packages and blocking IP addresses that exceed a certain threshold.
It uses the redis library to connect to a Redis database and increment counters for each incoming IP address. 
When the counter for an IP address exceeds the threshold, the code will block the IP address and reset its counter.
The Redis database is hosted on the local machine, on port 6379 and in database 0.
