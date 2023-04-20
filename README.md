Step 1: Create a folder and open in VS code
Step 2: Create a file called 'index.js'
Step 3: Run the command: npm init
Step 4: Give answers for name, description, keywords, author and press enter for rest of it
This creates a file package.json with the all the details entered
Step 5: Run the command: npm install express
This creates a file package-lock.json and a folder node_modules
node_modules folder contain many js, json files that contains many libraries needed to run express js and node js
package-lock.json contains all other dependencies and whenever one runs npm install, they get installed

Setting up Template Engine using ejs
1.npm install ejs
2.app.set --> view engine and view_path
3.setup the views folder
4.render it using res.render()
5.npm install body-parser
