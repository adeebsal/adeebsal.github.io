# List of artifacts I could show
- Zillow-esque home pricing estimates in Python machine learning
- reunion cafe website
- minecraft-kubernetes
- raspberry pi menuboard
-

This is a selection of software projects I have worked on for classes and personal use. All of these are available as repositories on my [GitHub page](https://github.com/adeebsal)

# [Home Value Predictor](https://github.com/adeebsal/homevaluepredictor)
This was done as a pair project for a business data analytics course, ECO4444. The goal is to take in a dataset including houses, their prices, and various statistics such as square footage, distance from the nearest central business district, and their age, and create a model that can predict the price based on the other variables. From there, we were given a validation dataset of completely new data, and had to apply our generated model to predict the prices of those properties.

# [Minecraft on Kubernetes](https://github.com/adeebsal/minecraft-kubernetes)
This is a personal project that was borne from a need for a Minecraft server in my friend group, but I used it as an opportunity to learn Docker and similar app containerization systems, and Kubernetes as a container and microservice orchestration system. The Kubernetes deployment makes use of a prebuilt Docker image the contains the minecraft server and all of its dependencies, available at [itzg/docker-minecraft-server](https://github.com/itzg/docker-minecraft-server). The deployment uses this container and sets up a persistent storage volume, networking, liveness checks, and environment variables for the container to attach to and use as inputs. This results in a streamlined Minecraft server setup, and allowed me to gain skills in microservices management while doing something fun. 

# [Reunion Cafe Website](https://github.com/adeebsal/reunioncafe-website)

