## uploa the project to the github:  
1.You need to build a parent folder in the github;  
2.according to the [Enviroment Building:](https://github.com/GlennOu66304/Tarominiprogram) to build the project;   
3.Then move the files in the project children into the parent project folder;   
4.Test the project(under the parent project folder):   
```
source ~/.bash_profile 
nvm use node 
yarn dev:h5  
```

## run the project from github in local:  
1. git clone project  from the github;  
2. remove the yarnlock file;(fix the bug:[Failed to compile ./src/App.js Module not found: Can't resolve](https://stackoverflow.com/questions/48767118/failed-to-compile-src-app-js-module-not-found-cant-resolve)
3. add the dependence:  
```
source ~/.bash_profile 
nvm use node  
yarn
```
node version:Now using node v14.14.0 (npm v6.14.8) 
change your wifi to the data to allow the install speed faster  
4. gitignore to avoid the many change in the git commit:  
file name:.gitignore
```
node_modules
```
5. test the code in the H5  
```
yarn dev:h5 
```
6. if your files could not runt the project, that is mean that your src lost some files, you could compare it with a new project and add the lack of file: pages.app.js, app.css,index.html in the src folder