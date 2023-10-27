#!groovy
// it means the libraries will be downloaded and accessible at run time
@Library('roboshop-shared-library') _ //Jenkins system configuration library name. There we referring from roboshop-shared-library repo
def configMap = [
    application: "nodeJSVM"
    component: "catalogue"
]
env //printing the variable
// this is .groovy file name and function inside it
//if not master branch then only trigger pipeline
if ( ! env.BRANCH_NAME.equalsIgnoreCase('master')){
pipelineDecission.decidePipeline(configMap)
}
else{
    echo "master PROD deployment should happen through CR"
}