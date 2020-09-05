# win10script
Esse é um script que reutiliza os scripts de debloat e gists do github. Também foi adicionado o Chocolatey e outras ferramentas que são comuns na maioria dos computadores.

Esse é o comando que vai rodar todo o código (baixa desse repositório e executa)
```
powershell -nop -c "iex(New-Object Net.WebClient).DownloadString('https://git.io/JUmad')"
```

## Adições

- Dark Mode
- Um comando para rodar o script
- Chocolatey Install
- O&O Shutup10 CFG and Run
- Adicionado Instalação de programas
- Adicionado Debloat Microsoft da Store Apps

## Modificações
É encorajado que dê um fork nesse projeto e comente as funções de forma que melhor se adapte para você! Seguem exemplos de modificações:
- Desinstalar o OneDrive (Está no script)
- Instalar o Adobe, Chocolatey, Notepad++, MPC-HC, and 7-Zip

Comente tudo o que você não quer... Exemplo:

```
########## NOTE THE # SIGNS! These disable lines This example shows UACLow being set and Disabling SMB1
########## Preste atenção no #  ele que vai comentar e desabilitar as funções, bem como retirá-lo vai ativar as funções.

Aqui mostra habilitando o UACLow e desabilitando o SMB1.

########## Valores originais:
### Security Tweaks ###
	"SetUACLow",                  # "SetUACHigh",
	"DisableSMB1",                # "EnableSMB1",

########## Valores Corrigidos
### Security Tweaks ###
	"SetUACHigh",                  # "SetUACLow",
	"EnableSMB1",                  # "DisableSMB1"
```
