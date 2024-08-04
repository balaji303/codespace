# codespace
List of Codespaces

- [c ninja listings](https://github.com/balaji303/c-ninja-listings)
- [C Exercise](https://github.com/balaji303/C-Exercise/tree/CodeSpace)
- [ESH](https://github.com/balaji303/esh)

*Even if we dont give any docker file, default image is used to create the github codespace*

## Complete Project Structure

'''

/my-project
|-- .devcontainer
|   |-- Dockerfile
|   |-- devcontainer.json
|-- .prettierrc
|-- .markdownlint.json
|-- .vscode
|   |-- settings.json
|-- (your project files)

'''

File and Directory Operations
Linux Command	Windows Command
ls	dir
cp	copy
mv	move
rm	del or erase
mkdir	mkdir
rmdir	rmdir
touch	type nul > filename
cat	type
nano or vim	notepad
File Permissions and Ownership
Linux Command	Windows Command
chmod	icacls
chown	icacls
System Information
Linux Command	Windows Command
top	tasklist
ps	tasklist
kill	taskkill
df	wmic logicaldisk get size,freespace,caption
free	systeminfo or wmic OS get FreePhysicalMemory
Network Commands
Linux Command	Windows Command
ifconfig or ip	ipconfig
ping	ping
netstat	netstat
ssh	ssh (via PowerShell or a tool like PuTTY)
Package Management
Linux Command	Windows Command
apt-get update	winget upgrade --all or choco upgrade all
apt-get install	winget install <package> or choco install <package>
Miscellaneous
Linux Command	Windows Command
sudo	Run Command Prompt or PowerShell as Administrator
clear	cls
echo	echo
