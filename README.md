# Pentaho Installation

Follow these steps to successfully install Pentaho Data Integration :

1. Download Pentaho Data Integration (1.1GB) at this site:  https://drive.google.com/drive/folders/1RSoNk5Z8W8wrFMZLjYaY9m_8PHaIA_v0?usp=sharing
2. Extract pdi-ce-9.4.0.0-343.zip
3. Create folder Pentaho at C:/Program Files.
4. Copy folder data-integration from the unzip   pdi-ce-9.4.0.0-343.zip.
5. Download the latest jre for windows 64-bit : https://download.cnet.com/Java-Runtime-Environment-JRE-64-Bit/3000-2213_4-75317067.html
6. Double click the  downloaded jre.
7. Click change destination folder.
8. If the destination folder is at C:\Program Files\Java\jre1.8.0_251, click Next.
9. In your window search box, type: environment variables.
10. Click Edit the system environment variables.
11. Click Environment variables.
12. Click New under Systems variables.
13. In the text box of variable name type: PENTAHO_JAVA_HOME
14. In the variable value type: C:\Program Files\Java\jre1.8.0_251
15. Download the DB2 Driver.  Refer to the link to this link:  https://drive.google.com/file/d/1he1_YUd7R6ymkTmyKDnAglMdxnmJJlbZ/view?usp=sharing
16. Copy the db2jcc.jar file to C:\Program Files\Pentaho\pdi-ce-9.4.0.0-343\data-integration\lib
17. Navigate C:\Program Files\Pentaho.
18. Right click  spoon.bat | Run administrator.
19. You should have the following desktop :

![image](https://github.com/Reirinn/Pentaho_Lab2/assets/142465054/37511a40-01b4-4aea-a994-5542f053f08f)


