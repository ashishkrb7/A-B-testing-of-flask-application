# β‘ Load balancing tool for A/B testing of flask application

## π Different types of Deployment
![](./docs/how%20to%20deploy%20services.jpg)

## Workflow diagram

![](./docs/load%20balancer.png)

## π Folder structure

```
    D:.
    β   docker-compose.yml
    β   Readme.md
    β
    ββββapp1
    β       app1.py
    β       Dockerfile
    β       requirements.txt
    β
    ββββapp2
    β       app2.py
    β       Dockerfile
    β       requirements.txt
    β
    ββββdocs
    β       how to deploy services.jpg
    β
    ββββnginx
            Dockerfile
            nginx.conf
```

## π How to use ?
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

## π Release History

* 0.0.1
    * Tool for A/B testing and load balancing

## βοΈ Author

Ashish Kumar

[![LinkedIn](https://img.shields.io/badge/-Ashish%20Kumar-blue?style=social&logo=Linkedin&logoColor=blue&link=https://www.linkedin.com/in/ashishkrb7/)](https://www.linkedin.com/in/ashishkrb7/) 
[![Gmail](https://img.shields.io/badge/-Ashish%20Kumar-c14438?style=social&logo=Gmail&logoColor=red&link=mailto:ashishkrb7@gmail.com)](mailto:ashishkrb7@gmail.com)
