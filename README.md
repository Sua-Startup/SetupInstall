## Ferramentas

Com essa solução, você consegue instalar as seguintes ferramentas:

- <b>Chatwoot</b>
- <b>Evolution API</b>
- <b>Typebot</b>

## Instalação

<p>Primeira instalação na minha VPS:</p>

```
sudo apt upgrade -y && sudo apt update && sudo apt install -y git && git clone https://github.com/Sua-Startup/SetupInstall.git && cd SetupInstall && sudo chmod +x install.sh && ./install.sh
```

<p>Já tenho uma instalação na minha VPS (para quem quer instalar outra aplicação):</p>

```
sudo apt upgrade -y && sudo apt update && cd SetupInstall && git stash && git pull && chmod +x install.sh && ./install.sh
```
