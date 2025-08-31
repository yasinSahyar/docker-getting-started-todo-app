# Docker Tutorial Steps

# Cloned the todo app:

git clone https://github.com/docker/getting-started-todo-app.git
cd getting-started-todo-app

# Installed dependencies:

cd backend
npm install
cd ../client
npm install
cd ..

# Ran the app with Docker Compose:

docker-compose up --watch

# Checked the app:
Frontend: http://localhost

![](images/docker001.png)

# Build and Run Production Image
docker build -t my-node-app:v1 .
 ![](images/dockerBUILD3.png)


# Ran locally:

npm run dev
 ![](images/docker002.png) 


 # Ran with Docker Compose:

docker-compose up --watch

#
 ![](images/helloDocker5.png)
 ![](images/chalange4.png) 



