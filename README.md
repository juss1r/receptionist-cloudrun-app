See https://www.youtube.com/embed/IjUnQ9kMnVo ! This repo is based on that video!

Deploying NextJS apps to GCP Cloud Run with Github Actions
Notes
You should have a GCP account
You need to enable some GCP API's for this to work (we'll touch on that)
You need Docker, NodeJS and npm installed. Prefer the latest versions
Some basic knowledge of Docker, JavaScript/NodeJS and React is preferred
What we'll do?
Create a basic NextJS app
Set up your cloud project to be ready for Cloud Run deployments using Github Actions
Create a project *
Create a service account
Enable the correct API's (Cloud Run + GCR)
Build a docker image of the NextJS app
Add your code to Git
Create a github workflow (Action) and deploy the app.