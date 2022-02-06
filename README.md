# heroku_commands

```bash
# Link remote heroku
heroku git:remote -a paigeshin-portfolio

# Deploy
git add .
git commit -m "production commit"
heroku create
heroku addons:create heroku-postgresql:{hobby-dev}
heroku config:set COOKIE_KEY=dsfopaksfpoas 
heroku config:set NODE_ENV=production 
git push heroku master 

```
