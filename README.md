# Windows 10 Tweak Toolbox


this script will give you the ability to tweak windows to your needs,
it won't do anything on its own it will ask you before doing almost everything.

<br/>

**You will be able to:**
- disable windows updates
- disable windows defender
- [debloat windows](https://github.com/REVENGE977/debloat-win10/blob/de897a3ef04b723dd1cb2c0dd8f1e1775a08615d/DebloatWin10%20(RUN%20AS%20ADMIN).ps1#L50)
- disable background apps
- disable windows search indexer
- download [Chocolatey](https://github.com/REVENGE977/debloat-win10#what-is-chocolatey-)
- run [O&O Shutup10](https://www.oo-software.com/en/shutup10) 
- disable telemetry
- disable location tracking
- disable scheduled tasks
- disable Cortana
- disable action center
- enable Visualfx
- uninstall OneDrive
- download [ReduceMemory & ReduceDisk](https://github.com/REVENGE977/debloat-win10#what-is-reducememory--reducedisk-)
- download [Classic Shell](https://github.com/REVENGE977/debloat-win10#what-is-classic-shell-)

### How to run ?
press `windows + r`
and type `powershell`
and press `ctrl + shift + enter`
**If UAC prompt comes up, click yes**

and paste this command:
```powershell
iex ((New-Object System.Net.WebClient).DownloadString('https://git.io/JmyLZ'))
```
<br/>
<br>
<img src="https://upload.wikimedia.org/wikipedia/commons/b/b0/Chocolatey_icon.png" width="95" align="right"/>

### What is Chocolatey ?
[Chocolatey](https://chocolatey.org/) is a package manager for windows, which means it will give you the ability to download & install a program by using commands instead if setups 

<br/>
<img src="https://l.top4top.io/p_1905hnmof1.png" width="95" align="right"/>

### What is Classic Shell ?
[Classic Shell](http://www.classicshell.net/) is a software manages your start menu, for example you can get windows 7 start menu and you can change the start icon too, pretty useful for slow pc's.
**chocolatey is required to installing this app**

<br/>

### What is ReduceMemory & ReduceDisk ?
<img src="https://h.top4top.io/p_19051sqsd1.png" width="120" align="right"/>

- [ReduceMemory](https://www.sordum.org/9197/reduce-memory-v1-4/) is a magical software will reduce your memory usage in one click, and you can make it reduce the memory automatically too.

<br/>
<br/>
<img src="https://c.top4top.io/p_1905hi3sf1.png" width="95" align="right"/>

- [ReduceDisk](https://github.com/REVENGE977/debloat-win10/raw/main/somethings/ReduceDisk.exe)
 is a software created by me, i realized that on the newer windows updates when you end 'System' task from the task manager
the disk usage will be reduced, so this will actually end 'System' task all the time to reduce the disk usage,
i know this is so weird but i tried it and it actually works so try it by yourself !

**chocolatey is required to install both**
