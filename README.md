# Azure DevOps CI-CD

## Pipeline

### Classic Editor Pipeline

- use the classic editor
<img src="/pictures/pip.png" title="pipeline"  width="900">

- choose repo
<img src="/pictures/pip1.png" title="pipeline"  width="900">

- empty job
<img src="/pictures/pip2.png" title="pipeline"  width="900">

- get source
<img src="/pictures/pip3.png" title="pipeline"  width="900">

- agent job
<img src="/pictures/pip4.png" title="pipeline"  width="900">

- npm install
<img src="/pictures/pip5.png" title="pipeline"  width="900">

- npm build (command should be "run build")
<img src="/pictures/pip6.png" title="pipeline"  width="900">

- publish
<img src="/pictures/pip7.png" title="pipeline"  width="900">

- deploy app
<img src="/pictures/pip8.png" title="pipeline"  width="900">


### Starter Pipeline

- starter pipeline
<img src="/pictures/starter.png" title="starter pipeline"  width="900">


- yml config
<img src="/pictures/starter1.png" title="starter pipeline"  width="900">


### Release Pipelines

#### Staging Stage

- choose **Azure App Service Deployment**. Rename stage into *Dev Deployment*
<img src="/pictures/release.png" title="release pipeline"  width="900">

- add an artifact
<img src="/pictures/release1.png" title="release pipeline"  width="900">

- add a branch trigger
<img src="/pictures/release2.png" title="release pipeline"  width="900">

- configure agent
<img src="/pictures/release3.png" title="release pipeline"  width="900">

- add a deployment slot. Clone the settings
<img src="/pictures/release4.png" title="release pipeline"  width="900">

- configure deploy
<img src="/pictures/release5.png" title="release pipeline"  width="900">

#### Production Stage

- add prod stage
<img src="/pictures/production.png" title="production pipeline"  width="900">

- configure deploy
<img src="/pictures/production1.png" title="production pipeline"  width="900">

- add query
<img src="/pictures/production2.png" title="production pipeline"  width="900">



## Web App

<img src="/pictures/web_app.png" title="web app"  width="900">



## teams Settings

<img src="/pictures/teams.png" title="teams"  width="900">
<img src="/pictures/teams2.png" title="teams"  width="900">
<img src="/pictures/dashboard.png" title="teams"  width="900">



## Test Plans

-create test plan
<img src="/pictures/test.png" title="test plan"  width="900">