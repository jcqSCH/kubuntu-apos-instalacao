# KUBUNTU

Lista de aplicações para instalar após a formatação do computador, testado na versão Kubuntu 18.04.3 LTS. <br/><br/>

## 1 ➜ PACOTES .DEB OU SNAP
**VS Code:** https://code.visualstudio.com/download/ <br/> 
**Spotify:** https://www.spotify.com/br/download/linux/ <br/>
**Google Chrome:** https://www.google.com/chrome/browser/desktop/

<br/>

## 2 ➜ COMANDOS NO TERMINAL
	sudo apt-get update && 

	sudo apt-get install kde-l10n-ptbr -y && 
	sudo apt-get install libreoffice-l10n-pt-br -y && 
	sudo apt-get install kubuntu-restricted-extras -y && 
	sudo apt-get install bleachbit -y && 
	sudo apt-get install git-all -y && 

	sudo apt-get update && 

	sudo add-apt-repository ppa:danielrichter2007/grub-customizer -y && 
	sudo add-apt-repository ppa:nemh/systemback -y && 
	sudo add-apt-repository ppa:docky-core/stable -y && 
	sudo add-apt-repository ppa:rvm/smplayer -y && 
	sudo add-apt-repository ppa:qbittorrent-team/qbittorrent-stable -y && 
	sudo add-apt-repository ppa:inkscape.dev/stable -y && 

	sudo apt-get update && 

	sudo apt-get install grub-customizer -y && 
	sudo apt-get install systemback -y && 
	sudo apt-get install plank -y && 
	sudo apt-get install smplayer smplayer-themes smplayer-skins -y && 
	sudo apt-get install qbittorrent -y && 
	sudo apt-get install inkscape -y && 

<br/>

## 3 ➜ CONFIGURAÇÕES
#### Plank temas: https://github.com/KenHarkey/plank-themes/archive/master.zip

#### Fontes do Sistema:
|  Configurações   |             …             |
|       ---        |            ---            |
|  Geral:          |  Segoe WP 14              |
|  Largura fixa:   |  Courier 10 pitch 16      |
|  Pequena:        |  Segoe WP 13              |
|  Barra:          |  Segoe WP 13              |
|  Menu:           |  Segoe WP 14              |
|  Título:         |  Segoe WP 14 ( negrito )  |
|        …         |             …             |
|  Anti-aliasing   | Habilitado, RGB, Leve     |

<br/>

## 4 ➜ DICAS

#### Para desmontar a partição do Windows no Kubuntu:
	mount -o ro /dev/sda2
> A parte `sda2` talvez mude no seu computador se essa não for a partição em que está o Windows
- FONTE: http://askubuntu.com/questions/335909/error-mounting-dev-sda2-at-media

<br/>

#### Corrigir bug da lixeira que não deixa excluir:
	sudo chown -R "$USER" ~/.local/share/Trash
> (A parte `"$USER"` corresponde ao seu nome de usuário no Ubuntu, e não deve conter as aspas)
- FONTE: http://askubuntu.com/questions/288513/cant-move-files-to-the-trash
