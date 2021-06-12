# Docker Network Commands

This read me is more related to the docker networking things. I will try to list down all the important commands used in docker networking in this read me file. 



## Command 1 (list networks)
To list down currenty running networks

```
docker network ls
```

## Command 2 (Create docker network)
To create a docker network use this command

```
docker network create my_app_net 
```
* **my_app_net** : Name of the network

## Command 3 (Run Container in a specefic network)
If you want to run a container in specefic network than use this command

```
docker container run -d --name new_nginx --network my_app_net nginx
```

# Author 

* Sohaib Anwaar
* gmail          : sohaibanwaar36@gmail.com
* linkedin       : [Have Some Professional Talk here](https://www.linkedin.com/in/sohaib-anwaar-4b7ba1187/)
* Stack Overflow : [Get my help Here](https://stackoverflow.com/users/7959545/sohaib-anwaar)
* Kaggle         : [View my master-pieces here](https://www.kaggle.com/sohaibanwaar1203)

# Helping Material

* Udemy -> Docker Mastery with kubernetes + swarm from a Docker Captain