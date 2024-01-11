Create an Executable Virus
======================
In this activity, you will create an executable file of the virus.


<img src= "https://s3-whjr-curriculum-uploads.whjr.online/ff9cbbd3-e216-4d5a-b64a-b35695fa8461.gif" width = "100%" height = "50%">


Follow the given steps to complete this activity.


1. Install the python library `PyInstaller` in case of Windows OS from the command prompt.
   ```
   pip install pyinstaller
   ```
2. Navigate to the directory in which the python file exists and run the command to convert it into an executable file.
   
   * Windows:
    ```
    pyinstaller --onefile windows.py
    ```


    * MAC/Linux:
    ```
    chmod +x mac.command
    ```
    or
    ```
    sudo chmod +x mac.command
    ```
3. Double click or run the executable virus file to create a text file.


Check content of the other files in the folder to check if they are encrypted by the virus.
