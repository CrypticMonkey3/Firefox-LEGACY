# Firefox-LEGACY
The firefox customisations I rock.

![image](https://github.com/user-attachments/assets/367859f5-57d6-4af9-b7f6-e4357733cc4a)


## Setup
1. Enter and submit 'about:support' in the address bar (without the speech marks). View the section: "*Application Basics*". <br>Depending on the OS you are using you want to find:<ul><li>"*Root Directory*" for linux (use the directory with the .default-release suffix)</li><li>"*Profile Folder*" for windows or mac</li></ul><br>Then click the "*Open Directory/Open Folder/Show in Finder*" button which will take you to the firefox profile for your user.
![image](https://github.com/user-attachments/assets/2ca4bbcc-4b75-4d82-b2c1-36ecd11e7295)

2. You'll see a bunch of folders and files. However, you want to find a folder called: "*chrome*", if you can't that's perfectly fine, just create a folder called "*chrome*".

3. Next, dump the img folder and userContent.css flie from this repo into the "*chrome*" folder.

4. Almost there now, go back to your firefox browser and enter 'about:config' in the address bar. A warning for risk will pop-up, however, nothing harmful or suspicious is being done in the css file (you can check yourself if you don't trust it), so there's nothing to worry about and you can accept it.

5. In the search bar, paste:
> toolkit.legacyUserProfileCustomizations.stylesheets

and set the value to true. This tells Firefox to load the CSS file at startup

6. To see the changes, close the firefox browser and restart the application, and voila~

## Instabilities
This customisation ONLY works well with the below firefox settings:

![image](https://github.com/user-attachments/assets/066246ca-aa75-417d-91ae-a997709fd4ac)

## Milestones
### 10 Stars
If this repo gets 10 stars, I'll consider adding a feature for stories

### 20 Stars
In this case I'll implement a way for multiple rows of shortcuts as well as a thing for Recent Activities.

### 50 Stars 
I'll fix any other issue, like the look for editing a recent site as well as any other things.

### 100+ Stars
Don't know how this got to be, but I'll make a customisation for tabs with the userChrome.css file
