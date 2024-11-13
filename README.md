# HFVR
A relative small tools to help recover from hidden files virus and regain ownership.

Features:

- Change all files and folders ownership is directory to the admin
- Change attribute for all files and folders to unhide
- Using elevated permissions, bypass any system blockage that disallow admin from making change on folders/file attribute

# FAQ
Does this delete any files?
- No

What procesed is used?
- HFVR simply create a batch file (CMD) and run it on your selected directory. This batch file is automatically removed after cleanup process.

How long the process would take?
- Relative to directory size, however mostly less than a second.

IT FLAGGED AS VIRUS IN VIRUSTOTAL?
- The only flag is from MaxSecure which is known as bogus and shady vendor. Even their own website use expired certificates.

HFVR changelog

******************************************************************

Version 0.1 

Program started with size 204KB
******************************************************************
Version 0.2

Program size reduced to 200KB

Code tweaking to improve effectiveness.

Add a line to automatically delete generated batch file after recovery process. 

Simplifying GUI for easier interaction.

******************************************************************

Version 0.3

Program size reduced to 191KB

Source code clean up, removing unused code.

Remove about us form in order to reduce sizes.

Add a pop up message to replace about us form.

Fixing random error that cause "Files or Folder not found" displayed during cleaning process.
