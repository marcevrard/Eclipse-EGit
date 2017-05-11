# Eclipse – GitHub

Tutorial to use Eclipse with GitHub through EGit

#### Marc Evrard

January 26, 2015

---

### Register a GitHub account
* <https://github.com>
* As student you can request an Education account: <br> <https://education.github.com>
<br>
It allows you to create private repositories (among other things)

### Install Git
* Tell Git your name:<br>
`git config --global user.name "YOUR NAME"`
* Tell Git the email address that will be associated with your Git commits (should be the same one found in your email settings)<br>
`git config --global user.email "EMAIL"`

For more info see:<br>
<https://help.github.com/articles/set-up-git/#platform-linux>

### Install and Setup EGit in Eclipse
* Install/update EGit from the Marketplace (if the last version is not already included in your Eclipse package)
* Add the Git command shortcuts in your Perspective (workspace dedicated to a particular language)
* ***Window*** > ***Customize Perspective***
* Select ***Git*** in ***Command Groups Availability***

![](/Docs/Images/part1-02.png?raw=true)

### Setup EGit in Eclipse
* Add the Git control tabs in the bottom window:<br>
(near the ***Problems*** tab)

![](/Docs/Images/part2-01.png?raw=true)

### Setup EGit
* Check the Git configuration in the Preference
* If the Git setup (see above) went well the config should be already completed
* You can add or amend all settings from here

![](/Docs/Images/part1-01.png?raw=true)

* Set the ***Default repository folder*** path:

![](/Docs/Images/part1-03.png?raw=true)

* Check this tutorial for more info on using EGit:<br>
<http://www.vogella.com/tutorials/EclipseGit/article.html>

---

### Add an existing project to GitHub
* Use the Project context menu (right-click on the project folder)
* Select ***Team*** > ***Share Project***

![](/Docs/Images/part2-03.png?raw=true)

* Select ***Git*** > ***Next***

* In the ***Configure Git*** Repository click on ***Create***
* Enter the ***Repository directory*** path

![](/Docs/Images/part2-04.png?raw=true)

* Click ***Finish***

* Click on the shortcut to first commit locally:

![](/Docs/Images/part2-12.png?raw=true)

* Select all required files (project files are optional)
* Write the message

![](/Docs/Images/part2-05.png?raw=true)

* Press ***Commit***

* Create a new repo on GitHub
* Copy the Clone link
* Click on the Push shortcut to start the push wizard

![](/Docs/Images/part2-13.png?raw=true)

* The link will be automatically added as well as other required fields

![](/Docs/Images/part2-06.png?raw=true)

* Click on ***Next***

![](/Docs/Images/part2-07.png?raw=true)

* Click the ***advanced push*** link

![](/Docs/Images/part2-08.png?raw=true)

* All good, click ***Next***

* Select ***master*** in ***Source*** and in ***Destination***
* Click ***Add Spec***

![](/Docs/Images/part2-09.png?raw=true)

* Click ***Next***

![](/Docs/Images/part2-10.png?raw=true)

* Select ***Show dialog...***

* Click ***Finish***

* The next time you commit, select ***Commit and Push***

![](/Docs/Images/part2-11.png?raw=true)

* You may need to select ***Show dialog...*** again
* Click ***Finish***

---

### Import an Eclipse project from GitHub
* Use the project contextual menu and select ***Import***
* Select ***Git*** > ***Projects from Git***

![](/Docs/Images/part3-02.png?raw=true)

* Click ***Next***

* Copy the ***Clone*** link from the GitHub repository
* Past in ***URI***, all other fields will be automatically updated

![](/Docs/Images/part3-01.png?raw=true)

* Click ***Next***

![](/Docs/Images/part3-03.png?raw=true)

* All good, click ***Next***

![](/Docs/Images/part3-04.png?raw=true)

* All good, click ***Next***

* Select ***Import existing projects***

![](/Docs/Images/part3-05.png?raw=true)

* Click ***Next***

* Select the projects you want to import from the repository

![](/Docs/Images/part3-06.png?raw=true)

* Click ***Finish***

---

### Import any project from GitHub
* E.g., in case you haven't included the `.project` and `.cproject` in GitHub
* You will need to ***Import as a general project***

![](/Docs/Images/part3-05.png?raw=true)

* Click ***Next***

* In the contextual menu of the project:<br>
select ***New*** > ***Convert to C/C++ Project...***

![](/Docs/Images/part4-02.png?raw=true)

* Chose ***Executable*** and the appropriate ***Toolchains***

![](/Docs/Images/part4-01.png?raw=true)

* Click ***Finish***
