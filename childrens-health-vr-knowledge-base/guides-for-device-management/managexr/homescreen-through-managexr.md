# Homescreen Through ManageXR

**Creating a Homescreen Through ManageXR**

For now, Innovation Lab Specialist will be responsible for this process. A homescreen will be created when a clinic goes live with VR that has not used VR before. This happens 1-2 times a quarter.

**PURPOSE:** Adding a homescreen prevents patients and/or staff from accessing unapproved applications / the app store. It “locks down” the device and only allows the user to access approved apps.

\*\* If the headset you are using still needs to be registered onto ManageXR, please refer to this document: [Registering a Headset on ManageXR.docx](https://dallaschildrens.sharepoint.com/:w:/t/InnovationTeam/Ec4JztNrYGpInuNKoG5Lu7QBv-l\_lwKXyAj4ojMNH0YtgA?e=SaPctn)

**Step 1: Ensure that the apps you want to include on the headset show up as installed apps on ManageXR.**

* Different Oculus accounts may contain different installed apps. Log into the account that you wish to make a homescreen for on your headset & Oculus app (on your phone). Ensure that the apps you wish to include on your homescreen are actually installed on your device.
* Open the ManageXR dashboard on your computer.
* Click on ‘Devices’ in the left menu and select the device that you are using.
* Click on ‘Installed Apps’ and toggle “Show System Apps” to show the apps that are installed on your device. Ensure that all of the apps you wish to include on the homescreen are listed.

**Step 2: Uploading the apps / package names as External apps**

* Take a picture of or list the names of the apps and their package names (this is so you will not have to go back and forth)
* Click on ‘VR Content’ on the left menu, then click on ‘Add Content’ at the top. Then click on ‘External’
* For each app, you will type in the name of the app in title, and the package name
  * Example”
    * Title: Beat Saber
    * Package name: com.beatgames.beatsaber
* You will also have to upload cover photos of each app (these images will appear on the homescreen)
  * A 256 x 256 square JPEG or PNG image is recommended
  * Ensure the picture is standard, good quality, and contains the name of the app
  * You may have to crop the image so that the length and width dimensions are equal or nearly equal (as close to a square as possible)
* You will have to repeat these steps for each app. (Add Content > External > type in the name of the app > type in the package name exactly how it appeared in the VR Content list > add a good quality square picture > Save Changes)

**Step 3: Deploying the apps you want to include in the homescreen to a configuration group**

* Once you have finished adding all of the apps as external apps, click on ‘Configurations’ in the left menu. There will be a box at the top left where you can type in the name of a new configuration.
* Create a new configuration for each clinic’s home screen (because each clinic has different apps).
  * **Name of configuration: \_\_\_(Clinic)\_\_\_ PM\&R Home Screen**
* See the ‘Richardson PM\&R Home Screen’ Configuration as an example.
  * ![](<../../../.gitbook/assets/0 (1)>)
* A list of Deployed Apps as well as the full App Library should appear. Scroll down the App Library list on the right and click ‘Deploy’ for all of the apps you wish to include on the homescreen.

**Step 4: Creating the homescreen**

* Once you have finished deploying all of the desired apps to the configuration, click on ‘Device Experience’
* A visual of what the homescreen will look like should appear. You can rearrange the apps and customize the homescreen. You can also add images to change the logo & background.
  * See below for the pictures used for the Richardson home screen:
    * [ManageXR Home Screen Images](https://dallaschildrens.sharepoint.com/:f:/t/InnovationTeam/Ep8O0C62-0RPi2wu4GHzUkoB1IK4LUZrEaGMSHhORhZuWA?e=Eyo4Ns)
* Additionally, click Settings Display and ensure that a PIN is required to access Admin Settings.
* This will be the homescreen for the devices in that clinic’s configuration.

**Step 5: Add the specific clinic’s headset to the configuration.**

* In ‘Devices’, click on the clinic device that you just made a home screen for.
* Click on the Configuration drop down menu near the top of the device page and select the configuration for that clinic.
  * ![](<../../../.gitbook/assets/1 (1)>)
