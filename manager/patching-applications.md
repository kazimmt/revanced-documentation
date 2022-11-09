| field | value |
| --- | --- |
| tile | Patching applications |
| id | patching-applications |
| parent | manager |


## Patching applications
- Tap the **Patcher** button in the bottom navigation bar.
- Tap the **Select an application** card.
- Here, you have the option to choose between selecting an app from on-device or selecting an APK file directly from storage.
   * For selecting on-device applications, tap on the desired app from the shown menu. For an app to show up in this list, the app must be already installed on the device.
     > **Warning**: This feature is incomplete for non-root users as ReVanced has yet to add split APK support. We suggest you pick your APK from storage for now.
   * To select from storage, click on the **Storage** button and select the APK normally through the file picker.
     > **Note**: We recommend downloading APK files from APKMirror as a temporary solution. `apkm` and `apks` files are not supported at the moment.
   * Verify that the selected application is a version supported by ReVanced. See the full list of supported versions of all apps [here](https://github.com/revanced/revanced-patches#-patches).
- After selecting an application, you will be brought back to the **Patcher** screen again. Tap the **Select patches** card.
- Select your desired patches. Note that certain patches are required for non-root installations. *(e.g. **MicroG Support** patch for YouTube)*
- Tap the **Done** button and the **Patch** button.
- The app is now patching. This process can range from 2-10 minutes depending on your device. Refrain from closing the Manager.
- When patching is complete, tap on the **Install** button. You may also tap on the three vertical dots in the top right to share logs or the patched APK.

   > **Warning**: If you close the Manager after patching, the patched APK file will be **automatically deleted from your device**!


### Managing patched applications
- Tap on the **Dashboard** tab in the bottom navigation bar
- Select the **Installed** chip
- You will see a list of all apps patched by the Manager. Tap on the **Info** button for the application you want to manage

Here, you will be greeted with buttons to open, uninstall, or repatch the application. You will also see information regarding the app, such as when it was patched, the type of installation, and the selected patches.

 > **Note**: Updating patched apps is currently removed and will be added back at a later date.
