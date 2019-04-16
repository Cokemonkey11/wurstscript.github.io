---
title: Install WurstScript
sections:
  - Install Compiler
  - Create Project
  - Update and import Projects
---

Now we will setup a Wurst compiler environment and create a project using the the Wurst Setup.

[*&nbsp;*{: .fa .fa-download} Download WurstSetup](https://grill.wurstlang.org/hudson/job/WurstSetup/lastSuccessfulBuild/artifact/downloads/WurstSetup.jar){: .btn .btn-green}

Once the download has finished, run the .jar to begin.

![](/assets/images/setup/WurstSetup.png){: .img-responsive}

### Install Compiler

The setup will check if the compiler has already been installed. If not, you are required to install it
before you can create a project.

To install the compiler simply click the **Install Wurst** button.
When everything is done, the setup should tell you that your installation is up to date and the **Create Project** button is now enabled:

![](/assets/images/setup/WurstInstallDone.png){: .img-responsive}

### Create Project

Now that the compiler is installed you can go ahead and create your Wurst project.
Select your desired project folder and name and start the process by clicking the **Create Project** button.
The setup will now create a wurst project structure and download the necessary dependencies.
If everything setup correctly, you should see the following message:

![](/assets/images/setup/ProjectSetupDone.png){: .img-responsive}

When the setup has finished, you can now open the project's root folder in VSCode.

{: .answer}
### *&nbsp;*{: .fa .fa-exclamation-circle} Make sure you are opening the project's root folder (contains wurst.build file) using `File -> Open Folder`

Once the project is opened, you can click the Hello.wurst file on the left to activate the Wurst plugin. The code should compile and the setup should be done.

If you are new to WurstScript but not new to programming, you probably want to continue with the [*&nbsp;*{: .fa .fa-external-link-square} Beginner's Guide](tutorials/wurstbeginner.html)

### Update and import Projects

By clicking the import button you can load an existing wurst.build file. After a successful load clicking the `Update Project` button will update your dependencies and generate local files as necessary. Use this feature to update your existing projects and to import projects which you didn't create.

