Elementary Os
====

Configurações do SO:
-------------------

**1) Atualizar o sistema:**

```shell
sudo apt update
```
```shell
sudo apt dist-upgrade
```

**2) Customizar tema:**

```shell
sudo apt-get install software-properties-common
```
**2.1 Tweeks:**

*Repositório e Instalação:*
```shell
sudo add-apt-repository ppa:philip.scott/elementary-tweaks
```
```shell
sudo apt update
```
```shell
sudo apt install elementary-tweaks
```

*Configurações:*
* Layou OS X
* Cores escuras

**3) Configurações Adicionais:**

**3.1 Instalando Codecs para rodar todos os formatos de áudio e vídeo**

```shell
sudo apt install ubuntu-restricted-extras -y
```

Aceitar os termos de licença para instalar as fontes da Microsoft, para isso basta apertar a "seta para ir para a direita" ou o "Tab" e pressionar "Enter":

Logo após use as setas para selecionar a opção "Sim" e dê "Enter" novamente.

Aguarde o final do processo e você já terá os Codecs instalados.

**3.2) Instalando PPAs e pacotes .deb**

Essa versão não tem suporte para PPAs e pacotes .deb nativamente.

```shell
sudo apt install software-properties-common gdebi -y
```

**3.3) Instalando Gerenciador de Drivers**

Instalar a interface com o comando:

```shell
sudo apt install software-properties-gtk
```

Ficará disponível em "Programas e atualizações". Gerenciamento de repositórios e drivers, exatamente como no Ubuntu.

**4) Instalar Apps:**

* Chrome (Site oficial)
* Firefox (Terminal)
* Vivaldi
* WPS Office (Site oficial)
* Synaptic (Terminal),
* Remmina (Site oficial)
* VLC (Terminal)
* Filezilla (Terminal)
* Poedit
```shell
sudo apt-add-repository ppa:vslavik/poedit
```
```shell
sudo apt update
```
```shell
sudo apt install poedit
```
* Gparted
* Desinstalar Scratch e Elephant
* Virtual Box
  * Win 7
  * Notepad
  * Fonts (Linux e Windows)
  * Illustrator, PS e Id
  * CorelDRAW Portable (+ .Net Framework 4.5)
  * Mouse without borders
  * Wirar

**5) Outras configurações**
  * Minimizar: canto inferior direito
  * Ctrl: para achar o mouse


Ambientes de Desenvolvimento
----------------------------

**1) Ambiente Front-end**

* Atom (Configs estão no GitHub)
* Git
* Nodejs
* Bower
* Grunt
* Componentes

**2) Ambiente PHP**

* Apache
* PHP
* MySQL
* PHPMyAdmin
* Wordpress

https://www.evernote.com/shard/s688/sh/5ad20ed3-c4bc-4a49-b81f-f313c7bc74ea/0d4a9dcf5044ad9ce99eb48a2d623e70

Configurar Virtual Host no servidor

https://www.digitalocean.com/community/tutorials/como-configurar-apache-virtual-hosts-no-ubuntu-14-04-lts-pt
