# pipeline-template-catalogs

* Cloudbees docs available at https://docs.cloudbees.com/docs/admin-resources/latest/pipeline-templates-user-guide/

CLI examples to export a template 

```
java -jar jenkins-cli.jar -auth admin:*****  -s https://<url>/<master> > output.json
```

Import

```
java -jar jenkins-cli.jar -auth admin:********  -s https://<url>/<master> pipeline-template-catalogs  --put < output.json
```
