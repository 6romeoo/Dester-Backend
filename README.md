# Dester-Backend

Using strapi as the backend for the project.

## Recommended Setup.

First deploy the backend.

Clone the repo locally and edit your config from there.

Then Deploy the frontend. Link to the frontend https://github.com/Dester-Alken/Dester-Frontend

Note: This is because the web version of the backend is a little slow.
 
## Welcome to Dester Backend. [Local]

Create a MongoDb cluster on https://www.mongodb.com/atlas/database

Collect the credentials

INSTALL
```
npm install
```

BUILD & RUN COMMAND
```
npm run develop
```

## Environment Variables

DATABASE_HOST=`Database Host Url Ex: @cluster.aaa.mongodb.net`<br>
DATABASE_SRV=`Boolean. If your mongodb is on atlas meaning remote then DATABASE_SRV=true`<br>
DATABASE_PORT=`Database Port Number`<br>
DATABASE_NAME=`Anything its up to you`<br>
DATABASE_PASSWORD=`Database Password`<br>

## Start Setting Up the Basic details.

1) First head over to the admin panel domail.com/admin

2) Create an user and save the credentials.

3) Then headover to the Setting in the dashboard menu.

4) Under 'USERS & PERMISSIONS PLUGIN' select 'Roles' then click Public.

5) Under Permissions Section. click the count,find,findone options under all the items then click save.

6) Start adding content in the movies and series menu of the dashboard menu.

Note: See the demo admin panel for reference.