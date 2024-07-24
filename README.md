# Upgrade Java from 11 to 17 manually
In this demonstration I will upgrade Java (which was installed on Rocky Linux) from Java-11 to Java-17 manually.

In below screenshot a Linux machine with Rocky Linux with Java-11 installed is shown below.
![image](https://github.com/user-attachments/assets/fad87770-cbd1-4efb-848b-aef0fe19a633)
![image](https://github.com/user-attachments/assets/e70a0da7-17a0-466e-8e3f-881fa7f86a7b)
![image](https://github.com/user-attachments/assets/c76c8f65-0d6e-49ed-a369-683b4023f07b)

Download tar file for java-17 and unarchive it.
![image](https://github.com/user-attachments/assets/275f26d9-4847-44a0-aae8-f3b4f1654f52)
![image](https://github.com/user-attachments/assets/8fa56cf0-498d-45c8-ad9a-676f79131d68)

Change JAVA_HOME and PATH in /etc/profile file as shown in screenshot below.
![image](https://github.com/user-attachments/assets/509c6ffa-1db6-4e29-8c41-4c4838f45bfe)
![image](https://github.com/user-attachments/assets/d9c8d4bd-8b60-44de-bb60-dc5c78f89e48)

Now check PATH, JAVA_HOME and java -version as shown in the screenshot below.
![image](https://github.com/user-attachments/assets/d1b88b1b-e360-4d2d-8e30-d46e318fb955)

You can see the java version is not changed and remain java-11. To select the java version as java-17 follow the below steps.
![image](https://github.com/user-attachments/assets/d0a467fc-e49a-43c6-b053-dac7c496ee51)

You can cross verify this, the select java version is java-17 using the command shown below.
![image](https://github.com/user-attachments/assets/625b199f-0d00-491d-8ee4-c45a061d8f4b)
