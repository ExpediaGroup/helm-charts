# Contributing new Helm Charts

Note: Unfortunately the process to publish new Helm Charts is not automated yet, so please bear with us while we explain this two step process 🦄

If you would like to contribute a new Expedia Group Helm chart you will need to open 2 pull requests.

## Publish Sources

* Start by forking this Github repository and creating a new branch from master.
* If this is a new application, create a new folder under `charts`.
* Add the relevant Yaml files (refer to an existing chart for reference).
* Submit a Pull Request with these changes.

## Publish Helm Charts

* Switch to the `gh-pages` branch and create a new branch from this in your fork.
* Package your chart into a `.tgz` file. See [Helm Package](https://helm.sh/docs/helm/helm_package/).
* Add your file under the `repo` folder.
* Finally, you will need to update the index file. See [helm repo index](https://helm.sh/docs/helm/helm_repo_index/). 
* Submit a Pull Request with these changes.
