Heroku Buildpack: Jpegoptim
=======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for using [jpegoptim](https://github.com/tjko/jpegoptim) in your application.  

Usage
-----

Add buildpack to heroku application

    $ heroku buildpacks:add --index 1 https://github.com/JazzJackrabbit/heroku-buildpack-jpegoptim

And then push the changes to Heroku

    $ git push heroku master

You can verify that everything is properly installed by running the following command:

    $ heroku run "jpegoptim -V"

