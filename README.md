# controlpanel
Control-Panel :passport_control:  Centro de controle mazonOS

## DEPENDÊNCIAS
* Dialog
* Bash
* Fcron

## ScreenShot<br>
![alt Run on mazonOS](https://raw.githubusercontent.com/slackjeff/controlpanel/master/screen.png)


## Instalação Manual
**Criação de diretórios especiais**<br>
* mkdir -v /etc/controlpanel/<br>
* mkdir -v /var/lib/controlpanel/<br>

**Copiar arquivos para os diretórios importantes**<br>
* cp -v {controlpanel.conf,controlpanel.dialog} /etc/controlpanel/<br>
* cp -v controlpanel.desktop /usr/share/applications/
* cp -v controlpanel.png /usr/share/icons/mazon/

**Se caso é o primeiro uso para testes utilize o changelog mais recente, após isso o mesmo começa a contar a partir deste momento**<br>
* {cd /var/lib/controlpanel/; wget http://mazonos.com/changelog.txt ;}
