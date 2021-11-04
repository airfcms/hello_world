#!groovy
/*
String path_automation_devops = "../devops_jenkins/automation/pipelines.groovy"

//Get the Jenkinsfile from the devops_jenkins directory (repository)
//GroovyShell shell = new GroovyShell()
def tools = new GroovyShell().parse(new File(path_automation_devops))

//Get the name of repository name
def repositoryName = "pwd".execute()
                          .text
                          .tokenize("/")
                          .last()

//Call jenkinsfile function from devops repository
tools.devops_call(repositoryName)

*/ // All wrong, it must be from jenkins import configuration

@Library('csw-airfcms-pipelines-library')
import com.criticalsoftware.automation.pipelines

devops_call('sometext')