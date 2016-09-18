ihakula-node1

===========
1. Download Heroku Command Line at : https://devcenter.heroku.com/articles/heroku-command-line
2. Create a repo in github e.g. https://github.com/wayde191/node1.git
3. Create App for heroku: $ heroku create myapp --buildpack heroku/nodejs : https://devcenter.heroku.com/articles/buildpacks
4. Push all your changes to github then do deploy to Heroku: $ git push heroku master
5. Check running instance: $ heroku ps:scale web=1
6. That's it: https://ihakula-node1.herokuapp.com/
