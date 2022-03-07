# instalacao-docker
Passo a passo para instalação d docker
### Documentação oficial: 
https://docs.microsoft.com/en-us/windows/wsl/install-win10

### Passo 1 (PowerShell Admin): 
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart

### Passo 2 (PowerShell Admin):
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart

### Passo 3
REINICIE O COMPUTADOR

### Passo 4 (Download the Linux kernel update package):
https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi

### Passo 5 (PowerShell Admin):
wsl --set-default-version 2

### Passo 6 (Instale o docker):
Tutorial: https://docs.docker.com/docker-for-windows/install/

### Passo 7 (Adicionar o usuario ao grupo de adm do docker Admin)
7.1-Procure na barra de pesquisa 'gerenciamento do computador';<br>
7.2-Ferramentas do sistema;<br>
7.3-Usuarios e Grupos Locais;<br>
7.4-Grupos;<br>
7.5-Docker-users(provavelmente o último da lista);<br>
7.6-Adicione o seu usuário;<br>
7.7-Aplicar e salvar;<br>
7.8-Reiniciar o computador.<br>

##Máquina pronta para a primeira imagem!!
