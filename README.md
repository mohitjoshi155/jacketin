# Jackett hosted on Heroku container


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
