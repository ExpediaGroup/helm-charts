# Contributing new Helm Charts

If you would like to contribute with a new Expedia Group helm chart, fork this GitHub repository, create a branch, and send a Pull Request.

## Release process
Unfortunately this process is not automated yet, so please bear with us 🦄

1. Start by adding the new chart with the sources to the master branch to the `charts` directory.

2. Next, package your new chart (you can use `helm package .`) and add it to the `gh-pages` repo.

3. Finally, you will need to update the index file (you can use `helm repo index .`)
