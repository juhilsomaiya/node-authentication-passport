# node-authentication-passport
This repository contains a simple demo of Authentication with username and password. User needs to supply username and password and if the credentials are correct then user will be redirected to the success page else error page

Please make sure you have installed following items inorder to use the demo.

  - nodejs 
  - passportjs
  - expressjs
  - MongoDB server 

Get MongoDB server by the steps below: 

--Installation-- 

  - sudo apt update
  - sudo apt install -y mongodb

-- Check the service and database --

  - sudo systemctl status mongodb

-- Check connection status -- 

  - mongo --eval 'db.runCommand({ connectionStatus: 1 })'
  
-- Workig with MongoDB -- 

  - Start server : sudo mongod
  - Start MongohShell in another terminal : mongo
  - Create db and add some data in mongo shell as follow:
      - use MyDatabase;
      - db.userInfo.insert({'username':'admin','password':'admin'});
      
      
After successful completion, please try to run the index.js on node server and you'll get the html file on specified port. Use credentials as we stored in db in order to work with it. 

Don't forget to Star and Fork the repo. :)
