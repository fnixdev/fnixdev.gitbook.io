# Add files via upload@fc34435

[Permalink](add-files-via-upload-fc34435.md)

[Browse files](https://github.com/fnixdev/KannaX/tree/fc34435870d7bf6c252aaacdca961018df0e4e39)

 Add files via upload

* Loading branch information

 Showing with **41 additions** and **0 deletions**.

1.  +8 −0 [.deepsource.toml](add-files-via-upload-fc34435.md#diff-a8c050b1fb601cdd8ba1282e837bc0b553d4f83de74d151e52f415b4e1ed6d14)
2.  +20 −0 [.gitpod.Dockerfile](add-files-via-upload-fc34435.md#diff-454eff0561fdbb1cdf08bef7a76ddf0f82c65fca08a150c43650f5098ecf7118)
3.  +13 −0 [.gitpod.yml](add-files-via-upload-fc34435.md#diff-370a022e48cb18faf98122794ffc5ce775b2606b09a9d1f80b71333425ec078e)

|  |  | @@ -0,0 +1,8 @@ |
| :--- | :--- | :--- |
|  |  |  version = 1 |
|  |  |  |
|  |  |  \[\[analyzers\]\] |
|  |  |  name = "python" |
|  |  |  enabled = true |
|  |  |  |
|  |  |  \[analyzers.meta\] |
|  |  |  runtime\_version = "3.x.x" |

|  |  | @@ -0,0 +1,20 @@ |
| :--- | :--- | :--- |
|  |  |  FROM gitpod/workspace-full |
|  |  |  |
|  |  |  RUN sudo apt-get update \ |
|  |  |  && sudo apt-get install -y --no-install-recommends \ |
|  |  |  tree \ |
|  |  |  mediainfo \ |
|  |  |  neofetch \ |
|  |  |  ffmpeg \ |
|  |  |  libasound2-dev \ |
|  |  |  libgtk-3-dev \ |
|  |  |  libnss3-dev \ |
|  |  |  curl \ |
|  |  |  git \ |
|  |  |  gnupg2 \ |
|  |  |  unzip \ |
|  |  |  wget \ |
|  |  |  jq && \ |
|  |  |  sudo rm -rf /var/lib/apt/lists/\* |
|  |  |  |
|  |  |  RUN curl -sO https://cli-assets.heroku.com/install.sh && bash install.sh && rm install.sh  |

|  |  | @@ -0,0 +1,13 @@ |
| :--- | :--- | :--- |
|  |  |  image: |
|  |  |  file: .gitpod.Dockerfile |
|  |  |  |
|  |  |  tasks: |
|  |  |  \# Install dependencies first. |
|  |  |  - init: pip install -r ./requirements.txt |
|  |  |  \# Then run if there's config.env, otherwise prompt to configure. |
|  |  |  command: &gt; |
|  |  |  if \[\[ -f config.env \]\]; then |
|  |  |  bash run |
|  |  |  else |
|  |  |  echo "Please edit the config.env.sample and rename it to 'config.env'. Then to run do-&gt; bash run" |
|  |  |  fi |

