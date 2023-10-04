# OhSINT

Essa room tem o objetivo de obtenção de informações a partir da imagem abaixo: 

![](./files/WindowsXP.jpg)

## Information Gaethering

Foi utilizada a ferramenta `exiftool` para análise do metadados da imagem. 
O nome **OWoodflint** foi encontrado no campo *Copyright*. <br>
Ao realizar pesquisa na web, foi encontrada uma conta na rede social Twitter com o usuário em questão. 

___

Twitter: [Link](https://twitter.com/OWoodflint)

![Alt text](files/image.png)

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

Após coletadas informações úteis no twitter, continuando as pesquisas, foi possível encontrar um GitHub em nome do alvo e um blog em wordpress.<br>

**GitHub:** [Link](https://github.com/OWoodfl1nt/people_finder)<br>

No GitHub foi possível identificar um gmail do alvo.<br>

*What is his personal email address?*<br>
RSP: **OWoodflint@gmail.com**<br>

No blog wordpress foi possível identificar outra localização para o alvo.<br>
*Where has he gone on holiday?*<br>
RSP: **New York**

Ainda no blog, é possível identificar uma possível senha escondida no source code do site.<br>
*What is the person's password?*<br>
RSP: **pennYDr0pper.!**



