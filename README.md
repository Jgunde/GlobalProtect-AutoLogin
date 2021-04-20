# GlobalProtect-AutoLogin
A Automator application for Macs that automatically logs in to the GlobalProtect client when ran.

1. Download the zip file and upzip it.
2. Open the "Automator" application on any Mac.
3. Select File->Open then select the "GlobalProtect Auto-Login" file that you just unzipped.
4. In the editor that opens
    - On line 11 change "your_username" to your account's username
    - On line 12 change "your_password" to your account's password
    WARNING: It is not reccomended to store a password in a file like this.
    If anyone finds out a way to store the password in Keychain and then use the password in this script, please do a pull request with the new code.
5. Save the application.

Now you can just place the application anywhere you want and double-click the icon to automatically get logged in to GlobalProtect!
