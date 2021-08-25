# README #

Two ways to install interactive modeling

Repo:
https://bitbucket.org/surflab/blender-interactive-modeling/src/master/

Method 1:
Put folder of interactive modeling in the addon folder of Blender (on Linux, the path would be a little different)
```
cd /Applications/Blender.app/Contents/Resources/2.82/scripts/addons/
git clone https://USER_NAME@bitbucket.org/surflab/blender-interactive-modeling.git
```

Method 2:
Install addon in Blender using zip file
Launch Blender >> Edit >> Preferences >> Add-ons >> Install >> select "blender-interactive-modeling.zip"

-- Kyle

### Execute Addon in Blender ###
#### 1. How to find the installed addon? ####
Click on the small left angle bracket to expand the panel

![Alt text](img_readme/find_addon_panel_1.png)

Then switch to the tab of interactive modeling

![Alt text](img_readme/find_addon_panel_2.png)

### Troubleshooting ###
#### 1. Not able to install addon properly ####
The error such as

![Alt text](img_readme/missing_script_file.PNG)

Can be solved by removing old addon

![Alt text](img_readme/remove_old_addon.png)
