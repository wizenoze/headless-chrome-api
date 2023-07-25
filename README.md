1. Install node JS 20.4.0
2. run `npm install` command to install all the required packages. (This repo is running with [puppeteer 20.9.0](https://pptr.dev/) which installs the required chromium version that is guranted to work )
3. if you are running this repo on EC2 you need to install [pm2](https://www.npmjs.com/package/pm2) 
*PM2 is a production process manager for Node.js applications with a built-in load balancer. It allows you to keep applications alive forever, to reload them without downtime and to facilitate common system admin tasks.*
4. start the application with 
**without pm2 -** `node server.js`    
**with pm2** - `pm2 start server.js`
