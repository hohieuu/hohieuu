What are the common load-balancing algorithms?

The diagram below shows 6 common algorithms.
🔹 Static Algorithms
1. Round robin
The client requests are sent to different service instances in sequential order. The services are usually required to be stateless.

2. Sticky round-robin
This is an improvement of the round-robin algorithm. If Alice’s first request goes to service A, the following requests go to service A as well.

3. Weighted round-robin
The admin can specify the weight for each service. The ones with a higher weight handle more requests than others.

4. Hash
This algorithm applies a hash function on the incoming requests’ IP or URL. The requests are routed to relevant instances based on the hash function result.

🔹 Dynamic Algorithms
5. Least connections
A new request is sent to the service instance with the least concurrent connections.

6. Least response time
A new request is sent to the service instance with the fastest response time.

![image](https://github.com/hohieuu/hohieuu/assets/55455388/ab9c0841-1a38-4e1c-9cc9-630e8e16d5b3)

# Refs
https://www.linkedin.com/posts/bytebytego_systemdesign-coding-interviewtips-activity-7092018678958800896-lRvB?utm_source=share&utm_medium=member_desktop
