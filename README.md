# iphonebackupbrowser
Automatically exported from code.google.com/p/iphonebackupbrowser

# Browse the files of local iPhone/iPod backups.
# Description
This program shows the content of your iDevice backup.

No special access to the device is required, just non-encrypted backups made by iTunes 9.1.1 or 9.2 - 10.1.2 (as I write this), of course.

Select an app to show its files, or double-click it to open the .ipa archive in the Explorer.

You can drag a file to an editor, an image viewer, etc. Or double-click to show it in the Explorer. The filename consists in 40 hex digits and is not renamed (so, the default program associations will not work).

# 2010/06/27: support added for new backup files database
Last release of iTunes introduced a couple of new files: Manifest.mbdb and Manifest.mbdx. These files replace the old Manifest.plist and the plethora of files .mdinfo.

It's quite fun to see Apple abandon their property lists and XML for something completely propriatary.

See the wiki page for an explanation of the file formats.

# 2011/02/13: now fetchs some information from the .IPA archives
The directory of .ipa must be <User's Music>\iTunes\Mobile Applications (this is the standard place).

# Requirements
This project requires Microsoft Visual C++ 2010 Express and Visual C# 2010 Express (and certainly a recent version of Windows).

You have to install the following packages:

[Visual C++ 2010 Runtime](http://www.microsoft.com/en-us/download/details.aspx?id=5555)

[Microsoft .NET Framework 4 (Web Installer)](http://www.microsoft.com/en-us/download/details.aspx?id=17851) or [Microsoft .NET Framework 4 (Standalone Installer - 48.1 MB)](http://www.microsoft.com/en-us/download/details.aspx?id=17718)

WARNING For XP users: Please install [Microsoft Internationalized Domain Names (IDN) Mitigation APIs 1.1](http://www.microsoft.com/en-us/download/details.aspx?id=734) since BPLIST.DLL may use NormalizeString and IsNormalizedString new APIs. Or upgrade to Windows 7.

# Example
![Example](http://iphonebackupbrowser.googlecode.com/files/screenshot-iphonebackupbrowser.jpg)
