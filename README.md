# Principles and Practice in Programming Languages
# Mini-Project: Fall 2022

See [instructions.md](instructions.md) for submission instructions.

# Express NodeJS

## Description

Express is simple and easy to use web application framework. We decided on this framework because we wanted to dive deeper into web development, as well as strengthen our skills in javascript and embedded javascript.

Our project are web pages that serve as a to-do list for daily tasks and work tasks. These pages utilize javascript, embedded javascript, and css and run on a localhost server at localhost:3000 and localhost:3000/work. You can add your own tasks to these lists to keep of track of what you need to work on.

## Repository Organization

This README file, the text for our script, and the instructions for this miniproject are in the root directory of this repository. The files for the web pages are placed inside of the upload folder. From there, there is a views folder that has a header (header.js), footer (footer.js), and main page (list.js) that make up the actual page. The package.json contains our dependencies for app.js (includes date.js, which has functions to get the current date), which is the js file that needs to be run in order to start the server. The css file to style the web pages (styles.css) are stored in upload/public/css.

- upload

    - public
    
        - css
        
            - styles.css
            
    - views
    
        - footer.ejs
        
        - header.ejs
        
        - list.ejs
        
    - app.js
    
    - date.js
    
    - index.html
    
    - package-lock.json
    
    - package.json
    
README.md

instructions.md

script.txt

## Building and Testing Instructions

Setup

Step 1. Run 'npm i'on the command line inside the upload directory to get all the dependencies for this project

Step 2. In the command line, type 'node app.js'

Step 3. Record the port number from the ouput (port 3000)

Step 4. In a web browser, go to localhost::<port number>
  
Testing
  
To add a new item, type the word into the 'New Item' box then click the plus.
  
Another page to look at is localhost:3000/work, and you can do the same thing as above.

## Presentation

TODO: Update the following links and remove this line.

- YouTube: https://www.youtube.com/watch?v=-2FX_RooKZI. (Couldn't add video to class playlist, but uploaded it to youtube)
- Script: [script.md](script.md)
- Recording: Our file size was to big to upload to github.
