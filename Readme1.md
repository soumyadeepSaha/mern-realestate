we are going to create the client site inside another folder called client 

-->INstall react js using vite by using command "npm create vite@latest client" //client is the folder in which we want ot make
--> we will install react in our case(framework)..


-->use javascript

--> now folder (client will be created )
-< go to folder "cd client"

--> install 'npm i" to install the dependencies and devdependencies

(1/5steps)-already done
--> Install "tailwind using vite" go to the webpage
->using react more specifically  
"2. install tailwind css" in web pagen tailwind site
    -npm install -D tailwindcss postcss autoprefixer
    -npx tailwindcss init -p
2/5)
3.configure your template paths

- in tailwind config.js (paste the config from the web)
--so this is basically goin to check the index.html file and also all the files with the below extentions in the src folder

3/5)

4. Add tailwind directives to your css

@tailwind base;
@tailwind components;
@tailwind utilities;
-replacing everything in inde.css with these three lines of code 
- these are going to apply the base classes of tailwind css



5. start your build process 
 command:::__> " npm run dev"

 --delete the unwanted files
 -app.css(because we are using tailwind css)
 -public-vite.svg
 -assets-react.svg


 



# IF YOU DONT GET THE SUGGESTION USE "ctrl + space "



# Next add the project to a github repository 
- we need these github repos to deploy our application
- commit 

steps-
1. stop the terminal using ctrl c
2.in terminal write git init ( to initialize the git hub repository)
3.'git add .'( we are going to add all the files inside our application)
4.git commit -m "install react js and tailwind"
5. go to github to create our github repo
6. if you are sign in click on the + icon and create new repo->give a name for repo-> description-> public -> create repository
7. we already did the initiallization part of commands so we will go to the next part
8. first we going to add origin with address
--->:"git remote add origin https://github.com/soumyadeepSaha/mern-realestate.git"
9. create a branch
-->git branch -M main
10. push code to main branch
-->git push -u origin main
11. refresh the page in git hub you can see all your codes inthe git hub


****************************************************
NOTE:::::::::::___>completed installing react js and
tailwind css and we have created our first template
******************************************************
# creating pages and routes for our application

-vscode-> src -> pages(folder)-> About.jsx
                            ->Signin.jsx
                            ->Signout.jsx
                            ->profile.jsx
                            ->home.jsx
- as we are first tryig to create authentication so these pages will be enough for now

- we need to add this pages inside the app.jsx before doing that we have to install a package called react router dom which enables us to create these routes inside an application 
command::"npm i react-router-dom

--> then we go to app.js to import {browserrouter, rotes ,roue} from reactrouter dom
-- and create the route for the application in the app level

---by (alt + shift + downkey/up) we can make different copies of the above text


