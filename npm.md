# npm #
## version ###
`npm -–version`  
### package version ###
`npm info jquery versions`
### package version list ###
`npm list --depth=0`


## install ##
- global install  
`npm install –g package_name`
- local install  
`npm install package_name`
- install with dependencies on package.json  
`npm install --save package_name`

### install from "package.json" ###
`npm install`

## package update ##
- conferm un-updated packages  
`npm outdated`
- update with package.json  
Update with the VERSION described in the package.json  
`npm update`

## uninstall ##
- global  
`npm uninstall -g jquery`
- local  
`npm uninstall jquery`
- uninstall with dependencies on package.json  
`npm uninstall --save jquery`  
`npm uninstall --save-dev jquery`
