# assignment 8
1. In order to be able to run our code please open our code using vscode.
2. When in vscode please open up a terminal to run the following command.
3. docker-compose up --build
4. When this is done running please open up another terminanl either in vscode or on your personal computer.
5. In this new termianl please run the below command for POST
6. curl -X POST -H "Content-Type: application/json" -d "{\"storage-key\": \"mykey\", \"storage-val\": \"myvalue\"}" http://localhost:4000/keyval
7. Once this command runs please look at the first termianl that ran your "docker-compose up --build" command and see what status code you recive
8. The below commands are for the GET, PUT, and DELETE you will run this one at a time to see what staus code you get for each one you get
9. curl -X GET http://localhost:4000/keyval/mykey
10. curl -X PUT -H "Content-Type: application/json" -d "{\"storage-key\": \"mykey\", \"storage-val\": \"newvalue\"}" http://localhost:4000/keyval
11. curl -X DELETE http://localhost:4000/keyval/mykey
