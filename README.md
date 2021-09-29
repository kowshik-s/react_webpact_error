# react_webpack_error-solution- copy the env file above and paste it in your root direcotry in react your react project
If you would prefer to ignore this check, add SKIP_PREFLIGHT_CHECK=true to an .env file in your project. That will permanently disable this message but you might encounter other issues.
if you are getting this type of error
#Note:donot use brackets in your terminal just copy paste the code inside the brackets
#step1:check the webpack version to check run command (npm webpack -version)in your terminal  donot use  brackets to run a command in terminal if the version greater than 4.42.1 goto step 2.if webpack version is less than 4.42.1
goto step4
#step2:in the react project go to src folder and create .env file and open it and add SKIP_PREFLIGHT_CHECK=true
#step3:save the env file and run command (npm start) in terminal and ur good to go.
#step4:do the below steps if the above steps didnt work or the webpack version is less than 4.42.1 run command (npm uninstall webpack)
#step5:run command(npm install webpack)this will solve the problem 
