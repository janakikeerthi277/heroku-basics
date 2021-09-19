# heroku-basics
This repo contains steps to deploy a simple app built on React and Nodejs to Heroku

1. Install Heroku CLI
    (mac OS) brew tap heroku/brew && brew install heroku

2. heroku login
3. Make sure to have the heroku-postbuild script in your package.json
4. rm -rf .git (remove any existing git references from your app folders)
5. git init
6. heroku create <youappname>
7. do a git add and commit of all your files
8. (optional) you can run the command "heroku local" to understand the final view of your app
9. git push heroku master
10. Go to heroku account, and go to the settings of your app
11. You can configure your env variables here (eg. mongodb uri and jwt secret key)
