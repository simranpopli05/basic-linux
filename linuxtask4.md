 Q1. Create a directory named "MyFiles" in your home directory. Navigate into this directory and list its contents.
 
 ![4F7B9A6A-EA1D-45F0-9419-B77397D8DE6A](https://github.com/simranpopli05/basic-linux/assets/153719945/f8c5ed0b-f8ab-4875-91a6-feafff18be80)

Q2. Copy a file named "document.txt" from your home directory to the "MyFiles" directory. Move the file to a subdirectory named "Documents" within "MyFiles."

![13D77C4A-09BC-40D3-8603-1F1BEAEB8A3E](https://github.com/simranpopli05/basic-linux/assets/153719945/a8b7543d-15af-4dc9-ac1f-7da4f0ad5bdf)

Q3. Create an empty file named "notes.txt" in the "MyFiles" directory. Afterward, delete the file.

![A20B5A2E-CCBC-4B3D-806B-A606670F197C](https://github.com/simranpopli05/basic-linux/assets/153719945/5705b172-ad35-4d65-8d60-3bc9868f84c1)

Q4. Create a hard link named "hardlink.txt" for the file "document.txt" within the "Documents" subdirectory. Also, create a symbolic link named "symlink.txt" in the same location.

![76B65886-DF59-4A59-A115-AB0699CC9E85](https://github.com/simranpopli05/basic-linux/assets/153719945/ceb9efa6-c7fe-4ed2-bd8f-438afd6b6ce9)

Q5. In the "MyFiles" directory, use a single command to list all files that start with the letter "a" and have a ".txt" extension.

![CE5CF99A-69F5-4255-8E67-4EF218D49CB1](https://github.com/simranpopli05/basic-linux/assets/153719945/08fe996a-9e25-44d4-b000-b90a116f128b)

 Q6. Rename all files in the "Documents" subdirectory of "MyFiles" with a ".bak" extension. Ensure the original file names are preserved.

 ![E4DD415F-2E83-46A5-85F2-BA7A9A747D98](https://github.com/simranpopli05/basic-linux/assets/153719945/532b0811-6fed-44e9-9bf5-99c11e1cade1)


 Q7. Use a wildcard character to copy all files from the "Documents" subdirectory of "MyFiles" to another directory named "Backup."

 ![414201CA-42DD-4309-BCBD-94EBDFD02086](https://github.com/simranpopli05/basic-linux/assets/153719945/9af28285-df51-417c-a80d-064f2dc0c0b0)


 Q8. Execute the ls command to list files in the current directory. Save the output to a file named "file_list.txt." Then, use a pipe to filter the output through grep to display only files with a ".txt" extension.

 ![FE8741D3-3BF3-411F-ADD9-39BAC2ED3186](https://github.com/simranpopli05/basic-linux/assets/153719945/a1b44c85-d6ec-48cb-9ed0-db54babf9ccc)


 new text file named "my_notes.txt" using the touch command. Open the file in the Vim editor, add some text, and save the changes.

 Q10. Run the date command and store the output in a variable named "current_date." Display the value of the variable and append it to the "my_notes.txt" file.

 ![D237BF6E-F376-4D35-A058-3EA5FC760A14](https://github.com/simranpopli05/basic-linux/assets/153719945/1b8a6d2c-3377-493c-93af-af687205db20)


 Q11. Edit the Bash startup script (e.g., .bashrc) to set an environment variable named "CUSTOM_PATH" to a specific directory path. Ensure the variable is available in new shell sessions.

 ![0EB06CD9-E2D4-4CD2-978A-C4224D90FAAF](https://github.com/simranpopli05/basic-linux/assets/153719945/3ca62851-575d-40ec-8e82-2aa4dd3f2670)


 Q12. Use the echo command to add a new line of text to the "my_notes.txt" file without overwriting existing content. Verify that the new text is appended.
 

 ![0EB06CD9-E2D4-4CD2-978A-C4224D90FAAF](https://github.com/simranpopli05/basic-linux/assets/153719945/3ca62851-575d-40ec-8e82-2aa4dd3f2670)


Q13. List all files in the "/etc" directory, filter the output to include only those containing the word "conf," and save the result to a file named "conf_files.txt."

![588C5AFF-4D4B-4DC7-AE5B-47176705C010](https://github.com/simranpopli05/basic-linux/assets/153719945/34579e8d-9bb1-4b3e-961d-c6a6f12d2be5)


Q14. Open the "my_notes.txt" file in Vim. Use Vim's search and replace functionality to replace all occurrences of the word "important" with "critical." Save the changes.

![image](https://github.com/simranpopli05/basic-linux/assets/153719945/79a9632e-6e2a-4ac4-90ed-a0e4af75b3fb)


Q15.Create a new user account named "john_doe." Set the user's home directory to "/home/john_doe" and assign the user to the "users" group.

![image](https://github.com/simranpopli05/basic-linux/assets/153719945/e8e6f412-c50a-482e-a575-f3af0037eab9)


Q16. Add the user "john_doe" to the sudoers file, allowing them superuser privileges. Confirm that "john_doe" can execute commands with sudo.

Q17. Modify the user account "john_doe" to change the default shell to "/bin/bash" and set the account's expiration date to one month from today.

 ![image](https://github.com/simranpopli05/basic-linux/assets/153719945/d75d656a-784f-4d62-b818-0907769282a2)


Q18. Create a new group named "development_team." Add "john_doe" to this group and verify the group's existence.

![image](https://github.com/simranpopli05/basic-linux/assets/153719945/ec2a6353-8d4f-47f8-b279-d6627303fa0e)


Q19. Remove "john_doe" from the "users" group and add them to the "development_team" group. Confirm the changes.

  ![image](https://github.com/simranpopli05/basic-linux/assets/153719945/f9bf0179-6626-4443-bcbc-6fca2b432f07)


Q20. Delete the user account "john_doe" and ensure that their home directory is also removed

![image](https://github.com/simranpopli05/basic-linux/assets/153719945/16059840-e948-44fe-b0af-3931d9d4fe33)


Q21. Delete the group "development_team" and ensure that all users previously belonging to the group are appropriately handled.

![image](https://github.com/simranpopli05/basic-linux/assets/153719945/ef416edb-f6dd-4558-9c2d-96f148d34fbb)


Q22. Implement a password policy that requires users to change their passwords every 90 days. Apply this policy to all existing and new user accounts.

![image](https://github.com/simranpopli05/basic-linux/assets/153719945/da1b6874-11eb-4065-99ab-114f26eedf4b)


Q23. Manually lock the user account "john_doe." Attempt to log in as "john_doe" to confirm that the account is locked. Then, unlock the account.

Q24. Use the id command to display detailed information about the "john_doe" user, including user ID, group ID, and supplementary groups.

Q25. Configure the password aging for the user "john_doe" to enforce a maximum password age of 60 days. Confirm that the changes take effect.





