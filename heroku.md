# heroku how-to

#### to deploy master branch to heroku (default for most weeks)

* `git checkout master` to swtich to your master branch (if you're not already there)
* `heroku create`  
* `git push heroku master`  push local `master` branch to heroku's `master` branch

* debug any errors you get from the `git push` command  


#### to deploy  

Same as [deploy master branch to heroku] except the last command is:

(given your branch name is "my_feature")

* `git checkout my_feature`
* `git push heroku my_feature:master` (heroku will only run the `master` branch of its own repo, so you must specify `master` as the target branch for the push
