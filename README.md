# php-sf-template-openshift
Start by creating template 
`oc create -f php-sf-template.yaml`
and then `oc new-app --template=php-sf-template -p DEPLOYMENT_NAME=free-app-deployment -p SERVICE_LABEL=free-app-svc -p ROUTE_NAME=free-app-route -p APP_LABEL=free-app`
