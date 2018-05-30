## 1: On GitHub fork the PlaygroundProjectStarter code

* Log into your GitHub account.
* Search for _playgroundprojectstarter_.
* Select the repository, by clicking on its name.
* After the page loads you should see a `fork` button in the upper right hand corner.
* Click on the `fork` button to make a copy in your GitHub account.
* The result will be a new repository in your GitHub profile.

## 2: Launch Git Bash

* Using Windows Explorer, navigate to your class folder.
* Right-click on the folder and choose `Git Bash Here` - this launches the Git Bash _shell_.
* The _working directory_ of the shell will be your class folder.

## Tell Git not to check SSL certificates

Enter this command and press the Enter key to execute it.

```bash
git config --global http.sslVerify false
```

## Clone your PlaygroundProjectStarter repository

Go to your GitHub profile and then into your PlaygroundProjectStarter repository. Click on the green `Clone or download` button, then click on the clipboard icon. This will copy the URL of your forked repository to your clipboard. Then type:

```bash
git clone 
```
After typing that, right-click and choose Paste from the context menu to add the URL of your repository after `git clone`.

Hit the `Enter` key to run the command and clone the repository to your computer.

## Open the PlaygroundProjectStarter in Unity

* Launch Unity
* From the startup splash screen choose `Open`
* Navigate to your PlaygroundProjectStarter folder
* Click on the `Select Folder` button
* Unity will open the PlaygroundProjectStarter - this will take quite a while.
* Test out one or more of the games in the Examples folder in the Project pane.

## Submit your work

To complete the assignment:

1. Verify that you have submitted a link to your GitHub profile, and
1. Submit a screen capture of Unity running one of the PlaygroundProjectStarter example games.
