title Windows 10 Pro - Permanent Activator Developed by @ios_euphoria @mrcreator1 @pwn2owned
color a
cls
@echo off
echo Loading patch...
TIMEOUT /T 3
echo Removing any potential product keys...
cscript slmgr.vbs /upk
echo Keys Removed!
TIMEOUT /T 3
echo Installing Windows 10 Pro Activation Key...
cscript slmgr.vbs /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX
echo Key Inserted!
TIMEOUT /T 3
echo Turning Key...
echo Fiddling around with lock activation server...
cscript slmgr.vbs /skms kms8.msguides.com
echo PATCHED! New activation server patched!
TIMEOUT /T 3
cscript slmgr.vbs /ato
color b
echo UNLOCKED! Your device is now activated successfully.
echo .
