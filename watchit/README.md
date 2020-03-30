need to detect when a file changes - use a package called "chokidar" to detect file changes
it would be nice to provide some help to user of our CLI tools -  use a packahe calle "caporal" to build our CLI tool
need to figure out how to eecyte some JS code from within JS program- use the standard library module "child_process" to execute a program

--chokidar add --
watchit starts up -> chokidar 'adds' a file -> we start up the user's code -> chokidar 'adds' a file -> we stop the suers program that e just created -> we start up the user's code -> chokidar 'adds' a file (repeat the cycle when adding/changing/removing)

--workaround --
----npm install lodash.debounce (also make sure to require it on js file
watchit starts up -> chokidar 'adds a file -> we wait for 100ms to go by .. -> chokidar 'adds a file -> we wait for 100ms to go by(if 100ms goes by without a new add event --->) ->start up users code



inst !!!!!!!!!!!!!!!!
1. #!/usr/bin/env node
2. npm init -y 
3. (add on package.json:) "bin": {"watchit": "index.js"} ----  (then : npm link)
4. install chokidar  || add the function for chokidar
5. install lodash.debounce || add the devounce fuction
6. install caporal
7.
8.
9.
10. 
