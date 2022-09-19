# Windows



**1. Install Chocolatey**

Open Powershell as admin and run

```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1')) 
```

**2. Install Other Packages**

Only Git is Compulsary

```
choco install git
```

```
choco install wget
```

```
choco install ffmpeg
```

**3. Clone the Repository**

```
git clone https://github.com/fnixdev/Loader.git && cd Loader
```

**4. Install Requirements**

Open `install_req.bat`

**5. Create config.env as given config.env.sample and Fill that**

```
 copy config.env.sample config.env
```

**6. Get String Session and Add it to config.env**

Open genStr.bat OR you can use this [@genStr\_bot](https://t.me/genStr\_bot) to get the string.

**7. Finally Run Hilzu**

Open run.bat **OR** run

```
py -m loader
```
