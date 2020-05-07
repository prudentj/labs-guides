# Setting Up Review Apps On Heroku

## Why Use Review Apps Pipeline

The Review Apps Heroku Pipeline would allow one not to have to use the Heroku remote to push to the staging server on Heroku. Overall, this should allow one to increase workload capacity since the Review Apps Pipeline could cut out the learning curve of deploying to Heroku via the Heroku remote through the CLI.

## How Review Apps Heroku Pipeline Works

Heroku deploys the HEAD commit of the branch that the associated Pull Request is created on. When the branch is updated Heroku redeploys to the connected repo on the Review Apps Pipeline with your latest commit.

### Setting Up Review Apps Steps

1. Create a Pipeline by going to your heroku ashboard and going to `new` and clicking the dropdown then clicking on `create new Pipeline`

2. Make sure to add the repo you want to connect the Review Apps Pipeline to

3. Once on the Pipeline Dashboard click `Enable Review Apps`

4. Then config Reviews Apps with your preferred settings
   - `Automatically create review apps for new PRs`
   - `Destroy stale review apps automatically` - set to preferred time frame

### For more information visit

https://devcenter.heroku.com/articles/github-integration-review-apps#configuration
