<h1 align="center">INSTALADOR ONNZAP</h1>


## Vamos instalar?

FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
Criando usuário deploy:
useradd -m -p [[pluszap]] -s /bin/bash -G sudo deploy
usermod -aG sudo deploy
```

```bash
sudo apt install -y git && git clone https://github.com/Onndigital/instalador-vemfazer install && sudo chmod -R 777 ./install && cd ./install && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd && cd ./install && sudo ./install_instancia
```


## Para Instalação você precisa:

Uma VPS Ubuntu 20.04 (Configuração recomendada: 3 VCPU's + 4 GB RAM)

Subdominio para Frontend - Seu frontend

Subdominio para API -Seu backend

Email válido para certificação SSL


