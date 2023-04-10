# SpringSecurityAdvance-2.7.10-StaticUser

Refer to the pom.xml for the dependencies ,we are usng the java 17 version and spring version 2.7.10

After completng the project go to postman and hit

http://localhost:8080/api/v1/auth/authenticate with post request with body as a json format

{
    "email":"sujith@gmail.com",
    "password":"password"
}
 ------------------------------------------------------------------------------------------
After that the token is created and hit the below url with get request with the authorization type of bearer with the  3 part token.

http://localhost:8080/api/v1/greetings/say-good-bye 
