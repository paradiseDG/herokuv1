just a quick application made in nodejs to deploy using heroku. 
not fully functional yet, very much still a WIP

Make sure you have Node.js and the Heroku CLI installed

```sh
$ git clone https://github.com/heroku/node-js-getting-started.git # or clone your own fork
$ cd node-js-getting-started
$ npm install
$ npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```
$ heroku create
 after making changes, use 
  $ git add
 and use 
  $ git commit -m "*comment*" 
 to prep for pushing
$ git push heroku master
$ heroku open
