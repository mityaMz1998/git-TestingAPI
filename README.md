I. Objective of the assignment: to build a collection of requests (.json) in Postman based on the described documentation, using the obtained collection to reach the “Policy Calculation” stage in the Test Insurance Company and get the premium. 
For this purpose it is necessary to:
1. Pass authentication by getting a token;
2. Create a driver (or more than one), policyholder, owner and car;
3. Combine the subjects and objects of insurance into one entity “insurance object”;
4. Create a contract and update it in the AgentApp system by linking it to the “insurance object” entity;
5. Get the full calculation for the insurance company.

Source data:
Host: https://partner.agentapp.ru/
Login: qa@qa.qa
Password: 111
api_version: v1

The following Postman features were used to complete the assignment:
- variables were created;
- on the Scripts tab we used queries that allow us to pull Id and token values from the server response body and substitute them into the collection variable;
- Snippets were used to check the status code of requests;
- POST and PATCH methods are used.

The created collection is in the file "TT_AgentApp.postman_collection.json"

II. There is a description of the API: https://dummyapi.io/docs

Create a collection of requests in Postman that includes:
- Get a list of users;
- Get a user;
- Creating a user;
- Updating a user;
- Deleting a user.

The following Postman features were used to complete the assignment:
- variables were created;
- Snippets were used to check the status code of requests;
- POST GET, PUT, DELETE methods are used.

The created collection is in the file "DummiAPI.postman_collection.json"
