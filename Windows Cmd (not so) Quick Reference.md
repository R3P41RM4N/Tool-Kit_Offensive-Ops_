## The following is a sample of command line commands for Windows Machines pulled from  https://www.ionos.com/digitalguide/server/know-how/windows-cmd-commands/. For additional, indepth explainations of different windows commands I suggest looking at https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/windows-commands

## CMD commands for the Windows command prompt

| CMD command | Description | Windows version|
| --- | --- | --- |
| bitsadmin | Creates and monitors downloads and uploads. | 10/8/7/Vista |
| break | Interrupts Ctrl + C checking in DOS, allowing you to stop processes in the old operating system. Only available for compatibility reasons in Windows.	All Win/DOS
| call | Calls a batch file within another batch file. The command has no effect if entered directly into CMD instead of in a batch file. | All Win/DOS	 
|cd | Displays the current directory and lets you switch to other directories. With the parameter /D plus drive and path specification, you can also switch drives. Use cd.. to switch to a higher directory (has the same function as the chdir command). | All Win/DOS	|
|chcp | Changes the current code page (character set table) or shows the page count of the current code page. | All Win/DOS |
chdir	Displays the current directory and lets you switch to other directories. With the parameter /D plus drive and path specification, you can also switch drives. Use chdir.. to switch to a higher directory (has the same function as the cd command).	All Win/DOS	 
choice	Creates a selection list: typical example is the selection of yes (Y) or no (N), which is created with /C YN. With the parameter /M you can add an explanatory message for the user.	All Win (not XP)/DOS	 
clip	Forwards the result of a command to the clipboard. For example, you can copy the directory structure (dir	clip) or the content of a file (clip < filename) to the clipboard.	10/8/7/Vista
cls	Clears the content of the screen.	All Win/DOS	 
cmd	Starts CMD.EXE.	10/8/7/Vista/XP	 
color	Changes the background (first value) and text color (second value) of the command prompt. The color lies between 0 (black) and F (white).	10/8/7/Vista/XP	 
command	Starts CMD.COM.	32-bit/DOS	 
date	Displays the current date and allows you to change it. With the parameter /T the date is shown without the option to change.	All Win/DOS	 
debug	Starts debug, a program that can test and modify programs within the command prompt.	32-bit/DOS	 
dir	Displays all folders and files within the current directory. You can restrict the output by attributes (/A), simplify the list (/B), or display all subdirectories and their files (/S).	All Win/DOS	 
doskey	Creates macros, recalls commands, and edits command input.	All Win/DOS	 
dosshell	Opens the DOS shell, a graphical file management tool. In Windows, the DOS shell is replaced by Windows Explorer.	95/DOS	 
echo	Displays a message and is mainly used within scripts and batch files.	All Win/DOS	 
edit	Starts the MS-DOS editor, with which you can create text files.	32-bit/DOS	 
edlin	Creates and edits text files within the command prompt.	32-bit/DOS	 
exit	Ends CMD.EXE or CMD.COM.	All Win/DOS	 
fasthelp	Displays helpful information about commands.	DOS	 
fastopen	Writes the position of a program into a specified list, which is in the working memory and should accelerate the start of programs.	32-bit/DOS	 
find	Searches through a file or multiple files for a particular character sequence. If you only want to know how frequently the word or phrase occurs, use the /C parameter. With the extension /I the command ignores upper- and lower-case in the search.	All Win/DOS	 
findstr	Finds character sequences in one or multiple files. It gives you more options when compared to the find command: you can search for files that contain various terms or with /C search for an exact word order.	10/8/7/Vista/XP	 
forcedos	Starts a program in the MS-DOS partial system, in case it’s not directly recognized by Windows XP as a DOS program.	XP (32-bit)	 
graftabl	Enables the option to use extended characters of a specific code page in graphics mode.	32-bit/DOS	 
graphics	Starts a program that can print graphics.	32-bit/DOS	 
help	Displays help text for a specific command (you can also use the /? command).	All Win/DOS	 
kb16	Changes the country settings of the keyboard for DOS programs (only included in Windows for compatibility reasons. Replaces the old command keyb).	32-bit	 
keyb	Changes the country settings of the keyboard for DOS programs (only included in Windows for compatibility reasons. Replaced by kb16 in newer Windows versions).	98/95/DOS	 
logoff	Logs the user out of Windows. Also allows you to end sessions on servers.	10/8/7/Vista/XP	 
lpq	Displays the status of a printer queue for computers that use a “line Printer Daemon” (LPD). (To use the command in Windows 10, 8, 7, or Vista, the LPD print service and the LPR port monitor have to be enabled first).	All Win	 
lpr	Sends a file to a computer that uses a line printer daemon (LPD). To use the command in Windows 10, 8, 7, or Vista, the LPD print service and LPR port monitor have to be enabled first.	All Win	 
md	Creates a new directory on the specified path. If directories don’t already exist on the path, md creates them automatically (you can also use the mkdir command).	All Win/DOS	 
mkdir	Creates a new directory on the specified path. If directories don’t already exist on the path, mkdir creates them automatically (you can also use the md command).	All Win/DOS	 
more	Outputs the content of a file (for example, a text file) by the page. You can also use the command to split the output of another command into pages.	All Win/DOS	 
msg	Sends a message to another user. You can write the username into the command or create files in which usernames are saved. The files can then be included in the command with @filename.	10/8/7/Vista/XP	 
nlsfunc	Provides country-specific information for language support.	32-bit/DOS	 
ntbackup	Runs backup services directly from the command line or as part of batch or script files.	XP	 
path	Creates and displays the path for searching executable files.	All Win/DOS	 
pause	Pauses execution in batch files and scripts. The user is then prompted in a message to continue by pressing a key.	All Win/DOS	 
popd	Changes to the folder saved by the pushd command. The command is mainly part of batch files and scripts.	10/8/7/Vista	 
print	Prints a text file. The device to be used for printing has to be specified.	All Win/DOS	 
prompt	Changes the display of the command prompt.	All Win/DOS	 
pushd	Saves a specific path into a script or batch file. You can change to this directory with popd.	10/8/7/Vista/XP	 
qbasic	Starts qbasic, a program environment based on the BASIC programming language.	98/95/DOS	 
rd	Deletes a directory. This must not contain any files, even hidden ones. You can delete an entire directory tree with the /S parameter (you can also use the rmdir command).	All Win/DOS	 
rem	Writes comments in batch and script files that aren’t taken into account when executing.	All Win/DOS	 
rmdir	Deletes a directory. This must not contain any files, even hidden ones. You can delete an entire directory tree with the /S parameter (you can also use the rd command).	All Win/DOS	 
runas	Allows a user to run commands with the rights of another user. For example, you can run a command as an administrator from a normal user account as long as you know the password.	10/8/7/Vista/XP	 
scandisk	Starts Microsoft ScanDisk. The program searches data carriers for errors.	98/95/DOS	 
schtasks	Sets the execution of specified programs and commands for a specified point in time. You can create, delete, change, and display all scheduled tasks.	10/8/7/Vista/XP	 
set	Displays environmental variables of CMD.EXE and lets you configure them.	All Win/DOS	 
shift	Moves variables within batch files and scripts.	All Win/DOS	 
shutdown	Shuts down the computer (/s), triggers a restart (/r), or logs the user out (/l). A graphical user interface is displayed if you enter the parameter /I as the first option in the command.	10/8/7/Vista/XP	 
sort	Lists out data (from a file or command) and outputs it again sorted – directly in the command prompt, in a new file, or in another output.	All Win/DOS	 
start	Opens a new command prompt window in which you can run a specific program or command.	All Win	 
subst	Assigns a drive letter to a path to create a virtual drive.	All Win/DOS	 
taskkill	Ends one or more running tasks. You either have to specify the process ID (PID) or image name.	10/8/7/Vista	 
tasklist	Lists all running processes – also on remote computers, if desired. The process ID also has to be specified, which is required for the taskkill command, for example.	10/8/7/Vista/XP	 
time	Displays the current time and allows it to be changed. If the parameter /T is entered, the command prompt only shows the time and offers no option to directly change it.	All Win/DOS	 
timeout	Stops a process for a specified time. The command Is used in batch files and scripts. If you use the /NOBREAK parameter, the command ignores any keyboard input.	10/8/7/Vista	 
title	Changes the title of the command prompt. Spaces are allowed, but not all special characters such as a slash, for example, because they may be interpreted as instructions for a parameter.	All Win/DOS	 
tree	Graphically displays the directory structure of a drive or path. With the /F parameter, all files in the folders are also listed out. /A also ensures that only ASCII characters are used for the graphical representation. The command takes into account all subdirectories starting from the given path. If you don’t enter a path, the current folder is used as the output.	All Win/DOS	 
type	Displays the content of a text file.	All Win/DOS	 
tzutil	Displays the currently set time zone (/g) or changes it (/s). The parameter /l helps determine the valid time zones.	10/8/7	 
ver	Displays the current version number of Windows or MS-DOS.	All Win/DOS	 
Files
CMD command	Description	Windows version
append	Sets the path in which files will be searched for.	32-bit/DOS
assoc	Changes the program that’s linked with a particular file ending.	10/8/7/Vista/XP
attrib	Changes attributes of specified files. With the parameter +R you can protect a file from changes.	All Win/DOS
cipher	Displays and changes the encryption status of files and directories on NTFS partitions.	10/8/7/Vista/XP
comp	Compares the content of two files or two file sets. The results can be displayed as a decimal value (/D) or with ASCII characters (/A).	10/8/7/Vista/XP
compact	Displays and changes the compression status of files and directories on NTFS partitions.	10/8/7/Vista/XP
copy	Copies a file or multiple files to another location. It’s also possible to connect several files to one. You can use the asterisk as a wild card.	All Win/DOS
cscript	Runs scripts over the Microsoft Script Host. You can enable additional debugging with the /D option.	All Win/DOS
del	Deletes a file or multiple files. If you also want to delete all files from subfolders, you can do this with the /S parameter. Read-only files can be deleted with /F (you can also use the erase command).	All Win/DOS
deltree	Deletes a directory as well as all subdirectories and files within.	98/95/DOS
diantz	Compresses files without any loss (command has the same function as makecab).	7/Vista/XP
diskcomp	Compares the content of two disks.	All Win (not 10)/DOS
diskcopy	Copies the content of a disk to another.	All Win (not 10)/DOS
endlocal	Ends the valid range of changes to batch files or scripts. After the command, changes are applied to the entire system again (localization is started with setlocal).	10/8/7/Vista/XP
erase	Function is the same as del.	All Win/DOS
exe2bin	Converts an EXE file to a BIN file.	32-bit
expand	Extracts files and folders stored in CAB files.	All Win (not 64-bit XP)/DOS
extrac32	Extracts files and folders stored in CAB files. The program is part of Internet Explorer, but can also be used in the command prompt.	All Win
extract	Extracts files and folders stored in CAB files (in new Windows versions use expand).	98/95
fc	Compares two individual files or two sets of files with one another and displays the differences.	All Win/DOS
for	Sets a specific command that should be run for each individual file in a file set. This command is usually used in batch and script files.	All Win/DOS
forfiles	Selects one or more files and runs a command that refers to these files. Usually used for batch and script files.	10/8/7/Vista
ftype	Specifies a program for opening a specific file type.	10/8/7/Vista/XP
goto	Skips the execution within a batch program to a specific line (marker).	All Win/DOS
if	Represents a conditional statement and executes expressions within batch files only under certain conditions. Can be extended by not if commands are only not to be executed under certain conditions.	All Win/DOS
makecab	Compresses files without loss in CAB format (you can also use the diantz command).	10/8/7/Vista/XP
mklink	Creates a symbolic link to a file. With /D you can also create connections to directories. Create a fixed connection instead of a symbolic connection with /H.	10/8/7/Vista
move	Moves a file or multiple files from one directory to another. The command can also change the names of directories. By default, the command overwrites other files with the same name when moving files to the destination. To prevent this use the /-Y parameter.	All Win/DOS
openfiles	Displays and separates open system files and folders.	10/8/7/Vista/XP
recover	Restores readable files that were on a defective data drive.	10/8/7/Vista/XP
ren	Changes the name of a particular file. Directory and drive cannot be changed this way (or use the rename command).	All Win/DOS
rename	Function is the same as ren.	All Win/DOS
replace	Replaces the selected file or files with one or more other files. With /S files in subfolders are also replaced. With the addition /U files are only replaced if another version is more current. The parameter /A allows users to add new files to the target directory at the same time. This parameter is not compatible with /S and /U.	All Win/DOS
robocopy	Allows so-called robust file copying. This is an extended version of copy and xcopy. With robocopy it’s possible to successfully transfer data even if there are interruptions in the network. There are a total of 72 parameters with which the copy command can be modified.	10/8/7/Vista
rsm	Manages media on removable storage devices. Is used in batch files and scripts to support programs that don’t use “Removable Storage API.”	Vista/XP
setlocal	Limits the valid range of changes to batch files or scripts. After the command, changes only apply to these files (localization is started with endlocal).	10/8/7/Vista/XP
share	Installs file sharing and file locking.	32-bit/DOS
sxstrace	Starts the WinSxs Tracing Utility, a tool for programming diagnostics.	10/8/7/Vista
takeown	Restores administrator access rights to a file that have been lost when reassigning a user.	10/8/7/Vista
undelete	Undoes the deletion of a file.	DOS
verify	When enabled, checks whether files are written correctly on a data drive. The check is disabled in the standard settings.	All Win/DOS
where	Finds files that match a particular search topic. The placeholders * and ? can be used within the topic.	10/8/7/Vista
xcopy	Copies files and entire directory structures. In this way, the command offers various additional options. For example, it can be specified that only files younger than a specific date (/D) should be copied. It can also be specified that read-only files are overwritten (/R).	All Win/DOS
System
CMD command	Description	Windows version
at	Starts commands and programs at a particular time. With the parameter /every:date[,…] you can also set regular appointments.	10/8/7/Vista/XP
auditpol	Displays current monitoring policies.	10/8/7/Vista
backup	Creates backups of files. These can be recovered with restore (replaced by msbackup).	DOS
bcdboot	Creates and repairs start files.	10/8/7
bcdedit	Allows users to make changes to start configuration data storage (the command is a new version of bootcfq).	10/8/7/Vista
bdehdcfg	Prepares a hard drive for BitLocker Drive Encryption.	10/8/7
bootcfg	Creates, edits, or displays the content of boot.ini (although it’s still included in the Windows 7 CMD, it has lost its function since boot.ini is no longer used for startup options, instead you should use bcdedit).	10/8/7/Vista/XP
bootsect	Modifies the master boot code sot that it’s compatible with the Windows Boot Manager or NT Loader (can only be started via system restore in Windows 7 and Vista).	10/8/7/Vista
cacls	Edits and displays the access control list. This sets access rights (outdated – replaced by icacls in newer Windows versions).	10/8/7/Vista/XP
chkdsk	Checks and repairs (with the parameter /R) a data drive.	All Win/DOS
chkntfs	Changes or displays the data driver check at startup.	10/8/7/Vista/XP
cmdkey	Can display (/list), create (/add), or delete (/delete) login information.	10/8/7/Vista
convert	Converts partitions from FAT/FAT32 to NTFS.	10/8/7/Vista/XP
ctty	Changes the standard input and output for the system.	98/95/DOS
dblspace	Creates or configures compresses drives (a newer version of the command is called drvspace)	.98/95/DOS
defrag	Defragments all or only specified drives. Use /U to observe the progress. To get an evaluation statistic after the defragmentation, use the parameter /V.	All Win/DOS
diskpart	Manages, creates, and deletes partitions from the hard drive.	10/8/7/Vista/XP
diskperf	Allows users to remotely control the disk performance counter.	10/8/7/Vista
diskraid	Manages RAID systems.	10/8/7/Vista
dism	Manages and integrates Windows images.	10/8/7
dispdiag	Creates a file in the current directory in which you’ll find information about your display.	10/8/7/Vista
dosx	Starts the DOS Protected Mode Interface, which allows MS-DOS programs more than 640 KB of RAM. Is only available to support older DOS programs.	32-Bit
driverquery	Creates a list with all installed drivers.	10/8/7/Vista/XP
drvspace	Creates or configures compressed drives. An older version of the command is called dblspace.	98/95/DOS
emm386	Provides DOS with more than 640 KB of RAM.	98/95/DOS
esentutl	Manages databases within the extensible storage engine.	10/8/7/Vista/XP
eventcreate	Creates an entry (ID and message) in an event log.	10/8/7/Vista/XP
eventtriggers	Configures and displays event trigger.	XP
fdisk	Creates, deletes, and manages partitions on the hard drive. Use diskpart in newer Windows versions.	98/95/DOS
fltmc	Allows users to manage and display filter drivers.	10/8/7/Vista/XP
fondue	Installs additional Windows features. The command is an abbreviation for the underlying tool: Features on Demand User Experience Tool.	10/8
format	Formats a drive to the file system specified by the user.	All Win/DOS
fsutil	Provides numerous features related to the file system, such as disk removal.	10/8/7/Vista/XP
hwrcomp	Compiles self-created dictionaries for handwriting recognition.	10/8/7
hwrreg	Installs a compiled dictionary for handwriting recognition.	10/8/7
icacls	Edits and displays the access control list. This sets access rights. An outdated version of this command is cacls.	10/8/7/Vista
ktmutil	Starts the kernel transaction manager.	10/8/7/Vista
label	Changes or deletes a drive’s label.	All Win/DOS
lh	Loads a program into the high memory area (UMB) – has the same function as loadhigh.	98/95/DOS
licensingdiag	Creates an XML and a CAB file that contain information on the Windows product license.	10/8
loadfix	Ensures that a program is loaded and executed above the first 64 KB of RAM.	32-bit/DOS
loadhigh	Has the same function as lh.	98/95/DOS
lock	Locks a drive so that only a user-selected program can access it directly.	98/95
lodctr	Updates all registry entries that have to do with performance indicators.	All Win
logman	Creates and manages event trace sessions and performance logs.	10/8/7/Vista/XP
manage-bde	Configures drive encryption with BitLocker. Use -on to encrypt a drive. Use -off to decrypt it again and end BitLocker protection.	10/8/7
mem	Displays information about the RAM and indicates which programs are currently loaded in it.	32-bit/DOS
memmaker	Optimizes the RAM.	98/95/DOS
mode	Configures system devices – primarily on the COM or LPT port.	All Win/DOS
mofcomp	Analyzes files in managed object format (MOF) and adds the classes and instances to the WMI repository.	All Win
mountvol	Creates and deletes mount points for drives and displays them.	10/8/7/Vista/XP
msav	Starts Microsoft Antivirus.	DOS
msbackup	Starts Microsoft Backup (replaces backup and restores).	DOS
mscdex	Loads the CD-ROM support for MS-DOS.	98/95/DOS
msd	Starts the program Microsoft Diagnostics, with which system information can be displayed.	DOS
msiexec	Starts the Windows installer, with which Windows can be installed and configured.	10/8/7/Vista/XP
muiunattend	Starts an automatic setup process for the multilingual user interface (MUI).	10/8/7/Vista
netcfg	Installs the minimal operating system Microsoft Windows PE.	10/8/7/Vista
ocsetup	Installs additional Windows functions.	8/7/Vista
pentnt	Recognizes floating point division errors in Pentium chips, starts floating point emulation, and disables floating point hardware.	XP
pkgmgr	Installs, uninstalls, and configures packages and functions for Windows.	10/8/7/Vista
pnpunattend	Automates the installation of device drivers.	10
pnputil	Installs plug-and-play devices from the command prompt.	10/8/7/Vista
power	Uses the IDLE status of a processor to reduce energy consumption.	98/95/DOS
powercfg	Allows the user to change the computer’s energy options and control energy conservation plans.	10/8/7/Vista/XP
pwlauncher	Configures the startup options for Windows To Go with which you can boot Windows from a USB drive.	10/8
qprocess	Provides information on running processes.	10/8/7/Vista
query	Displays the status of a particular service.	10/8/7/Vista
quser	Provides information on the currently logged-in users.	10/8/7/Vista
reagentc	Configures the Windows recovery environment, with which you can repair the installation of the operating system.	10/8/7
recimg	Creates a user-defined Windows image to restore the system.	8
reg	Manages the registry of the command prompt. Users can create new keys (reg add) or delete them (reg delete).	10/8/7/Vista/XP
regini	Changes registry authorizations.	10/8/7/Vista/XP
register-cimprovider	Registers a common information model provider (CIM provider) in Windows.	10/8
regsvr32	Registers a DLL file in the registry.	10/8/7/Vista/XP
relog	Creates new performance indicator protocols from the data in the existing protocols.	10/8/7/Vista/XP
repair-bde	Repairs and decrypts defective drives that are encrypted with BitLocker. The files should be saved on a replacement drive.	10/8/7
reset	Resets a session. You can also use the rwinsta command.	10/8/7/Vista/XP
restore	Restores backups that were created with the backup command (replaced by msbackup).	DOS
rwinsta	Command has the same function as reset.	10/8/7/Vista/XP
sc	Manages services by connecting to the Service Controller.	10/8/7/Vista/XP
scanreg	Repairs the registry and allows a backup to be created of it.	98/95
sdbinst	Applies user-defined database files (SDB).	10/8/7/Vista/XP
secedit	Analyzes the security settings by comparing the current configurations with templates. Settings can also be configured, imported, and exported with this command.	10/8/7/Vista/XP
setver	Sets a version number of MS-DOS that’s forwarded to a program – even if it doesn’t match the actual version.	32-bit/DOS
setx	Creates or changes environmental variable in the user of system environment.	10/8/7/Vista
sfc	Checks all important and protected system files. Incorrect versions are replaced by correct ones.	10/8/7/Vista/XP
smartdrv	Starts and manages the hard drive cache program SMARTDrive.	98/95/DOS
sys	Copies system files from MS-DOS and the command interpreter to another hard drive. This makes it bootable.	98/95/DOS
systeminfo	Displays information about the Windows installation, including all installed service packages. The information can be obtained from the local system as well as a remote computer.	10/8/7/Vista/XP
tpmvscmgr	Creates and deletes TPM virtual smart cards. These are virtual smartcards encrypted on the basis of the Trusted Platform Model.	10/8
tracerpt	Processes logs or real-time data generated during the tracing of computer programs.	10/8/7/Vista/XP
typeperf	Displays performance counter data or writes it into a file.	10/8/7/Vista/XP
unformat	Undoes the drive formatting done by the format command.	DOS
unlock	Unlocks a drive that was locked with the lock command.	98/95
unlodctr	Deletes names as well as descriptions for extensible performance counters in the Windows registry.	10/8/7/Vista/XP
vaultcmd	Creates, deletes, and displays saved registration information.	10/8/7
vol	Displays the label and serial number of a drive.	All Win/DOS
vsafe	Starts the antivirus software VSafe.	DOS
vssadmin	Manages the volume shadow copy services that can be used to store different versions (snapshots) of drives.	10/8/7/Vista/XP
wbadmin	Creates backups of the operating system and delivers information to the created backup copies.	10/8/7/Vista
wevtutil	Manages event logs and event log files.	10/8/7/Vista
whoami	Provides information about the current user. With the /GROUP parameter you can obtain additional information about group membership.	10/8/7/Vista
winmgmt	Manages WMI repositories. Backups (/backup) are possible with the command, for example.	All Win
winsat	Evaluates various system factors – for example, processor performance or graphical capabilities.	10/8/7/Vista
wmic	Starts the Windows Management Instrumentation in the command prompt. Various Windows settings can be changed here – both locally and on remote computers.	10/8/7/Vista/XP
xwizard	Registers Windows data in the form of XML files.	10/8/7
Network
CMD command	Description	Windows version
arp	Displays and edits entries in the Address Resolution Protocol cache.	All Win
atmadm	Displays information on asynchronous transfer mode (ATM).	XP
certreq	Manages and creates certificate registration requirements for certification authorities.	10/8/7/Vista
certutil	Manages services related to certificate authentication.	10/8/7/Vista
change	Changes the settings of a terminal server and can be used together with the parameters logon, port, or user (replaces the commands chglogon, chgport, and chgusr).	10/8/7/Vista
checknetisolation	Checks the network capability of apps from the Windows Store.	10/8
chglogon	Enables, disables, or adjusts logins for terminal server sessions.	10/8/7/Vista
chgport	Displays or changes the COM pin assignment of terminal servers for DOS compatibility.	10/8/7/Vista
chgusr	Changes the installation mode of a terminal server.	10/8/7/Vista
cmstp	Installs or uninstalls profiles for the connection manager.	10/8/7/Vista/XP
djoin	Creates a new computer account in the Active Directory Domain Services (AD DS).	10/8/7/Vista
finger	Provides information about users on remote devices using the Finger service.	10/8/7/Vista/XP
ftp	Transfers data to an FTP server or from this to a PC. The command offers additional options: For example, you can activate debugging with -d.	All Win/DOS
getmac	Displays the MAC address of all network adapters. The format of the output (Table, List, CSV) is set with /FO. With /S you can use the command on remote systems as well.	10/8/7/Vista/XP
gpresult	Displays information on the Group Policy.	10/8/7/Vista/XP
gpupdate	Updates information on the Group Policy.	10/8/7/Vista/XP
hostname	Outputs the name of the current host.	10/8/7/Vista/XP
interlnk	Connects two computers via serial or parallel connection to share files or printers.	DOS
intersvr	Starts an interlnk server and transfers data from one computer to another via serial or parallel connection.	DOS
ipconfig	Provides information on the IP of each used network adapter. The command can also be used to release (/release) or renew (/renew) addresses. With /flushdns you can clear the DNS cache.	All Win/DOS
ipxroute	Changes and displays information on the IPX routing tables.	XP
irftp	Transfers files via infrared connection, if one is available.	10/8/7/Vista
iscsicli	Manages iSCSI, which enables connections via the SCSI protocol.	10/8/7/Vista
klist	Displays all tickets authenticated by the Kerberos service. Also enables the command to delete tickets (purge).	10/8/7
ksetup	Configures a connection to a Kerberos server.	10/8/7
mount	Enables network sharing under the Network File System. (To use the command, enable NFS services).	7/Vista
mrinfo	Provides information on the router.	10/8/7/Vista/XP
nbtstat	Displays statistics and information on the TCP/IP connections on remote computers.	10
net	Configures and displays network settings.	All Win
net1	Configures and displays network settings (it’s recommended to use net instead; the net1 command is only intended as a temporary solution for a Y2K problem).	10/8/7/Vista/XP
netsh	Starts the network shell, which allows for network settings to be changed on local and remote computers.	10/8/7/Vista/XP
netstat	Displays statistics and information on TCP/IP connections on the local computer.	All Win
nfsadmin	Manages NFS servers and clients (to be able to use the command, you first have to enable NFS services in Windows).	7/Vista
nltest	Displays information related to secure channels in the Active Directory Domain Services (AD DS) and tests the connections.	10/8/7
nslookup	Sends a DNS query to a specific IP or host name on the preconfigured DNS server. You can also specify another DNS server.	10
ntsd	Runs debugging.	XP
pathping	Provides information on forwarding and package loss when sending over a network and also specifies the latency.	10/8/7/Vista/XP
ping	Sends an internet control message protocol echo request to a specific host to check if it’s accessible. The duration of the echo can also be specified. Ping signals can be sent continuously with -t. To display statistics on this action, press Ctrl + Brk. Cancel the process with Ctrl + C.	All Win
qappsrv	Displays all available remote computers in the network.	10/8/7/Vista/XP
qwinsta	Displays information on the open remote desktop sessions.	10/8/7/Vista
rasautou	Manages autodial addresses.	10/8/7/Vista/XP
rasdial	Starts and ends network connections for Microsoft clients.	10/8/7/Vista/XP
rcp	Copies files from a Windows computer to a server that’s running a RSDH daemon, and vice versa.	7/Vista/XP
rdpsign	Signs a remote desktop protocol file (RDP file).	10/7
rexec	Runs commands on a remote computer that’s running a Rexec daemon.	Vista/XP
route	Displays routing tables and makes it possible to change, add, or delete entries.	All Win
rpcinfo	Sends a remote procedure call (RPC) to an RPC server. The result displays the programs on the remote computer (to use the command, NFS services on Windows have to be enabled first).	7/Vista
rpcping	Sends a ping via remote procedure call (RPC) and checks whether a connection is possible.	10/8/7/Vista
rsh	Runs commands on remote computers that are running the Unix program Remote Shell (RSH).	7/Vista/XP
setspn	Creates, deletes, and changes SPNs. These are unique identifiers for services on a network that uses Kerberos authentication.	10/8/7
shadow	Monitors a session on a remote computer. The user can also actively control the remote computer.	7/Vista/XP
showmount	Provides information on NFS file systems (to use the command, you first have to activate NFS services in Windows).	7/Vista
tcmsetup	Enables or disables a client for the Telephony Application Programming Interface (TAPI), a programming interface for telephone applications.	10/8/7/Vista/XP
telnet	Enables communication with another computer that also uses the telnet protocol.	All Win/DOS
tftp	Enables a file exchange between the local computer and a server that supports the Trivial File Transfer Protocol (TFTP). To use the command, the TFTP client first needs to be enabled in the system settings.	10/8/7/Vista/XP
tlntadmn	Manages a telnet server on a local or remote computer (to be able to use the command, the telnet server functions first have to be enabled in the system settings).	8/7/Vista/XP
tracert	Tracks a data package on the way through the network to a server. It doesn’t only check whether the package arrives and how long it takes, but also records how many hops the package makes on the way. All packages have a set time-to-live (TTL), which is increased gradually with the command.	All Win
tscon	Connects the current local user session with a session on a remote computer.	10/8/7/Vista/XP
tsdiscon	Ends the connection between a local user session and a session on a remote computer.	10/8/7/VistaXP
tskill	Ends a process on a remote computer.	10/8/7/Vista/XP
tsshutdn	Shuts down or restarts a remote terminal server. If the target computer supports it, the entire computer can be turned off in this way.	XP
umount	Removes mounted network file system drives. To use the command, the NFS functions first have to be enabled in the system settings.	7/Vista
w32tm	Manages the Windows time service that synchronizes dates and times on all computers that share an AD DS domain.	10/8/7/Vista/XP
waitfor	Sends or waits on a single. If the signal is only supposed to be sent to specified computers in a domain instead of all, use the /S parameter. Computers within a network are synchronized with one another through this command.	10/8/7/Vista
wecutil	Creates and managements subscriptions for events. These are forwarded from remote event sources that support the WS management protocol.	10/8/7/Vista
winrm	Manages secure connections between local and remote computers via the WS management protocol.	10/8/7/Vista
winrs	Enables access to the command line of a remote computer via a secure connection to implement changes. If you want to disable encryption, use -un.	10/8/7/Vista
wsmanhttpconfig	Manages functions of the Windows Remote Management (winrm).	10/8/7/Vista

     Great table that I want to include in my tool kit when I figure out how to put tables
## Additional Resources

#### 1. An A-Z Index of Windows CMD commands. 
https://ss64.com/nt/
_Narrative: Very useful in terms of finding the right command for the job!
