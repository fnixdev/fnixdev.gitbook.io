---
description: VARs adicionais para o bot
---

# VARs Opcionais

## Definindo as VARs.

* **Heroku: **pelo bot use** **`.setvar LOAD_UNOFFICIAL_PLUGINS true`
* **Local: **edite o arquivo `config.env `

{% content-ref url="g_drive_client_id-and-g_drive_client_secret.md" %}
[g\_drive\_client\_id-and-g\_drive\_client\_secret.md](g\_drive\_client\_id-and-g\_drive\_client\_secret.md)
{% endcontent-ref %}

{% content-ref url="alive_media.md" %}
[alive\_media.md](alive\_media.md)
{% endcontent-ref %}

{% content-ref url="custom_pack_name.md" %}
[custom\_pack\_name.md](custom\_pack\_name.md)
{% endcontent-ref %}

#### Defina false se você não gosta de usar plug-ins extras

`LOAD_UNOFFICIAL_PLUGINS=true`

#### É melhor se você quiser adicionar seus próprios plug-ins

#### privado / público ambos os repositórios são suportados

#### Faça fork da pagina [KannaX-Plugins](https://github.com/fnixdev/KannaX-Plugins) e adicione seus plugins

`CUSTOM_PLUGINS_REPO=false`

#### Contagem de trabalhadores do Userbot : Default = cpu\_count + 4

`WORKERS`

#### Defina como true se for TeamDrive

G\_DRIVE\_IS\_TD=false

#### Index link do gdrive

`G_DRIVE_INDEX_LINK`

#### Defina o nome para o seu diretório de trabalho

`DOWN_PATH="downloads/"`

#### Your Languge ( ex: if english => 'en' )

`PREFERRED_LANGUAGE="pt"`

#### Obter chave API de 'https://free.currencyconverterapi.com/'

`CURRENCY_API`

#### Obter a chave API para o módulo OCR 'http://eepurl.com/bOLOcf'

`OCR_SPACE_API_KEY`

#### Adicionar cidade padrão para o clima

`WEATHER_DEFCITY`

#### SpamWatch API pode ser obtido em @SpamWatch no Telegram

`SPAM_WATCH_API`

#### API do tempo pode ser obtida em 'https://openweathermap.org/'

`OPEN_WEATHER_MAP`

#### RemoveBg API Key obtê-lo em 'https://www.remove.bg/api'

`REMOVE_BG_API_KEY`

#### GDrive ID da pasta

`G_DRIVE_PARENT_ID`

#### &#x20;Definir prefixo de comando

`CMD_TRIGGER="."`

#### Definir prefixo de comando para usuários SUDO

`SUDO_TRIGGER="!"`

#### Defina isso para seu fork KannaX no GitHub

`UPSTREAM_REPO`

#### Unico caractere para o progresso concluído

`FINISHED_PROGRESS_STR='█'`

#### Caractere único para progresso inacabado

`UNFINISHED_PROGRESS_STR='░'`

#### Defina sua própria mídia personalizada para bot pm

`BOT_MEDIA`

#### Para Spotify Music Auto Bio, obtenha seu ID de client e secret do Spotify em

#### (https://developer.spotify.com/dashboard)

`SPOTIFY_CLIENT_ID`

`SPOTIFY_CLIENT_SECRET`

#### Nsfw Detect API Key para obtê-lo em https://deepai.org/dashboard/profile&#x20;

`DEEP_AI`

#### Para gen\_memes.py&#x20;

#### Pegue de https://imgflip.com/ criando uma conta gratuita

#### E não se esqueça de verificar seu endereço de e-mail e copiar o nome de usuário e a senha.

`IMGFLIP_ID`

`IMGFLIP_PASS`

#### LastFM username e api key

`LASTFM_USERNAME`

`LASTFM_API_KEY`
