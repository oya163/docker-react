# Docker & Kubernetes

## Applications

### [fibonacci](https://github.com/oya163/docker-react/tree/main/fibonacci)
- A simple React app to calculate fibonacci value at a given index.
- This app utilizes multiple docker containers which includes images of Nginx, NodeJS (Express), ReactJS (client), Worker, Redis and Postgres.

### [frontend](https://github.com/oya163/docker-react/tree/main/frontend)
- A simple React app based on multi-phase single docker container.
- This project shows the difference between dev vs prod deployment.
- It utilizes docker-compose to build projects
- It uses Travis CI to build, test and deploy the apps on AWS Elastic Beanstalk.

### [redis-image](https://github.com/oya163/docker-react/tree/main/redis-image)
- A simple docker container to pull Redis image from docker hub.

### [simple-web](https://github.com/oya163/docker-react/tree/main/simple-web)
- A simple web app deployment using docker container.

### [simplek8s](https://github.com/oya163/docker-react/tree/main/simplek8s)
- Kubernetes configuration to setup the cluster based on objects types - pods (dev) and deployment (prod).
- Images are pulled from Docker hub.
- Kubernetes manages the declarative deployment.

### [visits](https://github.com/oya163/docker-react/tree/main/visits)
- A simple web app deployment using docker container to count the number of this page visits.
- It stores the count using in-memory data structure called Redis.


#### References
Special thanks to Stephen Grider for teaching this [course](https://www.udemy.com/course/docker-and-kubernetes-the-complete-guide) wonderfully.
