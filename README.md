# Loot-to-Dropbox

<h1> Here you will learn how to set up and save loot to Dropbox using Ducky and powershell scripts </h1>

1. To Start you will want to create a dropbox account which i assume most will already have.
2. Now we will head over to https://dropbox.com/developers/apps .
    From here you should create an app by clicking the "Create app" button.
    
    <img width="635" alt="image" src="https://user-images.githubusercontent.com/116710663/198232914-4ddcacef-1c62-4da5-9e1f-b89de08dddca.png">

3. After clicking create app, copy the configuration as follows and name your app then click "Create app" in the bottom right:

<img width="553" alt="image" src="https://user-images.githubusercontent.com/116710663/198233650-834641cb-1807-4871-9b37-1bf7e0ed3c4c.png">

4. After creating the app, head over to the permissions tab in the menu bar at the top.

<img width="556" alt="image" src="https://user-images.githubusercontent.com/116710663/198234225-3b692f2f-1870-4d65-a7a5-1c027534f1f3.png">

Configure permissions as follows and click submit at the bottom of your screen:

<img width="589" alt="image" src="https://user-images.githubusercontent.com/116710663/198234555-c5aac8a7-429d-4d51-ba84-55ae992cfbc3.png">

5. Now head back to settings (Next to "permissions" on the navigation bar at the top).
6. Scroll down until you see "Generate Access Token" and click it then copy the generated code.

<img width="428" alt="image" src="https://user-images.githubusercontent.com/116710663/198235576-42c2dc31-7d2c-4181-866f-7596fc1cda94.png">

This key will be pasted into the .ps1 script of your payload, I will be using Jakoby's ADV-RECON payload for the O.MG cable in this example.
(Note. These Keys only last for about 4 hours, after expiration you will have to generate a new one)

<img width="685" alt="image" src="https://user-images.githubusercontent.com/116710663/198237330-e20740e4-185e-41f6-b833-33efae0fe089.png">

7. Now head back to https://dropbox.com/home . Here you will now find a new folder called Apps and a sub-folder with the name of your app inside of it.

<img width="887" alt="image" src="https://user-images.githubusercontent.com/116710663/198239000-1b333e61-3a12-42f6-8fd5-4dd549228000.png">

8. Enter the folder named after your app and upload the .ps1 file withe the access key.

<img width="775" alt="image" src="https://user-images.githubusercontent.com/116710663/198239310-e587306e-f5fd-4fa2-966e-1c5995f4ab4c.png">

9. Copy the link to the .ps1 file and paste it into you payload (Remember to change the "?dl=0" at the end of the link to "?dl=1"). 

<img width="775" alt="image" src="https://user-images.githubusercontent.com/116710663/198239749-cbc8c40b-c446-4916-9474-e57e4826ceca.png">

<img width="454" alt="image" src="https://user-images.githubusercontent.com/116710663/198240217-2937057b-3af6-4690-806c-6b2419e141d9.png">

Now run your payload and your loot will appear in the folder with the .ps1 file.

<img src= https://i.gifer.com/3APO.gif/>
