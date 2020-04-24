# Example Shiny App on Heroku

This is an example Shiny application, which uses [heroku-docker-r][1] for Heroku.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

You can use this project as a template for creating Shiny application on Heroku. Execute these commands to get started:

```bash
# get the sources
git clone https://github.com/virtualstaticvoid/heroku-docker-r-shiny-app.git
cd heroku-docker-r-shiny-app

# optionally, reinitialize git
rm -rf .git
git init
git add --all
git commit -m "initial"

# create a new heroku application and deploye
heroku create --stack=container
git push heroku master

# view the application
heroku open
```
[1]: https://github.com/virtualstaticvoid/heroku-docker-r
