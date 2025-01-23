# Docker and (Springboot configuration) and API 

# Design
## How to track event consumed 
* offset : track consumed position - easy to rewind back : user cases of rewind back? 
### Analyze Pull vs Push model
* How push-based model can introduce latency? 
### Consumed position
#### broker-oriented approach
* how broker mark the message has been consumed - consider machine fail cases  
### Kafka approach : Offset
* topics - **totally-ordered** partition 

# distributed system and deployment