This is a public repository for the Orbit SaaS product. I am keeping the official full codebase private because I am releasing the it to market soon, and I don't want to put my SaaS product freely on the web for anyone to copy - obviously! 

For this project, I implemented a Chrome Extension that utilizes React JS for a web application user interface. The React UI is in charge of aggregating all of the user's lead data and creating and sending automated message sequences to all of the leads. Other parts of the extension inject JS into Facebook.com, allowing a user to import leads from Facebook Groups and send messages to them automatically.

I actually did not implement a server for this project. My front-end app communicates directly with Pocketbase.io. This has allowed me to drastically increase the speed of my development. I had to take some specific measures to ensure the security of communicating directly with a database from the front-end. Pocketbase alos provides added security in it's schema configuration. Pocketbase is a super cool project I highly recommend it!

Throughout the development of this UI, I always mockup the design in figma with comments regarding what each functional component does and then I implement it in React. When my project is live, I will include a link to the landing page here, along with some screen shots of the UI. I unfortuniately will not release the code for obvious reasons!
