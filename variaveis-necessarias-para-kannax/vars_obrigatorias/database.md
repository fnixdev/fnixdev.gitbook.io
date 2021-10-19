---
description: >-
  MongoDB é um programa de banco de dados. Classificado como um programa de
  banco de dados NoSQL, o MongoDB usa documentos do tipo JSON com esquemas
  opcionais.
---

# DATABASE\_URL

```
DATABASE_URL
```

## **1. Criando Cluster**

* Primeiro, abra o site [MongoDB ](https://www.mongodb.com)e crie uma conta clicando em `"try MongoDB now"` , inscreva-se com Google torna isso mais fácil. ; )
* Em seguida, clique no plano de cluster gratuito, escolha o provedor de nuvem e escolha a região e clique em`"create cluster"`

Se você deseja implantar no Heroku, escolha "AWS" e na região escolha "U.S." , caso contrário, escolha a região mais próxima de onde você está implantando.

{% hint style="danger" %}
Não use na sua senha caracteres como '`@`' ou '`:`'
{% endhint %}

## **2. Network Access** <a href="2-network-access" id="2-network-access"></a>

* Va para **Network Access** na guia **SECURITY **clique no botão `"add ip address".`

![](https://gblobscdn.gitbook.com/assets%2F-MNTQklL6f32BuRnjFuB%2F-MNTRa3jXyEGTxIFCogB%2F-MNTU-ouSpUazuXX2a88%2FScreenshot%202020-12-01%20182149.png?alt=media\&token=79b97a6a-26df-4d3b-b7e4-4def5797acae)

* Agora clique em `"ALLOW ACESS FROM ANYWHERE"` e clique em Confirm.

![](https://gblobscdn.gitbook.com/assets%2F-MNTQklL6f32BuRnjFuB%2F-MNTRa3jXyEGTxIFCogB%2F-MNTZ1Dc48MovQzrhEJk%2FScreenshot%202020-12-01%20182329.png?alt=media\&token=65f45339-c941-4fd6-a2c0-658a95f9de44)

## 3. Configurando um Cluster <a href="3-setting-up-a-cluster" id="3-setting-up-a-cluster"></a>

* Depois de configurar o acesso à rede, vá para a guia Clusters e clique em`"connect"` escolha o nome de usuário e defina a senha.

Dica: Use letras minusculas no nome de usuário e na senha e evite espaços em branco.

* em **connection methods** escolha`"Connect your Application"` como abaixo.

![](https://gblobscdn.gitbook.com/assets%2F-MNTQklL6f32BuRnjFuB%2F-MNTRa3jXyEGTxIFCogB%2F-MNTcjxyYxIzzjk5wc7p%2FScreenshot%202020-12-01%20182552.png?alt=media\&token=b62929fd-a771-4b1a-b350-b4f3947af8e3)

* Em seguida, configure o driver e a versão e clique no botão `"Copy"` para copiar o url.

> **DRIVER :** Python
>
> **VERSION :** 3.11 or later.

![](https://gblobscdn.gitbook.com/assets%2F-MNTQklL6f32BuRnjFuB%2F-MNTRa3jXyEGTxIFCogB%2F-MNTdbq4gXOncOdMFGPW%2FScreenshot%202020-12-01%20182654.png?alt=media\&token=6b46c90e-63b3-47ef-8eaa-b33b7ea0defa)

## 4. URL do banco de dados <a href="4-final-database-url" id="4-final-database-url"></a>

* Substitua \<password> pela sua senha e simplesmente remova '<>'.

Não se esqueça de remover o "<>" após adicionar a senha.

* Se o URL final do banco de dados for semelhante ao acima, você está pronto para prosseguir, basta adicioná-lo ao var.
