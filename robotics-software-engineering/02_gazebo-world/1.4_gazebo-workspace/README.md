# ToDo - Instructions
Follow these simple steps to boot up Gazebo in your Workspace:

* Open Udacity's VM workspace (Ubuntu 20.04 LTS) or the local VM image (Ubuntu 18.04 LTS) running on your VMWare/VirtualBox to practice the current exercise. If you haven't already, review the overview and restrictions outlined in the Ubuntu VM Workspace - Overview page.

* Once you log into the VM, open a Terminal window.

* Update and upgrade the Workspace image to get the latest features of Gazebo. To do so, open a terminal, and write the following statement:

```bash
$ sudo apt-get update && sudo apt-get upgrade -y 
```
Note: Remember to update and upgrade your image after each reboot since these updates(or any package that you install) are not permanent. Ignore any error you get while upgrading.

* Now launch Gazebo from the terminal by typing:
```bash
$ gazebo
```
Be advised that occasionally Gazebo gets stuck in a loading loop. If Gazebo does not fully load after about one minute, try closing it by pressing Ctrl+C while the Gazebo terminal is active. Then, try running the command again to restart Gazebo.