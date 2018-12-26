# Flask-Blog
A Blog Project

| Endpoint                | Functionality                  | HTTP Method |
|........................|.................................|


| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| Github | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

|Endpoint | Functionality|HTTP METHOD|
| ------- | ------------ |-----------|
|POST /auth/signup       | Register a user|POST|
|POST /auth/signup       |Register a user|POST|
|POST /auth/login        |Login a use|POST|
|GET /questions          |Fetch all questions|GET|
|GET /questions/<questionId> |Fetch a specific question|GET|
|POST /questions         |Post a question|POST|
|Delete /questions/<questionId>|Delete a question|DELETE|
|POST /questions/<questionId>/answers|Post an answer to a question|POST|
|PUT /questions/<questionId>/answers/<answerId>|Mark an answer as accepted|PUT|