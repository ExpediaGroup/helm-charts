# Contributing new Helm Charts

If you would like to contribute a new Expedia Group Helm chart:
 * fork this GitHub repository and create a branch
 * create a a folder for your chart under `charts` and add the relevant YAML, template and related files (refer to an existing chart for reference)
* submit a Pull Request with these changes

## Release process
Unfortunately this process is not automated yet, so please bear with us 🦄

1. Start by adding the new chart with the sources to the `charts` directory in the `master` branch.

2. Next, package your new chart (you can use `helm package .`) and add it to the `gh-pages` branch.

3. Finally, you will need to update the index file (you can use `helm repo index .`)
