<h1><p align="center"> Simple Microservices Application</p></h1>

![image](https://github.com/user-attachments/assets/9cc8efeb-6ee0-4fa1-886e-9d7107eb0ee9)<br>
1. I have created a main directory named "microservices-app" along with two subdirectories: "frontend" and "backend" to organize my application components. <br>
   **commands:** `mkdir microservices-app && mkdir microservices-app/frontend && mkdir microservices-app/backend`
   
![image](https://github.com/user-attachments/assets/da02026c-0309-470f-b827-150522c42e9e)<br>
2. I opened the nano text editor to create an index.html file in the frontend directory. This file will serve as the entry point for my front-end application. <br>
   **commands:** `nano index.html`
   
![image](https://github.com/user-attachments/assets/f718b32b-dc10-49e2-9d53-db9db19d9c42)<br>
3. This step involves creating a nginx configuration file to define how the web server will route traffic to frontend and backend services. <br>
   **commands:** `nano nginx.conf`
   
![image](https://github.com/user-attachments/assets/5d0853cf-62f3-47aa-b99b-56eae9f2f40b)<br>
4. I created a Dockerfile for the frontend service, specifying how to build the frontend container image.<br>
   **commands:** `nano Dockerfile`

![image](https://github.com/user-attachments/assets/9a23c407-b2f8-4607-bf23-7c87a188962f)<br>
5. I navigated to the backend directory to set up the backend file.<br>
   **commands:** `cd ..`, `cd backend/` and `nano app.js`
   
![image](https://github.com/user-attachments/assets/18dea507-965f-45cb-8661-ff8c3bee9397)<br>
6. I created a Dockerfile for the backend service, specifying how to build the backend container image.<br>
   **commands:** `nano Dockerfile`
   
![image](https://github.com/user-attachments/assets/ec052306-9fbe-48fc-a0cd-4adf9e8436e8)<br>
7. This step involves creating a package.json file that manages the dependencies for backend application.<br>
   **commands:** `nano package.json`
   
![image](https://github.com/user-attachments/assets/d1432979-e513-4050-b9bf-9173c5380110)<br>
8. I created a docker-compose.yml file that defines how the different services (frontend and backend) will be configured and run together.<br>
   **commands:** `nano docker-compose.yml`
   
![image](https://github.com/user-attachments/assets/4ce6b35b-4f88-49d1-9f18-5ec39c5417dd)<br>
9. I build and start the application using Docker Compose, setting up the containers as defined in your docker-compose.yml file.<br>
    **commands:** `docker-compose up --build`  

**<p align="center"> TESTING PHASE</p>**

![image](https://github.com/user-attachments/assets/1390c4fd-03b4-46a6-a29a-238112fcc69d)
Verify running containers using `docker-compose ps`. The services are up and running.




