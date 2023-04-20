
# Recipe App Backend

A fully functional backed for recipe app which can be used by mobile or web applications. A user can perform CRUD operations i.e create, read, update and delete a recipe, apart from this user can filter out recipes based on tags and ingredients.
  

## Run Locally
Python, Docker and docker-compose must be installed in your system to run this application. The installation commands/link for python and docker are as follows:
 
Python : https://www.python.org/downloads/

Docker : https://docs.docker.com/desktop/install/windows-install/

docker-compose: https://docs.docker.com/compose/install/

Clone the project

```bash
  git clone https://github.com/lucky-7865/recipe-app-backend.git
```

Go to the project directory

```bash
  cd recipe-app-backend
```

Install dependencies

```bash
  pip install -r requirements.txt
```

Start the server

```bash
  docker-compose up

  The server will get Start on localhost:8080. You can access the documentation of the api on http://localhost:8000/api/docs/ while the server is ON

```

