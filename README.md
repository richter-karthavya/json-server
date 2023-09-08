# Steps to create a fake json-server using github

## step 1:- create a db.json file with following structure and upload to github

{
    "posts": [
        {
            "id": 1,
            "title": "hello"
        }
    ],
    "profile": {
        "name": "typicode"
    }
}

## step 2:- access the server using:- https://my-json-server.typicode.com/ <user> / <repo> /posts/1
Note:- Replace the "user" & "repo" with github username and "repository name" respectively.
Eg:- https://my-json-server.typicode.com/richter-karthavya/json-server/posts/1

## step 3:- Now the server is hosted with above address and we can access the server using "Axios" in our application.
