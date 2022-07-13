## JJTECH GCP CICD PROJECT
### SONARQUBE CREDENTIALS
### TOKEN
```
jjtech-cicd-java-project: a8e62abe08f89e6cc74de5c8a2fba9dd6de75d96
```
username: admin
passwd: admin
```
mvn sonar:sonar \
  -Dsonar.host.url=http://34.73.200.213:9000 \
  -Dsonar.login=a8e62abe08f89e6cc74de5c8a2fba9dd6de75d96
```
### Maven
```
username: admin
passwd:admin
ip: 35.190.154.219
```

## Nexus
```
username: admin
passwd:admin
(command to run for encryption=== mvn -emp admin)
Nexus encrypted passwd: S7fmYYvs82kHrDTWzl3ua3E9+lmduKlTJgVWttZITDU= 
nexus encrypted passwd master === q/A25qcxJ7gHFAUVKbitXDejIceFw3oJ7cfTNr+vM9c=
ip: 35.237.157.26
```
## GitHub
```
webhook: http://35.227.92.0:8080/github-webhook/
username:ibiba-briggs
passwd:mpakAb7660#
```
## Jenkins
```
username: admin
passwd: admin
ip: 35.190.154.219
```
## Ansible
```
username: ansible
passwd: ansible
ip:35.190.154.219
```




<?xml version="1.0" encoding="UTF-8"?>

<settings xmlns="http://maven.apache.org/POM/4.0.0"
        xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
          xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/settings-1.0.0.xsd">

  <localRepository>/var/lib/jenkins/.m2/repository</localRepository>

<servers>
   <server>
        <id>nexus</id>
        <username>admin</username>
        <password>{q/A25qcxJ7gHFAUVKbitXDejIceFw3oJ7cfTNr+vM9c=}</password>
    </server>
</servers>

<mirrors>
    <mirror>
      <id>nexus</id>
      <name>nexus</name>
      <url>http://35.229.97.95:8081/repository/maven_project/</url>
      <mirrorOf>*</mirrorOf>
    </mirror>
  </mirrors>

</settings>

Oracle Account Credentials
    - Username: mbandiawan@gmail.com
    - Password: JJTech@Accelerate2021