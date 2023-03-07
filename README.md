# hands-free-express
-THE ULTIMATE TOOL OF BUILDING FAST-

## What was the problem?
Ah! Shit. A new project, making the folder structure, writing the same base code as other projects, copying and pasting all of them, initializing git, downloading packages, initializing package.json, running server and ... <strong> WTF BRO!? </strong>

## So How Was This Solved? 🤔
Aaaa~ A good one. Well, Actually one night when I was just chatting as normal with one of my developer friends the idea came out of the cave  and then I started to write it.
- Creates Folder Structures (For both app directory and class-based(OOP) projects and functional projects (no-app)) ✅
- Creates Some Basic and Obvious files of those directories ✅
- Initializes package.json ✨✅
- Installs the basic common packages (express, mongoose, morgan, cors, http-erros, http-status-codes, jsonwebtoken, dotenv and a bunch of others) 🎉✨ 
- Writes the basic server code needed for both OOP and functional projects. (The require statements don't need changes ) ✨✅ 
- Creates a Special response-builder names (SendResponse) ✨✨ 
- Creates some very useful middlewares such as validation Error mapper and ... ✅
- With also more utils such as a key generator for generating Secret_key for JWT tokens. ✅
- .gitignore and git out of the box, with node_modules and .env ignored 🎉✨✅ 
- Adds dev command to package.json file and runs the server for you (in functional or no-app mode)
- What Else you want! Open an issue and let's talk!

# USAGE
*for the day I'm writing this (3/7/2023) there is no automatic way to set ENVs on system from code, but I have the idea about fixing it. And I will. Wait a little*.

## Windows Users:
1. Do a clone of this repo anywhere you want
2. Press Windows button and type ```env```
3. Click on ```Environment Variables```
4. In both user variables and system variables, create a new env by pressing the ```new``` button and fill variable name with ```cea```.
5. Then choose ```Browse Directory``` and select the directory of cloned project as this Example: ```YourDrive:\path\to\hands-free-express\src```
6. Also double-click on both path variables and add the above address to your system's path too so your CMD or PowerShell can access it by typing ```cea xxx```.
7. Restart your PC/laptop and it's done! ✅

## Unix Based (macOS && Linux)
*Hey Bro, if I was  professional I wouldn't use Windows! You as a Unix based user should know how to fix ENV problems or at least how to search it! 🗿 GOOD LUCK*

# Commands
```cea help``` helps you get along with options and things here. <br />
```cea new-cb``` Creates a brand-new empty class-based project. <br />
```cea class-based``` or ```cea cb```: Creates a filled and almost ready OOP based project. <br />
```cea no-app``` Creates a Functional-suggested folder structure with the basic code you need for running your server with an index route (It's Perfect, Believe me and test it). <strong> You Don't even need to write a fucking single line of code for getting a server up and running.</strong>
