
# Recipe App Backend

A fully functional backed for recipe app which can be used by mobile or web applications. A user can perform CRUD operations i.e create, read, update and delete a recipe, apart from this user can filter out recipes based on tags and ingredients.

## ER Diagram of the Application

![ER diagram](https://user-images.githubusercontent.com/87746680/233376436-d61cbf7e-d05a-4455-9544-e5360b17655e.PNG)

## CI/CD Workflow Diagram

![CICD workflow](https://user-images.githubusercontent.com/87746680/233377880-6bca8b8d-43e0-45eb-a165-6108586cf2cf.PNG)
  

## Run Locally
Python, Docker and docker-compose must be installed in your system to run this application. The installation commands/link for python and docker are as follows:
 
Python : https://www.python.org/downloads/

Docker : https://docs.docker.com/desktop/install/windows-install/

docker-compose: https://docs.docker.com/compose/install/
<br />

Step 1: Clone the project

```bash
  git clone https://github.com/lucky-7865/recipe-app-backend.git
```

Step 2: Go to the project directory

```bash
  cd recipe-app-backend
```

Step 3: Install dependencies

```bash
  pip install -r requirements.txt
```

Step 4: Start the server

```bash
  docker-compose up
```
The server will get Start on localhost:8080. You can access the documentation of the api on http://localhost:8000/api/docs/ while the server is ON
### The API documentation will looks like:
You can play around with the APIs as per your need
  
![documentation1](https://user-images.githubusercontent.com/87746680/233294261-04a43d7e-503e-427e-93ee-a9bb1ebfabf6.PNG)
![documentation2](https://user-images.githubusercontent.com/87746680/233294560-625a608d-7310-4ecf-ada3-8f81154c3e82.PNG)

