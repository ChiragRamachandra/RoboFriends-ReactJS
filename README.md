# robofriends
udemy course - React
To run the project:

1. Clone this repo
2. Run `npm install`
3. Run `npm start`# RoboFriends-ReactJS


To Deploy the package to Git hub Pages:

1. go to package.json and add: "homepage": "https://myusername.github.io/my-app",
2. npm install --save gh-pages
3. Add these 2 in scripts
 "scripts": {
      "predeploy": "npm run build",
      "deploy": "gh-pages -d build"
 }
4. npm run deploy

Incase you run into errors for npm run deploy. Use via the GitHub Terminal.

Also try:
rm -rf node_modules/gh-pages/.cache

so that the cache is cleared.

Note: Useful resource to display github pages
https://dev.to/yuribenjamin/how-to-deploy-react-app-in-github-pages-2a1f


