#MHPortfolio
##Portfolio Project - Deployment of Web Applications

###Deployment Plan

1. Open Project Folder Into WebStorm
  1. Make sure to "Checkout" the gh-pages branch before developing new features
  2. Once gh-pages branch is loaded you may make changes as this is the beta
2. Saving New Features to Testing Environment
  1. Once a change is made testing is done locally using MAMP Pro
  2. After all testing performed and the code is stable we should test the feature in a remote environment
  3. "Commit and Push" the changes to the gh-pages branch
  4. After the being pushed to the gh-pages branch the test version will be viewable at [http://mattghicks.github.io/mhportfolio/](http://mattghicks.github.io/mhportfolio/)
3. Getting our Beta to The Live Server
  1. We must now "Checkout" the master branch to make sure our content is the same as the most recent master version
  2. In WebStorm under the Git Selection, select gh-pages and then merge option
  3. Now Commit and Push the master branch to GitHub
  4. In order for the Live Server to be updated you must run "git push prodServer" which is the remote server we setup with GitHub

######All versions at this point should be functional and up to date.