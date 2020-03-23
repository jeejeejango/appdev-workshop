# Appendix: Environment Info

<!-- TOC -->

- [OpenShift](#openshift)
- [Git Server](#git-server)
- [Nexus Repository](#nexus-repository)
- [SonarQube](#sonarqube)
- [Jenkins](#jenkins)
- [CodeReady Workspaces](#codeready-workspaces)
- [ServiceMesh Kiali](#servicemesh-kiali)
- [Bookinfo Example](#bookinfo-example)
- [Workshop Docs](#workshop-docs)
- [OpenShift Docs](#openshift-docs)

<!-- /TOC -->

You find all urls, hostnames, usernames and passwords that are needed during the labs in this page. Note that the urls are also embedded inside each lab instructions.

## OpenShift

Master URL: api.\<cluster url\>:6443

Console URL: https://console-openshift-console.apps.\<cluster url\>

```
Replace with the userid provided to you by the instructor.
```

- Username: \<userid - htpasswd userid/LDAP ID\>
- Password: \<password - htpasswd/LDAP password\>


## Git Server

Web: http://gogs-devops.apps.\<cluster url\>

Service: http://gogs.devops.svc:3000

- Username: \<userid - htpasswd userid/LDAP ID\>
- Password: \<password - htpasswd/LDAP password\>
- Provider: AD/LDAP/Local


## Nexus Repository

Web: http://nexus-devops.apps.\<cluster url\>

Service: http://nexus.devops.svc:8081

- Username: admin
- Password: \<provided by Administrator\>


## SonarQube
Web: http://sonarqube-devops.apps.\<cluster url\>

Service: http://sonarqube.devops.svc:8081

- Username: admin
- Password: \<provided by Administrator\>


## Jenkins
Web: https://jenkins-devops.apps.\<cluster url\>/

- Username: \<userid - htpasswd userid/LDAP ID\>
- Password: \<password - htpasswd/LDAP password\>


## CodeReady Workspaces

Register an account on Eclipse Che using an email address.

Web: http://codeready-workspaces.apps.\<cluster url\>

Git Project: https://gogs-devops.apps.\<cluster url\>/gogsadmin/codeready

## ServiceMesh Kiali

Web: https://kiali-istio-system.apps.\<cluster url\>/console/overview

- Username: \<userid - htpasswd userid/LDAP ID\>
- Password: \<password - htpasswd/LDAP password\>


## Bookinfo Example
Web: http://istio-ingressgateway-istio-system.apps.\<cluster url\>/productpage


## Workshop Docs

Web: https://gogs-devops.apps.\<cluster url\>/gogsadmin/


## OpenShift Docs

Web: https://docs.openshift.com/container-platform/4.2/welcome/index.html


[Previous](devops-codeready-workspaces.md) | [Top](README.md) 
