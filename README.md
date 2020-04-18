# Prepare-node-js

- Download Node.js from given link.
  
  https://nodejs.org/en/download/

- Download VSCode

  https://code.visualstudio.com/download

- Create one project folder and opent it in vscode
- Cretae one file in that folder like one.js
- past given code into it 
***
      var http = require('http');
      http.createServer(function(req, res) {
          res.writeHead(200, { 'a': 'b' });
          res.end('fdgvdsv');
      }).listen(8000);
      console.log("hii");
***
- Run this file in terminal of vscode
  - node .\one.js [command]
- Opent it into browser with port number given by you
  - http://localhost:8000/
  
- Packages not availabe due to that open node.js cmd and follow givent command
- First goto your project folder in cmd
    - npm init -y

- Install nodeone package
  - npm i nodemon -g [use -g for installing globally]
- Visit given site to know what this package can do.
  - https://www.npmjs.com/package/nodemon

