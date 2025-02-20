# Akka Cluster Sharding

Inspiration 

I wanted to learn more about infrastructure at M1 Finance and I came across some blogs regarding the use of Akka, a distributed messaging system, as a part of the microservices architecture. This spurred me on to learn about CQRS design principles and I found about the original project for cluster sharding by Hugh Mckee and I thought how aesthetic the visualization for these interactions were. As a result, I wanted to add some documentation within the codebase for this project and add some neat functionality. 


Additions

Added querying functionality to the visualization to count ping statistics (will probably add more statistics querying)

![alt text](https://github.com/mfshi03/Akka-Cluster-Sharding/blob/main/docs/images/Screen%20Shot%202022-08-07%20at%209.53.05%20PM.png?raw=true)

Next up:
- [ ] Probably adding some stuff to the CLI
- [ ] Add a way to display values and change values of individual entitities like a real API server
- [ ] Custom-made cluster-sharding algorithm
