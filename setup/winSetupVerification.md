# Setup Verification For Windows


### Git

1. Open Git Shell (installed as part of GitHub Desktop) and check the git version using the command: 

		git --version

    You should see something like this (your version number may be slightly different):

    ![Git Version](images/winGitVersion.png)
 
### IntelliJ IDEA

1. Open IntelliJ IDEA.
1. The dialog below should open. If it doesn't, click "Configure" on the Welcome Screen, and then "Manage License".

    ![Activation Screen](images/winIntelliJLicenseActivationEmpty.png)
    <br/><br/>

1. Choose to activate a new license with your JetBrains Account and complete the form with your username/email and password.

    ![Activation Screen](images/winIntelliJLicenseActivation.png)
    <br/><br/>

1. You should see a welcome screen like this:

    ![Welcome Screen](images/winIntelliJWelcomeScreen.png)

### TomEE+

1. Navigate to the bin directory of your tomEE+ install directory.  
1. Run startup.bat to start the server. 

    ![Tomee home page](images/winTomeeStartup.png)

    You should see something like this:  

    ![Tomee home page](images/winTomeeStarted.png)

1. Open a browser and navigate to http://localhost:8080. You should see this: 

    ![Tomee home page](images/TomcatSuccess.png)

1. If startup.bat fails, refer to the RUNNING.txt file in the root tomee install directory for help troubleshooting.

### MySQL

1. Open MySQL Command Line Client. 
1. Enter the password you set up during installation. 
    
    ![MySQL Server Log in](images/winMySQLLogin.png)

1. Show databases to confirm things are working to this point. You should see something like:  

    ![MySQL Server Log in](images/winMySQLShowDatabases.png)

