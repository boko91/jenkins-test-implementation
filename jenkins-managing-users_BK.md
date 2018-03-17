#Managing Users
Jenkins allows users with administrative access to create, modify and delete user accounts.

##Prerequisites
Refer to [Post-installation setup wizard](https://jenkins.io/doc/book/installing/#setup-wizard) to set up the initial administrator account before getting started.

##Directions
All path instructions in this topic begin at the Jenkins Dashboard.

##View list of existing users
To access the existing list of users, click **People**.

##Enable users to create accounts
1. Log into Jenkins as an administrator. If necessary, [disable security features](https://jenkins.io/doc/book/system-administration/security/#disabling-security) to gain universal access for set-up.
1. Click **Manage Jenkins** > **Configure Global Security** > check **Enable Security**
1. Under **Security Realm** > check **Jenkins' own user database** > check **Allow Users to sign up**
1. Under **Authorization** > check **Logged-in users can do anything** > **Allow anonymous read access**
1. Click **Save**.

**Note:** If you need to integrate with a 3rd party credential platform, refer to [Using credentials](https://jenkins.io/doc/book/using/using-credentials/).

##Create a new account as an administrator
To enter a new user account as an administrator, click **Manage Jenkins** > **Manage Users** > **Create User**.

##Create a new account as a user
Once account creation is enabled, new users can create new accounts easily by clicking **sign up** on the Jenkins Dashboard.

##Configure list of users
To make administrative changes to users, go to **Manage Jenkins** > **Manage Users** > ![Gear icon](/image/jenkins-gear-icon.png)

##Delete user
To delete a user, click **Manage Jenkins** > **Manage Users** > ![Delete icon](/image/jenkins-delete-icon.png)
