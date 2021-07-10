Heroku
Steps to deploy the application to Heroku

Create account on Heroku
Download and install Heroku-Client
Commands to run to deploy the application by using Heroku-Client

$ heroku login //login to Heroku

$ heroku logout //logout of Heroku
$ heroku create <project_name> --buildpack https://github.com/mars/create-react-app-buildpack.git

$ git push heroku master
Check existing Heroku apps
$ heroku apps
Check and remove existing buildpacks
$ heroku buildpacks

$ heroku buildpacks:remove <buildpack_name>
Config
$ heroku config:set <env_property_name>=<value>
Application URL 