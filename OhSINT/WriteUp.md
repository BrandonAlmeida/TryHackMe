# OhSINT

Essa room tem o objetivo de obtenção de informações a partir da imagem abaixo: 

![](./WindowsXP.jpg)

## Information Gaethering

Foi utilizada a ferramenta `exiftool` para análise do metadados da imagem. 
O nome **OWoodflint** foi encontrado no campo *Copyright*. <br>
Ao realizar pesquisa na web, foi encontrada uma conta na rede social Twitter com o usuário em questão. 

___

Twitter: [Link](https://twitter.com/OWoodflint)

![Alt text](image.png)

A partir desta conta, podemos completar a primeira flag da room: 

*What is this user's avatar of?* <BR>
RSP: **Cat**

Ao analisar as postagens da conta em questão, obtem-se um BSSID supostamente da rede privada do alvo. <br>

Foi utilizada a ferramenta online [Wigle](https://wigle.net/) para identificação da localização do MAC encontrado e do SSID da rede.

*What city is this person in?*<BR>
RSP: **london**<br>

*What is the SSID of the WAP he connected to?*<BR>
RSP: **UnileverWiFi**<br>

___






