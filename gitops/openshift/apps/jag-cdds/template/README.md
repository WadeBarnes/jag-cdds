## Templates to create openshift components related to jag-cdds api deployment

### Command to execute template
1) Login to OC using login command
2) Run below command in each env. namespace dev/test/prod/tools
   ``oc process -f jag_cdds.yaml --param-file=jag_cdds.env | oc apply -f -``


