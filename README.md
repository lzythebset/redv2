# node-red-azure-webapp
A webapp wrapper for running node-red in an Azure Web App.
To use it just:

1. Deploy to Azure with this button:

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Flzythebset%2Fnode-red-azure-webapp%2Fmaster%2Fwebapp.json" target="_blank"><img src="http://azuredeploy.net/deploybutton.png"/></a>

> This project currently uses a workaround to avoid a small problem caused with `child_process.execFile`: it uses a fake npm.cmd that points to the real one.

## Usage

Wait until everything is deployed before opening the website, during the deployment a script is executed to download this repo and install all the needed modules. If you see this screen just wait about 30 seconds to let the Node-RED app start: