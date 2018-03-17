#Managing Users
Jenkins makes managing users simple.

##Prerequisites
Refer to [Post-installation setup wizard](https://jenkins.io/doc/book/installing/#setup-wizard) to set up the initial administrator account before getting started.

##Enable users to create accounts
1. Log into Jenkins as an administrator. If necessary, [disable security features](https://jenkins.io/doc/book/system-administration/security/#disabling-security) to gain universal access for set-up.
1. From the Jenkins Dashboard, click **Manage Jenkins** > **Configure Global Security** > check **Enable Security**
1. Under **Security Realm** > check **Jenkins' own user database** > check **Allow Users to sign up**
1. Under **Authorization** > check **Logged-in users can do anything** > **Allow anonymous read access**
1. Click **Save**.

##Create a new account


##Access list of Users
1. From the Jenkins Dashboard, click **People**.

![People page on Jenkins site](https://github.com/boko91/jenkins-test-implementation/blob/master/jenkins-people.png)

##
