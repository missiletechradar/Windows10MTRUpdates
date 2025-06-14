The files in the repository are files of the first update to be released for Windows 10 MTR.

Any future updates will be uploaded to the releases tab.

To change your MTR Settings language after you installed update MBFPEU250613.21H2 use the following command:

English: reg add "HKLM\SOFTWARE\MTR" /v UserLanguage /t REG_SZ /D en-US /f
Italian: reg add "HKLM\SOFTWARE\MTR" /v UserLanguage /t REG_SZ /D it-IT /f

If you want to make a custom language file, refer to the changelog for more information
