# week2-omeruysal
week2-omeruysal created by GitHub Classroom

Authentication backend endpoints

Tech Stacks: Node.js Typescript Mysql Typeorm Jwt Express

End points with request body :  
1- POST Register : http://localhost:8080/api/register 
{  
    "firstName":"user",  
    "lastName":"user",  
    "email":"user@user.com",  
    "password":"12345",  
    "passwordConfirm":"12345"  
}  
2- POST Login : http://localhost:8080/api/login 
{  
    "email":"user@user1.com",  
    "password":"12345",  
}  
3- GET  Authenticated User : http://localhost:8080/api/user  
4- POST Logout : http://localhost:8080/api/logout  
{}  
5- PUT  Update User without password : http://localhost:8080/api/info  
{  
    "firstName":"user1",  
    "lastName":"user1",  
    "email":"user@user1.com",  
}  
6- PUT  Update password : http://localhost:8080/api/password  
{  
    "password":"user12345",  
    "passwordConfirm":"user12345"  
}  
7- GET  All users : http://localhost:8080/api/users  
