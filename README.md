
 #__Step-by-step Node/npm project__

 
 1. Identify npm to use for the project.
    1. Follow install steps from developers on NPM website
    2. In Terminal type: ```npm install``` followed by the the NPM name (follow develper instructions).
 2. Node packages are collections of modules, and contain the dependency files that the individual project requiers.
    1. These files will be stored in a file called package.json.
    2. It is important to list the dependency files in a .gitignore file to avoid storing large amounts of unnecessary information on github.
 3. Repo and clone.
    1. In github create a new repository.
    2. Get the clone, and use ```git clone``` to save the repository in a new directory.
    3. Open file in VSCode using ```code .```
 4. Use the ```node``` command followed by the file name to run the file using node.


 ##__Class notes__

### new npm project

1. Setting up javaScript in terminal:
    * Make a directory and cd into the new project direrctory.
    * npm init to create a package.json file
    * Touch index.js or other main entry point file
2. Set up the git repo
    * run git init to create a new repo directory
    * create a git ignore file ```echo node_,odule >> .gitignore```
    * check to make sure node_modules folder is not being tracked with a git status
    * add and commit your work ```git commit -m "message"```

### cloning a project down

1. Create new project
    * clone ansd repo onto your local and cd into new directory
    * run and install the requiered packages from the package.json
