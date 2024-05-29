# Windows-Registry-Tweaks
This Repository demonstrates how you can make Windows better through Registry Editor. 
⚠️Note! This is intended for users who are more over advanced in the use of Windows and know the mechanics of Microsoft Windows

**Not providing any files apart from Registry Keys. Below is some you can use for Windows 8 - 11!

## Settings that are also Registry
Even though most of these following hacks can be done through Windows Settings, here is how to do it anyways!

### **1. Disable Aero Shake**

   ![Screenshot of Search](https://github.com/jerfer1111/Windows-Registry-Tweaks/blob/main/disable_aero_shake_attached_screenshots/Disable%20Aero%20Shake%20Picture%201.png?raw=true)
   
   The Aero Shake feature allows you to minimise the other windows by shaking nearby it. You may not have realised you even had such feature, but even if you knew, you might not want it. This is removeable through the Windows System Settings for Windows 11 but for any previous versions of Windows (10 and before) this is how to remove this feature.

   1. Open the Registry Editor:
     ![Screenshot of Search](disable_aero_shake_attached_screenshots/registry_editor_search.png)

**Step 1**: Navigate to the following path:
	***Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced***

 ![Screenshot of Search](https://github.com/jerfer1111/Windows-Registry-Tweaks/blob/main/disable_aero_shake_attached_screenshots/Disable%20Aero%20Shake%20Picture%202.png?raw=true)

 **Step 2** Right-click an empty space in the right side pane, select **New > DWORD (32-bit),** then name it **DisallowShaking**

 ![Screenshot of Search](https://github.com/jerfer1111/Windows-Registry-Tweaks/blob/main/disable_aero_shake_attached_screenshots/Disable%20Aero%20Shake%20Video%204.gif?raw=true)

 Double click the entry you just created, then change the Value Data to **1** and click **OK**
