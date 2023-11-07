# Keylogger

The purpose of this lab is to gain a tactile understanding of what a keylogger is and the ways it can be configured for efficient and effective usage. At its core, the biggest take away from this lab is to understand how software like keyloggers are able to record typed keystrokes and why it can be considered a dangerous tool -especially when used as spyware. Below is a list on ways to go about configuring, setting up, and studying the logger for educational purposes.

As stated, all of the information provided is intended for educational purposes with no malicious intents. Special thanks goes to Josh Madakor for creating this lab and code.   

**1. Download and Install Visual Studio Community:**

- Download Visual Studio Community for free and install it.
- During installation, select ".NET Desktop Environment."

**2. Download Keylogger Source Code:**
- Go to: [Keylogger w/ email](https://github.com/Larbi3/Keylogger/tree/main/Key-Logger-With-Email)
- Extract the downloaded ZIP file to a folder on your desktop.

**3. Open and Modify the Code:**
- Inside the extracted folder, open the program.cs file.
- Modify the following variables in the code:
    - From_Email_Address: Enter the email address you want to send the logs from.
    - From_Email_Password: Enter the password for the sender's email address.
    - To_Email_Addresses: Enter the recipient's email address where you want to receive the logs (this can be the same email as the sender).
    - Log_File_Name: Specify the location and name of the log file on the disk.

**4. Configure Gmail:**
- Enable "Less Secure Apps" in your Gmail account settings. This allows the C# application to send emails on your behalf.
- To do this, search for "Gmail Turn On Less Secure Apps" and follow the instructions to enable it.

**5. Build and Run the Keylogger:**
- In Visual Studio, click the green "Start" button to build and run the keylogger.
- Test the keylogger by typing on the keyboard; the keystrokes should be logged.

**6. Hide the Console Window (Optional):**

- To run the keylogger without displaying the console window, change the output type to "Windows Application":
- Right-click on the project, go to "Properties."
- Under "Application," change the "Output Type" to "Windows Application."
- Rebuild the project and run it again through clean solution under the build tab. 

**7. Distribute the Executable (Optional):**

- To deploy the keylogger on another computer, navigate to the project's debug folder.
- Find the generated executable file (.exe) and copy it to the target computer.
- Optionally, use Task Scheduler to set the keylogger to run on system startup.

**8. Test Against Anti-Malware Engines (Optional):**
- Use websites like VirusTotal to check if the keylogger is detected by anti-malware engines.
- Upload the executable to VirusTotal to see if it's flagged as potentially malicious.
