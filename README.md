The steps to run docker include:

Clone the GIT Project Repository.

In the terminal 'run npm install express'.

Change directory to backend adn run node server.js. 

Install docker as follows:
Windows: https://docs.docker.com/desktop/setup/install/windows-install/                                                                
Ubuntu: https://docs.docker.com/engine/install/ubuntu/

Run the command
"docker-compose up --build"

Open the browser and access the port:
"http://localhost:3000/api/student"

"http://localhost:3000/api/questions"

"http://localhost:3000/api/users"

The output displayed there would be:
{ "name": "Levin Jospeh Poovakulath", "studentId" : "s224877838" }

{"data": [], "currentPage": 1, "totalPages": 0, "totalQuestions": 0}

{"message": "Unauthorized"}

run 'docker ps' to get detils of the docker container running
