DESATIVAR FIREWALL
```bash
sudo ufw disable
```
ADCIONAR USUARIO DEPLOY
```bash
adduser deploy
```
ADCIONAR USUARIO DEPLOY AO SUDOERS
```bash
usermod -aG sudo deploy
```

FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/ronaldodavi/instaladorwhatsapsaas-main && sudo chmod -R 777 instaladorwhatsapsaas-main && cd instaladorwhatsapsaas-main && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd ./instaladorwhatsapsaas-main && sudo ./install_instancia
```

