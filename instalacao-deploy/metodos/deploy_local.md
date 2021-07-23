# Local/VPS

## Requisitos

* Python 3.8 ou Superior

## Como Instalar

#### **Metodo fácil e automatico \(testado em Ubuntu 18.04/20.04\)**

```text
bash <(curl -s https://fnixdev.github.io/Setup_Local_VPS.sh)
```

#### **Método manual**

**1. Instalando os pacotes**

```text
sudo apt install tree wget2 p7zip-full jq ffmpeg wget git
```

```text
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
```

```text
sudo apt install ./google-chrome-stable_current_amd64.deb
```

**2. Clone o Repositorio**

```text
git clone https://github.com/fnixdev/KannaX.git && cd KannaX
```

**3. Instale os requisitos**

```text
pip3 install -r requirements.txt
```

**4. Crie config.env como config.env.sample e preencha as Vars**

```text
cp config.env.sample config.env
```

**5. Obtenha a Session String** [**AQUI**](https://replit.com/@fnixdev/StringSessionKX) **e adicione-a ao config.env**

**6. Finalmente execute o KannaX.**

