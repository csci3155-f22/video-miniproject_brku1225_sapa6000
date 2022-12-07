# Principles and Practice in Programming Languages
# Mini-Project: Fall 2022

See [instructions.md](instructions.md) for submission instructions.

# Express NodeJS

## Description



## Repository Organization

This README file, the text for our script, and the instructions for this miniproject are in the root directory of this repository. The files for the web pages are placed inside of the upload folder. From there, there is a views folder that has a header (header.js), footer (footer.js), and main page (list.js) that make up the actual page. The package.json contains our dependencies for app.js (includes date.js, which has functions to get the current date), which is the js file that needs to be run in order to start the server. The css file to style the web pages (styles.css) are stored in upload/public/css.

upload
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

- YouTube: https://youtu.be/TODO.
- Script: [script.md](script.md) or [script.pdf](script.pdf).
- Recording: [recording.mp4](recording.mp4).
- Slides (if you use them in your recording): [slides.pdf](slides.pdf) and slide sources (e.g., [slides.pptx](slides.pptx) or [slides.key](slides.key)).
