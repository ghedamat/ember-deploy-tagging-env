# ember-deploy-tagging-env 

Uses the ENV variable EMBER_DEPLOY_TAG to mark the revision. This was created so that I could use a variable from the Build/CI server in order to mark the revision for later deployment.

TODO:
- Better error handling

Sample Usage:

In the config/deploy.js add: 

    tagging: 'env-tag'
