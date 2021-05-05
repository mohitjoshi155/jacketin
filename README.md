# Jackett hosted on Heroku container

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/mohitjoshi155/jacketin) #Revived

## Instructions
Clone this repo in your machine, and use those coomands after install de [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)

```bash
  heroku login
  heroku create your-app-name
  heroku stack:set container
  heroku container:login
  heroku container:push web
  heroku container:release web
  git add
  git commit -m "First Commit"
  git push heroku master
```
