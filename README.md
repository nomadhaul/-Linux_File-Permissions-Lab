# -Linux_File-Permissions-Lab
File permissions in Linux
Project description
Updating file permissions for certain files and directories. This is a basic way of keeping the system secure.
Check file and directory details
Ls -al will list all files in the directory, even hidden ones.

 
Describe the permissions string
1st character marks whether it's a directory with “d” or a file with “-”.
2nd -4th should be either r,w,x for read, write, and execute respectively, for the permissions of the user.
5th-7th should be either r,w, or x for the group
8th-10th should be r,w,x for the other
Change file permissions
Chmod allows us to change permissions, o indicates others - I'm taking away a permission of w, which is write, followed by the location of the file I'm discussing, being project_k.txt
 
Change file permissions on a hidden file
This is more or less the same as changing a not hidden file, just ensure you can see the hidden file with ls -la, then do the same thing, making sure you have the “.”.
 
Change directory permissions
Exactly the same as a file, just instead of a file location it's a directory location
 
Summary
Multiple permissions were changed to adequately protect the system environment. After checking permissions, I was able to modify authorization to match company standards.

