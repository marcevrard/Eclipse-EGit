# Eclipse – GitHub

Tutorial to use Eclipse with GitHub through EGit

####Marc Evrard

January 26, 2015

---

### Register a GitHub account
* <https://github.com>
* As student you can request an Education account: <br> <https://education.github.com>
<br>
It allows you to create private repositories (among other things)

###Install Git
* Tell Git your name:<br>
`git config --global user.name "YOUR NAME"`
* Tell Git the email address that will be associated with your Git commits (should be the same one found in your email settings)<br>
`git config --global user.email "EMAIL"`

For more info see:<br>
<https://help.github.com/articles/set-up-git/#platform-linux>

###Install and Setup EGit in Eclipse
* Install/update EGit from the Marketplace (if the last version is not already included in your Eclipse package)
* Add the Git command shortcuts in your Perspective (workspace dedicated to a particular language)
* ___Window___ > ___Customize Perspective___
* Select Git in ___Command Groups Availability___
![](/Docs/Images/part1-02.png?raw=true)

###Setup EGit in Eclipse
* Add the Git control tabs in the bottom window:<br>
(near the ___Problems___ tab)
![](/Docs/Images/part2-01.png?raw=true)

###Setup EGit
* Check the Git configuration in the Preference
* If the Git setup (see above) went well the config should be already completed
* You can add or amend all settings from here
![](/Docs/Images/part1-01.png?raw=true)

* Set the default cloned repository location:
* Check this tutorial for more info on using EGit:<br>
<http://www.vogella.com/tutorials/EclipseGit/article.html>
![](/Docs/Images/part1-03.png?raw=true)

---

###Add an existing project to GitHub
* Use the Project context menu (right-click on the project folder)
* Select ___Team___ > ___Share Project___
* Select ___Git___ > ___Next___
![](/Docs/Images/part2-03.png?raw=true)

* In the ___Configure Git___ Repository click on ___Create___
* Enter the local path
* Click ___Finish___
![](/Docs/Images/part2-04.png?raw=true)

* Click on the shortcut to first commit locally:
![](/Docs/Images/part2-12.png?raw=true)
* Select all required files (project files are optional)
* Input the message
* Press ___Commit___
![](/Docs/Images/part2-05.png?raw=true)

* Create a new repo on GitHub
* Copy the Clone link
* Click on the Push shortcut to start the push wizard
![](/Docs/Images/part2-13.png?raw=true)
* The link will be automatically added as well as other required fields
* Click on ___Next___
![](/Docs/Images/part2-06.png?raw=true)

* Click the ___advanced push___ link
![](/Docs/Images/part2-07.png?raw=true)

* All good, click ___Next___
![](/Docs/Images/part2-08.png?raw=true)

* Select ___master___ in ___Source___ and in ___Destination___
* Click ___Add Spec___
* Click ___Next___
![](/Docs/Images/part2-09.png?raw=true)

* Select ___Show dialog...___
* Click ___Finish___
![](/Docs/Images/part2-10.png?raw=true)

* The next time you commit, select ___Commit and Push___
* You may need to select ___Show dialog...___ again
* Click ___Finish___
![](/Docs/Images/part2-11.png?raw=true)

---

###Import an Eclipse project from GitHub
* Use the project contextual menu and select ___Import___
* Select ___Git___ > ___Projects from Git___
* Click ___Next___
![](/Docs/Images/part3-02.png?raw=true)

* Copy the ___Clone___ link from the GitHub repository
* Past in ___URI___, all other fields will be automatically updated
* Click ___Next___
![](/Docs/Images/part3-01.png?raw=true)

* All good, click ___Next___
![](/Docs/Images/part3-03.png?raw=true)

* All good, click ___Next___
![](/Docs/Images/part3-04.png?raw=true)

* Select ___Import existing projects___
* Click ___Next___
![](/Docs/Images/part3-05.png?raw=true)

* Select the projects you want to import from the repository
* Click ___Finish___
![](/Docs/Images/part3-06.png?raw=true)

---

###Import any project from GitHub
* E.g., in case you haven't included the `.project` and `.cproject` in GitHub
* You will need to ___Import as a general project___
* Click ___Next___
![](/Docs/Images/part3-05.png?raw=true)

* In the contextual menu of the project:<br>
select ___New___ > ___Convert to C/C++ Project...___
![](/Docs/Images/part4-02.png?raw=true)

* Chose ___Executable___ and the appropriate ___Toolchains___
* Click ___Finished___
![](/Docs/Images/part4-01.png?raw=true)
