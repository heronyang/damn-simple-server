Please read my blog post [here](https://blog.heron.me/damn-simple-python-web-server-on-heroku-ba67cad2fb18).

# Install

```bash
$ pip install -r requirements.txt
```

# Deploy

Set `$PROJECT` to your project name.

```bash
$ heroku create $PROJECT
$ heroku git:remote -a $PROJECT
$ git push heroku master
```

Done! Your hello-world website should be live now at https://$PROJECT.herokuapp.com/.
