# SonarCloud Badge

[![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=rishibagekar_PSL-ZS_GithubActionsUnlockedPackages)](https://sonarcloud.io/summary/new_code?id=rishibagekar_PSL-ZS_GithubActionsUnlockedPackages)

# Installation of Unlocked Packages on SF environments

# Installation Options
<a>
  <img alt="Deploy to Salesforce"
  src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>

## URL
- [Production/Developer](https://login.salesforce.com/packaging/installPackage.apexp?p0=04tao000000jsQrAAI)
- [Sandbox](https://test.salesforce.com/packaging/installPackage.apexp?p0=04tao000000jsQrAAI)

Unlocked Packages can be installed by clicking on above mentioned url depending upon the type of Salesforce Environment you own

## CLI
sf package install --package "04tao000000jsQrAAI" --targetusername YOUR_ORG_ALIAS --wait 10 --publishwait 10

Unlocked Packages can be installed by running the above mentioned SF command using the CLI

## Manual 
You can install this by cloning the repository and deploying the content of force-app folder. Before that you should remove the _namespace property in the _sfdx-project.json_ file if present any.
