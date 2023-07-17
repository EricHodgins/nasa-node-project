Environment Variables On Windows
Heads up! If you're using the default Windows shell, the syntax to set an environment variable like PORT is slightly different than what we saw in the previous video. To set PORT in your package.json on Windows, you'll want to write:

"start": "set PORT=5000&& node src/server.js"

Instead of:

"start": "PORT=5000 node src/server.js"

Alternatively, there's the cross-env NPM package which will work all platforms. Both options work!f

## I set the bash shell for npm in a terminal

`npm config set script-shell bash`

## Multi command script in package.json files 😁

`"server": "cd server && npm run watch",`
`"client": "cd client && npm start",`

&& multi command runs one after the other & runs both at same time

## Mongo

`user: eric`
`password: ZK670GFBnRTN22B6`

`mongodb+srv://eric:<password>@ztmcourse.she5ls4.mongodb.net/?retryWrites=true&w=majority`
