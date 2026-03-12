# Como clonar um repositório no android
Usaremos o aplicativo [[Termux]], para clonar repositórios para quaisquer fins pensáveis.
Instale o **Termux** através da Play Store

## Atualize o Termux
```
apt update
apt upgrade
```

## Instale e configure o git
```
pkg install git  
git config --global user.name "<name>"  
git config --global user.email "<email>"
```

## Acesse a pasta onde o repositório será clonado
Primeiro é necessário permitir que o **Termux** acesse os arquivos do dispositivos

```
termux-setup-storage
```
Após isso vá para a pasta e storage e abra os opções através do comando **ls** e escsolha a pasta desejada
```
cd storage
ls
cd nome-da-pasta
```
## Instale e configure uma chave SSH para autenticar no git hub
```
pgk install openssh
```
Create the SSH keys that we’ll be using as our authentication method to access our Git repository. You can keep the default file name. Enter a passphrase. Unless you enter a new location, the file path is `~/.ssh/id_ed25519.pub`.

```
ssh-keygen -t ed25519 -C "<email>"
```
## Envie a key para o GitHub
```
cp ~/.ssh/id_ed25519.pub ~/storage/shared/Documents/ # will place the file in the Documents folder.
```




https://towardsdev.com/how-to-clone-and-synchronise-a-github-repository-on-android-a59ddf7cd092