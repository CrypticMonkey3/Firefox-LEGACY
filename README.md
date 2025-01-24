# Firefox-LEGACY
The firefox customisations I rock.

## Setup
1. Enter and submit 'about:support' in the address bar (without the speech marks). View the section: "*Application Basics*". <br>Depending on the OS you are using you want to find:<ul><li>"*Profile Directory*" for linux</li><li>"*Profile Folder*" for windows or mac</li></ul><br>Then click the "*Open Directory/Open Folder/Show in Finder*" button which will take you to the firefox profile for your user.
![image](https://github.com/user-attachments/assets/2ca4bbcc-4b75-4d82-b2c1-36ecd11e7295)

2. You'll see a bunch of folders and files. However, you want to find a folder called: "*chrome*", if you can't that's perfectly fine, just create a folder called "*chrome*".

3. Next, dump the img folder and userContent.css flie from this repo into the "*chrome*" folder.

4. Almost there now, go back to your firefox browser and enter 'about:config' in the address bar. A warning for risk will pop-up, however, nothing harmful or suspicious is being done in the css file (you can check yourself if you don't trust it), so there's nothing to worry about and you can accept it.

5. In the search bar, paste:
> toolkit.legacyUserProfileCustomizations.stylesheets

and set the value to true. This tells Firefox to load the CSS file at startup

6. To see the changes, close the firefox browser and restart the application, and voila~
