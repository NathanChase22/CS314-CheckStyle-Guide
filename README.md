# CS314-CheckStyle-Guide

Hey guys! So I created a github that'll included needed files and links for installation processes for a few IDE's that y'all could be using.
Of course if you wish for me to add another one, then I will do so. 

*NOTE: I am not 100% sure of either the IntelliJ or VsCode's installation processes, however I hope these given links will help guide you.

## INSTALLATION FOR ECLIPSE FOUND HERE:
https://wiki.cs.jmu.edu/student/eclipse/checkstyle (guide for installation)

## INSTALLATION FOR INTELLIJ FOUND HERE:
https://www.jetbrains.com/help/idea/managing-plugins.html (guide for installation of plugins)

https://plugins.jetbrains.com/plugin/1065-checkstyle-idea (plugin itself found here)

## INSTALLATION FOR VSCODE FOUND HERE:
https://code.visualstudio.com/learn/get-started/extensions (guide for installation of extension)

https://marketplace.visualstudio.com/items?itemName=shengchen.vscode-checkstyle (the extension itself)

# Getting it to work with Eclipse

Okay! So you have CheckStyle installed for your IDE. Now you need to setup the proper configurations, I'm afraid I'm only familar 
with how it works on Eclipse. 

## STEP 0: 
Now before we do anything let's consider if you've sucessful installed the plug in. To do do this go to 
** Preferences > Checkstyle ** if you don't see a newly made option for CheckStyle then you must've done the installation wrong. 

## STEP 1: 
Download the XML file provided here, make sure to put it in a directory where you can easily find it for installation. 

## STEP 2: 
click through the **CheckStyle** menu option and there should be a table called ***Global Check Configurations*** 
this is where all of your CheckStyle configurations will appear. Currently you should have *Google Checks* and *Sun Checks* already provided 
to you, however these configurations are not the same as Mike Scott's and I will not recommend using them.

## STEP 3: 
To the right of the configurations table there should be a button labled **New...** click on this. Upon clicking it a window pops up prompting 
you to give a name and type of configuration for your CheckStyle config. I would keep it as a ***Internal Configuration*** and put something like 
'CS314 Checks
