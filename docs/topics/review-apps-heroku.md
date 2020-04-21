*** Setting up Review apps on Heroku ***

How Review Apps Heroku Pipeline works 

Heroku deploys the HEAD commit of the branch that the associated Pull Request is created on. When the branch is updated Heroku redeploys to the connected repo on the Review Apps Pipeline with your latest commit. 

*** Setting Up Review Apps Steps ***

1. Create a Pipeline by going to your heroku ashboard and going to `new` and clicking the dropdown then clicking on `create new Pipeline`

2. Make sure to add the repo you want to connect the Review Apps Pipeline to 

3. Once on the Pipeline Dashboard click `Enable Review Apps`

3. Then config Reviews Apps with your preferred settings 
    * `Automatically create review apps for new PRs`
    * `Destroy stale review apps automatically` - set to preferred time frame

For more information visit: https://devcenter.heroku.com/articles/github-integration-review-apps#configuration