# How to Build?

**Step 1 - Installing Chocolatey and Cmake**

Run another Powershell.exe **As Administrator** and enter this command to install chocolatey like this:

![adminpshell](https://cdn.discordapp.com/attachments/794975038616895488/1008036672736342086/unknown.png)
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
![comand](https://cdn.discordapp.com/attachments/794975038616895488/1008037125448548402/unknown.png)

close Powershell and open it Again as Administrator and enter this command:
```
chocolatey install cmake
```
Answer Y to every question and when it is finished, close the Powershell.

![chocolatey](https://cdn.discordapp.com/attachments/794975038616895488/1008037498640928868/unknown.png)

**Step 2 - Cloning repository**

Open another Powershell and use `cd` to navigate into the desired location (default folder is C:/Users/your_name/)

*How do i use `cd`?*
Use `cd ../` to go back one Folder and use `cd path/to/your_folder/` to go into that Folder. This also works for full paths, i.e. C:/Users/example/Documents/.

To clone the repository ether these commands one by one:
```
git clone --recurse-submodules https://github.com/ange-yaghi/engine-sim
cd engine-sim/
mkdir build/
cd build/
```
![repo](https://cdn.discordapp.com/attachments/794975038616895488/1008038407362064404/unknown.png)

**Step 3 - Dependencies**

First, create a `local` folder in your `C:` drive.

![folder](https://cdn.discordapp.com/attachments/794975038616895488/1008038688393015326/unknown.png)

then put [these files]()
