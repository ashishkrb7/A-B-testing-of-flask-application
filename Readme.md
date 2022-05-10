# ⚡ Load balancing tool for A/B testing of flask application

## 👉 Different types of testing
![](./docs/how%20to%20deploy%20services.jpg)

## Workflow diagram

![](./docs/load%20balancer.png)

## 👉 Folder structure

```
    D:.
    │   docker-compose.yml
    │   Readme.md
    │
    ├───app1
    │       app1.py
    │       Dockerfile
    │       requirements.txt
    │
    ├───app2
    │       app2.py
    │       Dockerfile
    │       requirements.txt
    │
    ├───docs
    │       how to deploy services.jpg
    │
    └───nginx
            Dockerfile
            nginx.conf
```

## 👉 How to use ?
- Start the docker desktop in your machine
- To launch the APP, just open a terminal at the same level with docker-compose.yml, and execute : 
    ```
    docker-compose up
    ```

- This will spin up the dockerised architecture. After that, you need to open a browser and tape : 
    ```
    http://localhost:8080
    ```
- It will redirect 60% traffic to app1 and 40% traffic to app2.
- To quit, you can just CTRL + C in the terminal and it will stop the application and destroy the created containers.

## 📜 Release History

* 0.0.1
    * Tool for A/B testing and load balancing

## ✍️ Author

Ashish Kumar

[![LinkedIn](https://img.shields.io/badge/-Ashish%20Kumar-blue?style=social&logo=Linkedin&logoColor=blue&link=https://www.linkedin.com/in/ashishkrb7/)](https://www.linkedin.com/in/ashishkrb7/) 
[![Gmail](https://img.shields.io/badge/-Ashish%20Kumar-c14438?style=social&logo=Gmail&logoColor=red&link=mailto:ashishkrb7@gmail.com)](mailto:ashishkrb7@gmail.com)
