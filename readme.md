### Simple Flask Todo App

#### How to run the project local
<hr>

- Create python3 virtual environment and activate it (python3 -m venv venv)
- Run '. venv/bin/activate'
- Run 'pip install -r requirements.txt' on terminal
- Run 'python app.py' on terminal for start local server
- To stop the server press Ctrl + C
- To Exit from the virtual environment type 'deactivate' and press Enter

<hr>

#### Required Tasks

[ ] Push the project to github
[ ] make some changes on index.html, commit changes and push the changes to your repo.
[ ] connect the project to AWS RDS Server
[ ] write the app dockerfile
[ ] push the image to ECR
[ ] building and pushing the image using CircleCI

### RDS-Configuration

#### DB-Identifier
![db-identifier](https://user-images.githubusercontent.com/98274959/169576510-6e98f801-9c53-4b2d-8cdf-3dfeb79a5f97.png)

#### DB endpoint and port
![endpoint port](https://user-images.githubusercontent.com/98274959/169576545-fb6749e4-2610-4787-b469-94003e0651a6.png)

#### DB name
![db-name](https://user-images.githubusercontent.com/98274959/169576575-2b7cec2c-d12e-4b8e-9d72-959df6b17526.png)

#### RDS-SG
![rds-sg](https://user-images.githubusercontent.com/98274959/169576597-0a926210-3a0c-4289-96e0-b4ed0a2575a2.png)

#### Test app with a container
![add topics](https://user-images.githubusercontent.com/98274959/169576626-ccc68a0d-1a5b-46da-b9b7-06b319389c71.png)

#### Test RDS with DBeaver
![dbeaver](https://user-images.githubusercontent.com/98274959/169576647-cfb1c64e-e97c-4e48-85bc-03ecc4f9de40.png)


### ECR-Configuration

![ECR-Policy 1](https://user-images.githubusercontent.com/98274959/169587944-9d0bacb5-68ad-44b4-8118-0c0f6f1cc4be.png)
![ECR-Policy 2](https://user-images.githubusercontent.com/98274959/169587991-6b1d7e7a-f736-4a77-b645-dbbd35cf8f25.png)
![ECR-Policy 3](https://user-images.githubusercontent.com/98274959/169588060-c134e5ac-2239-4ab3-a77b-2a6ff42f0d57.png)
![pushed image](https://user-images.githubusercontent.com/98274959/169588830-09349259-56ff-4ec1-9204-2c996e84f898.png)

### Circleci
![circleci](https://user-images.githubusercontent.com/98274959/169588161-df379160-4bb9-40fa-9e2b-1b97cf62007c.png)
