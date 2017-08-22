Repo 0

This is the mother of all smartworkx repos and if all fails is the start of setting up the smartworkx ecosystem.

## Principles

### Everything is a repo

The starting point is the README.md in that repository. Repositories are in GitHub documentation, issue management, etc. will be done in those projects. 

- An environment is a repo, so separate repos for your laptop, staging, production, build this only holds config information and scripts specific for that environment.
- An artifact is a repo
- An environment technology has a repo like kubernetes-cluster, gcloud, gcloud postgres database, concourse

Every repo has a folder pipeline from which the necessary automation will be set up

### Use docker everywhere

### Scripting start with bash, use javascript when complex

## Strategic technology
- Container framework: docker, vagrant
- Cluster: kubernetes, gke, minikube
- Version control: git, github
- Programming language: javascript
- Build server: Concourse ci
- Operating system: Bash, Linux, Alpine, Ubuntu

## Getting started:
- Create Github account
- Create google account
- Install Git to your machine
- Install Docker to your machine
- Set up the gcloud image
- Set up the google container registry
- Setup a cluster named smartworkx-cluster. See the kubernetes-cluster project on how to set up a cluster.
- Create a build server named smartworkx-build-server. See the build-server project on how to set up a build server.
 
## Creating an app
- Create a repository
- Add a readme
- Add a pipeline and create it with the build server

## Security issues
- Database wachtwoord in admin api
- Service account json in gcloud image

