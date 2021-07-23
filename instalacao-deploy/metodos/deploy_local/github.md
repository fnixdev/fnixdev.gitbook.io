# GitHub

 [![](https://camo.githubusercontent.com/6da73f985d095d4545c500965a78e59c9dfd8e598ce5926351f2b9f6e3483ace/68747470733a2f2f74656c656772612e70682f66696c652f6330303563613266353232363539646139623937382e706e67)](https://t.me/kannaxupdates)

 [![](https://camo.githubusercontent.com/d299ecd4fa54d4fd1b56a921b43c31539c4ef6df85c00758edf684c726678df1/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f417574686f722d666e69786465762d7265642e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562)](https://github.com/fnixdev) [![](https://camo.githubusercontent.com/b24b012184e16c94748fd121c2979db68cfe88fcc65d63cbea59219d820c2210/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f464e49584445562d42494f2d7265642e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6170707665796f72)](http://fnixdev.github.io/)

 [![](https://camo.githubusercontent.com/2fed016167afda684b22a48dedcf50642bdb90bc034c11f4de8d3f44f00046f0/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4a6f696e2d54656c656772616d25323047726f75702d7265642e7376673f7374796c653d666c61742d737175617265266c6f676f3d54656c656772616d)](https://t.me/kannaxupdates) [![GitHub issues](https://camo.githubusercontent.com/920ba0e65d26ee335dc033978898e389e05c9ecb1c0815dfefc9e31ac5e9d2fc/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6973737565732f666e69786465762f4b616e6e61583f7374796c653d666c61742d737175617265)](issues.md) [![GitHub license](https://camo.githubusercontent.com/cb0d6bc53708a67ec9beb976c8898403b08aded8fe0e2657317a91c66a473364/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6963656e73652f666e69786465762f4b616e6e61583f7374796c653d666c61742d737175617265)](blob/master/kannax-license-at-master.md) [![GitHub stars](https://camo.githubusercontent.com/7b98aaef033d843fda1addcefa095d2b111fed784e3dce25ca3da2e56680ca72/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f666e69786465762f4b616e6e61583f7374796c653d666c61742d737175617265)](stargazers.md) [![GitHub forks](https://camo.githubusercontent.com/7031a886e0ade1a3129887231b2ea2df363cbbea787f3f1f7221596e9ff18f1e/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f666f726b732f666e69786465762f4b616e6e61583f7374796c653d666c61742d737175617265)](https://github.com/fnixdev/KannaX/network)

## Disclaimer

```text
/**
   ⚠️Kang por sua própria conta e risco⚠️
    Sua conta do Telegram pode ser banida.
    Eu não sou responsável por qualquer uso indevido deste bot
    Este bot tem o objetivo de se divertir com memes,
    bem como gerenciar grupos de forma eficiente.
    Ele também pode ajudá-lo a se controlar.
    Você acabou enviando spam para grupos, sendo denunciado à direita e à esquerda,
    e então você acabou em uma batalha com o Telegram
    e no final a Equipe do Telegram
    excluiu sua conta?
    E depois disso, você apontou seus dedos para mim
    por sua conta ter sido excluída?
    Estarei rolando no chão rindo de você.
    Sim! você ouviu direito.
/**
```

## Requirements

* Python 3.8 ou Superior
* Telegram [API Keys](https://my.telegram.org/apps)
* Google Drive [API Keys](https://console.developers.google.com/)
* MongoDB [Database URL](https://cloud.mongodb.com/)

## Como Instalar

**Detalhes e Guias**

### Pelo Heroku

- Clique aqui para dar deploy ao KannaX.

[![MyGpac](https://camo.githubusercontent.com/6979881d5a96b7b18a057083bb8aeb87ba35fc279452e29034c1e1c49ade0636/68747470733a2f2f7777772e6865726f6b7563646e2e636f6d2f6465706c6f792f627574746f6e2e737667)](https://heroku.com/deploy?template=https://github.com/fnixdev/KannaX-Deploy)

- Preencha API\_ID \| API\_HASH \| DATABASE\_URL \| LOG\_CHANNEL\_ID \| HEROKU\_APP\_NAME \| HEROKU\_API\_KEY **\(obrigatorio\)**

**- Cique no botao Deploy.**

**- Ligue o Dyno na aba de Resource.**

**- É isso ... Comece a usar KannaX.**

**Você pode adicionar tambem** [**VARs não obrigatorias**](https://telegra.ph/Deploy-VARs-Heroku-05-26) **mais tarde de acordo com suas necessidades. Esses vars são usados por seus respectivos plug-ins no userbot para funcionar. Para saber como adicionar vars não obrigatórios, verifique este** [**Guia**](https://telegra.ph/Tutorial-VARs-Extras-06-15)**.**

### **Instalando com Metodo Tradicional**

#### **Metodo fácil e automatico**

```text
$ bash <(curl -s https://fnixdev.github.io/Setup_Local_VPS.sh)
```

#### **Método manual**

**1. Instalando os pacotes**

```text
$ sudo apt install tree wget2 p7zip-full jq ffmpeg wget git
```

```text
$ wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
```

```text
$ sudo apt install ./google-chrome-stable_current_amd64.deb
```

**2. Clone o Repositorio**

```text
$ git clone https://github.com/fnixdev/KannaX.git && cd KannaX
```

**3. Instale os requisitos**

```text
$ pip install -r requirements.txt
```

**4. Crie config.env como config.env.sample e preencha as Vars**

```text
$ cp config.env.sample config.env
```

**5. Obtenha a Session String e adicione-a ao config.env**

Ou voce pode usar [REPL](https://replit.com/@fnixdev/StringSessionKX) para obter a string.

**6. Finalmente execute o KannaX**

## **String Session**

* **VAR -&gt; `HU_STRING_SESSION`**

#### **Pelo HEROKU**

* [**Abra seu app heroku**](https://dashboard.heroku.com/apps/) **clique em more** -&gt; **run console** e digite `bash genStr` e clique em **run**.

#### Pelo REPL \(Metodo mais facil\)

* [Gerar String no REPL](https://replit.com/@fnixdev/StringSessionKX)

### Créditos pelo Projeto

* [USERGE-X](https://github.com/code-rgb/USERGE-X)
* [Pyrogram Assistant](https://github.com/pyrogram/assistant)
* [PyroGramBot](https://github.com/SpEcHiDe/PyroGramBot)
* [PaperPlane](https://github.com/RaphielGang/Telegram-Paperplane)
* [Uniborg](https://github.com/SpEcHiDe/UniBorg)

### Copyright & License

[**GNU General Public License v3.0**](blob/master/kannax-license-at-master.md)

