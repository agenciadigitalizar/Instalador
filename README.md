Atulizações de pacotes e instalação de libs que serão utilizadas pela vps.

```javascript
sudo apt update && sudo apt upgrade -y
```

```javascript
 sudo apt-get install -y libgbm-dev wget unzip fontconfig locales gconf-service libasound2 libatk1.0-0 libc6 libcairo2 libcups2 libdbus-1-3 libexpat1 libfontconfig1 libgcc1 libgconf-2-4 libgdk-pixbuf2.0-0 libglib2.0-0 libgtk-3-0 libnspr4 libpango-1.0-0 libpangocairo-1.0-0 libstdc++6 libx11-6 libx11-xcb1 libxcb1 libxcomposite1 libxcursor1 libxdamage1 libxext6 libxfixes3 libxi6 libxrandr2 libxrender1 libxss1 libxtst6 ca-certificates fonts-liberation libappindicator1 libnss3 lsb-release xdg-utils git
```

```javascript
sudo apt-get install build-essential
```

## 🍷 ADICIONAR USUÁRIO DEPLOY
```
adduser deploy
```

## 🍷 Instalação Automatica

Fazendo download do instalador e executando o instalador: 💾
```bash
sudo apt install -y git && git clone https://github.com/agenciadigitalizar/Instalador.git install && sudo chmod -R 777 ./install && cd ./install && sudo ./install_primaria
```

## 🍷 LINK DO GIT
```
https://github.com/agenciadigitalizar/repositorio-instalador.git
```
