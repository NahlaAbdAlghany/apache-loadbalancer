# Creating a single HAProxy and two Apache containers with Docker compose
> In this porject I created two identical Apache servers and one HAProxy container to balance the traffic load to more than microservices based on a simple Round-Robin.

### Example:
- Hit 1  → Forward to the 1st microservice 
- Hit 2 →  Forward to the 2nd microservice

![Alt text](https://img.hotimg.com/laodbalancer.png)
