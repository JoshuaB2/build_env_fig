GitLab, Jenkins, Artifactory Build Environment with Swarm Build Nodes
===

###All Environments
    <local mapped drive> = The directory on your local system that you are mapping to the docker container.

###Gitlab Environment

####Postgresql:
    <password> = Set the password you want set for the GitLab postgres database.

####Redis:
<br>

####GitLab:
    <gitlab hostname> = Hostname for your GitLab server.
    <gitlab reply to email address> = Reply to email address for GitLab email.
    <snmp hostname> = SNMP server to relay mail through.
    <snmp domain name> = Email domain name.
    <password> = Password set for the postgresql database

####Artifactory:
<br>

####Jenkins:
Set the time zone for Jenkins by passing a Java opt.
    - JAVA_OPTS=-Duser.timezone=America/Los_Angeles
<br>

####Sample Swarm Client:
    <jenkins server url> = URL for the Jenkins CI server the swarm client should connect to.