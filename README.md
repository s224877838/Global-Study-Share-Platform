The steps to run docker include:

Clone the GIT Project Repository.

In the terminal 'run npm install'.

Then run 'npm install node'.

Install docker as follows:
Windows: https://docs.docker.com/desktop/setup/install/windows-install/                                                                
Ubuntu: https://docs.docker.com/engine/install/ubuntu/

Run the command
"docker build -f backend/Dockerfile -t express-docker-app ."

Then run the command
"docker run -p 3000:3000 express-docker-app"

Open the browser and access the port:
"http://localhost:3000/api/student"

The output displayed there would be:
{ "name": "Levin Jospeh Poovakulath", "studentId" : "s224877838" }

run 'docker ps' to get detils of the docker container rumming
