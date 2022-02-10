# Unit 19 PWA Homework: Text Editor

https://nmh-texteditor.herokuapp.com/

## My Task
A PWA text editor that can be used locally offline. Can be downloaded as a browser extension as well. Most of the task was simple, once I got it working locally I had some troubles with heroku deployment. I realized I had forgotten to update parameters to the scripts in the package.json, this fix solved the deployment problems. 

## NPM Packages
```
Babel
Express
Node
Webpacks
Workbox
```

## Images
![image](https://cdn.discordapp.com/attachments/695157509761269790/941159780767137862/unknown.png)

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```