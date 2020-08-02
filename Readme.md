### Without Docker
Update local/cloud Mongodb link in the file: database.config.js

npm i

npm start

CRUD:

POST: http://localhost:8080/notes/

Body: {
	"title": "test",
	"content": "test1"
}

GET: http://localhost:8080/notes/

PUT: http://localhost:8080/notes/{id}

DELETE: http://localhost:8080/notes/{id

### With Docker
Update docker Mongodb link in the file: database.config.js

npm i

Build Image (on VS Code, right click on 'Dockerfile' and select 'Build Image')

Start Docker-compose: docker-compose -f "docker-compose.yaml" up -d --build

Stop Docker-compose: docker-compose down

Restart Docker-compose: docker-compose restart

CRUD: Same as above

Reference: https://www.callicoder.com/node-js-express-mongodb-restful-crud-api-tutorial/
