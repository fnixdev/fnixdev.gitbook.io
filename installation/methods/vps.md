# VPS / Local

#### Requirements: <a href="#requirements" id="requirements"></a>

* Python (Min Version 3.8 & Max version 3.9)

#### Installing Automatic In Ubuntu or Variants:

```shell
bash <(curl -s https://raw.githubusercontent.com/fnixdev/Hilzu/master/resources/scripts/ubuntu_install.sh)
```



#### Installing Automatic In **Arch:**

```shell
bash <(curl -s https://raw.githubusercontent.com/fnixdev/Hilzu/master/resources/scripts/arch_install.sh)
```

****

**1. Install required package**

```shell
sudo apt install tree wget2 p7zip-full ffmpeg wget git neofetch mediainfo
```

```shell
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
```

```shell
sudo apt install ./google-chrome-stable_current_amd64.deb
```

**Notes:** Recommended FFMPEG version is 4.3 or above

**2. Clone the Repository**

```
git clone https://github.com/fnixdev/Loader.git && cd Loader
```

**3. Install Requirements**

```
bash install_req
```

**4. Create config.env as given config.env.sample and Fill that**

```
cp config.env.sample config.env
```

**5. Get String Session and Add it to config.env**

```
bash genStr
```

OR you can use this [@genStr\_bot](https://t.me/genStr\_bot) to get the string.

**6. Finally Run Hilzu**

```
bash run
```

\
