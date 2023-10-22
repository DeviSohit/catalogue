#!groovy
// it means the libraries will be downloaded and accessible at run time
@Library('roboshop-shared-library') _ //Jenkins system configuration library name. There we referring from roboshop-shared-library repo
def configMap = [
    application: "nodeJSVM"
    component: "catalogue"
]
// this is .groovy file name and function inside it
pipelineDecission.decidePipeline(configMap)