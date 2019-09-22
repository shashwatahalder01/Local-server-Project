1.General information This section explains in general terms the system and the purpose for which it is intended.

1.1 System Overview

Rklul47 FTP Server is an application which allows users to store their valuable information (files) on to a server. The graphical user interface of the application allows users to upload and download their files in a secure way. Moreover, it allows users to update their files in the server too. The application stores the data to a local disk folder(server).

1.2 System configuration

Rklul47 FTP Server operates on JDK platform with a java supporting IDE. It is compatible with platforms like windows, linux, mac etc. with the help of JVM. The application is build up on features of java like java swing (panel, label, button, password field, radio button, combo box), java classes (BufferedReader, File, FileReader, JFileChooser, nio files), Java logging API etc. to make the program more robust and dynamic.

1.3 System authors

The Rklul47 FTP server has been created by Tanjilul Anwar, Rajkumar Shashwata Halder in the purpose of a project in Computer Network course . The system authors tried to provide a fastest, efficient and reliable FTP server for the user which is also very user friendly.

Getting Started
This section explains how to get Rklul47 and install it on the device.

2.1. Installation and creating server

The application is a .java file, which should be installed on the device. This application requires a local drive (E:) and a folder named “server” with a .txt file named “account.txt” in the drive. User should create the required “server” named folder on the drive and a “account.txt” file in the server folder.

2.2. Customizing server location

If the user unable to provide a local drive (E:), he/she might have to customize the server location. First open the application with a java supported IDE and navigate to NewJFrame3.java > public void submission () > find the line” File file = new File("E:"+File.separator + "server"+File.separator +"account.txt");” . Replace the “E:” driver letter with the desired driver letter in which he/she want to create the server.

2.3. Sign up and logging in After running the application the user will have a window for log in into the server with an existing account or create a new one.

“Existing User” button takes the user to a login window asking for user ID and password.

As for the first time the user has to click the “New user “button to navigate to the Register window to complete the sign-up process.

Every field of the register window must be filled to complete a successful registration. After pressing the “submit” button providing proper information the application will allocate a new account for the user to access the server as well as open the sever access window.

2.4. Accessing the server

After a successful login the user will have the server access widow for further operation. First the user has click the “Connect” button to create a session between the server and the user. After that to upload a file onto the server the user has to click the “Upload” button to open file chooser to navigate the desired file location and select the file to upload.

As for the download operation the user simply has to choose the desired file from the server and then click “Download” and also have to select the save location to download the file.

“Update” and “Delete” button offers the user to alter a file in the server. Update operation allows the user to upload a file with a message “do you wish to keep the older file” and a choice of yes (for keeping the new file with a rename option) or no (for replacing the old file with the new one) to upload a file onto the server.

Delete operation simply offers the user to delete a file from the server.

2.4. Exit Server

“Log out” button allows the user to exit from the server after the completion of their desired operation.
