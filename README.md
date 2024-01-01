## node.js-pet-mongodb-avatar-test-email

### Mod06-1 

http://localhost:3000/auth/get-reset-token 

{  
    "email": "iii65@meta.ua"  
}  
  
http://localhost:3000/auth/reset-password  

  
{  
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9",  
    "password": "654321"   
}

Login :  
http://localhost:3000/auth/login  
  
{  
    "email": "iii65@meta.ua",  
    "password": "654321"   
}   

### === Docker ===  

$ docker -v  

$ docker build . -t pet-backend   

$ docker run pet-backend  

$ docker run -it --entrypoint sh pet-backend

'#' npm run start  

$ docker run -it -p 3000:3000 pet-backend   