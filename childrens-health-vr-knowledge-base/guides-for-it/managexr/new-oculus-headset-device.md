# New Oculus Headset Device

### Preparing an Oculus Device

**OOBE (Out of Box Experience) Oculus Device**

This section will guide you through getting the oculus headset out of the box and ready for you to enroll.

1. Put the headset on and power it up.
2. Activate both controllers by pressing a button.
3. Follow the on screen prompts until you get to WiFi Connection
   1. The device needs to be connected to a network other than RedBalloon. I suggest using cmcuser with your Children's credentials
4. Watch the intro video (it stops playing if you remove your headset)
5. The headset and controllers may need to update (you can remove the headset for this)
6. Once the device reboots you will need to take off the headset and use the phone with the Oculus Developer account to pair it
7. Open Oculus App on your phone
8. Click Pair when prompted
9. Set the Floor level
10. Select Switch to stationary Boundary when prompted to create the Boundary area
11. Follow the on screen prompts until you are taken to the lobby room (palm trees and canyon)

Preparing an Oculus Device for Registration

**Enable Developer Mode on the Device**

1. If you haven't already, [create a developer account on Oculus](https://developer.oculus.com/sign-up/?login\_redirect\_uri=https%3A%2F%2Fauth.oculus.com%2Flogin%2F\&redirect\_uri=https%3A%2F%2Fdeveloper.oculus.com%2F). _(This only needs to be done once. If you're already using a developer Oculus account, skip to step 2)_
   1. On your computer, go to [dashboard.oculus.com](https://dashboard.oculus.com/)
   2. Login to your Oculus Developer account
   3. [Click this link to create an "organization"](https://developer.oculus.com/manage/organizations/create/)
   4. Accept the developer agreement
2. Enable Developer Mode using the Oculus App on your phone.
   1. On your phone (iOS or Android device), open the Oculus app
   2. Navigate to the **Devices** tab
   3. Find your device and tap **Developer Mode**
   4. Enable developer mode

The Device Setup Tool will now recognize your device when you plug it into your computer.

**Download and Launch the Device Setup Tool**

We register devices to ManageXR using the ManageXR Device Setup Tool. The Device Setup Tool is a separate application that you must download and run on your computer.

1. Download the latest Device Setup Tool:
   * Download for [Mac](https://console.managexr.com/downloadDeviceSetupTool?os=mac)
   * Download for [Windows](https://console.managexr.com/downloadDeviceSetupTool?os=win)
2. Launch the Device Setup Tool
   * **Windows**
     1. The Device Setup Tool will download as a zip folder. Unzip the folder and launch the "ManageXRDeviceSetupTool.exe".
     2. After launching, you may get a "Windows protected your PC" popup. Click "More info", then select "Run anyway".
   * **Mac**
     1. The Device Setup Tool will download as a .dmg. Open the .dmg and then drag the program into your applications folder as prompted.
3. Log in to the Device Setup Tool using your ManageXR account email and password.
   1. Note: You can also use the Device Setup Tool without logging in if you have a Registration Code. Read more about [registering a device with a Registration Code here](https://help.managexr.com/en/articles/5345978-register-a-new-device-using-a-registration-code).

**Remove all Android accounts (Required for Oculus Firmware v28+)**

1. Launch the Device Setup Tool and plug your device into your computer.
2. The device status will read **Not Authorized**. You need to authorize your computer to connect from within the headset. Inside of the headset, you will have two separate popups you must accept. The first will allow USB debugging, be sure to select **Always Allow** for this option. For the second popup, we will click **Allow** to give permission for your computer to access files on the device.
3. The device status should now read **Requires Preparation**. If it doesn't, refresh your device using the Device Setup Tool.
4. Put on your headset now to find a special settings menu. (If the special settings menu is not open, click **Refresh Device**)
5. Scroll down and click on the **Accounts** option.
6. Remove all accounts from the device. It will most likely have an **Oculus** and **Facebook** account. In some cases, there may be other accounts on this list, you must remove those as well. Once all of the accounts are removed, immediately move on to the next step.

### Register an Oculus Headset Device

This section is going to cover the enrollment process for the headset to ManageXR. This section assumes you have already followed all of the steps above.

1. Ensure the Status is "Ready For Install". If it isn't, hover over the status for more instructions, or read about the various statuses [here](https://help.managexr.com/en/articles/5296578-register-a-new-device#h\_afbba777ff).
2. Enter your device's target Configuration and Name
3. Click "Install"
4. ![image](<../../../.gitbook/assets/0 (9)>)
5. Log into ManageXR and assign the desired configuration to the device.
6. Hit Sync on the device page to force the device to check in with the server and retrieve the latest configuration
7. The device will download the assigned apps and launch the HomeScreen.

Guided video: [Oculus Device Setup Tutorial](https://youtu.be/0at9Oz2EPlw)

![Video titled: Oculus Device Setup Tutorial](<../../../.gitbook/assets/1 (6)>)
