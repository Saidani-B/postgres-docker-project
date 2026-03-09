# postgres-docker-project
we are learning Git , GitHub, and Docker

Description:
This project demonstrates how to run a PostgreSQL atabes inside Docker using Docker Compose .
The database contains a simple users table (name,email,password) .
This project is userful for learning how to run postgreSQL with Docker , initialize a databese using SQL scripts , and manage database containers
This project also uses Git with GitHub for version control 
The following Git commands were used during development: git init, git add, git commit, git push, ....
Additionally, some Linux terminal commands were used to create and manage files: mkdir, touch, cd, ....

How To Run The Project : 
1- clone the repository : 
git clone <link>
cd postgres-docker-project
2- Start the container:
docker compose up -d 
3- check running containers:
docker ps 
Example Query: 
INSERT INTO users (name, email, password) VALUES ('user-name', 'name@gmail.com', '000000');
SELECT * FROM users;
