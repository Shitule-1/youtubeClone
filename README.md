# youtubeClone
Making Basic YouTube Using MERN

**How to run youtube clone project**
1)download this zip file
2) unzip file
3) set directiory  > YouTubeProject (in vs code terminal ) and type below command 
          > npm i
          > npm start
4) sure your mongodb is running if you linux user start mongodb using(> sudo systemctl start mongod)
5) after > npm start change directory  > cd vite-project  and type below command
             > npm run dev
6) go to on provided url in browser and now you can see our project


**feature of this created youtube clone**
 1) Adding functionality of signIn and signUp
 2) adding Jwt Token Authenticatioin
 3) preventing some routes only access that routes when user login ex. uploading vedio this route is only accessible to user which user is login else user not able to upload video
 4) we uses a cloudinary for storing images and vedios and providing that thumbanil unpload links and store in database.
 5) add toast to handling ui (showing message error or success) 






