Como instalar o PHP 8 no Ubuntu e sistemas derivados

Para instalar o programa no Ubuntu e ainda poder receber automaticamente as futuras atualizações dele, você deve fazer o seguinte:
#debian

Passo 1. Abra um terminal;
Passo 2. Instale os seguintes pacotes necessários;

sudo apt-get install software-properties-common

Passo 3. Em seguida, adicione o repositório do software;

sudo add-apt-repository ppa:ondrej/php

Passo 4. Depois disso, atualize o APT;

sudo apt update

Passo 5. E, finalmente, instale o PHP 8 e alguns módulos;

sudo apt install php8.0 php8.0-intl php8.0-mysql php8.0-sqlite3 php8.0-gd

Passo 6. Em seguida, verifique a versão recém-instalada:;

php -V

#amazon linux/ cetreOs
#debian

Passo 1. Abra um terminal;
Passo 2. Instale os seguintes pacotes necessários;
sudo yum install gcc-c++ zlib-devel;

sudo yum install -y amazon-linux-extras 

Passo 4. Depois disso, atualize o APT;

sudo apt update

Passo 5. E, finalmente, instale o PHP 8 e alguns módulos;

sudo apt install php php8.*-intl  php8.*-gd php8.2-intl  php-mbstring

Passo 6. Em seguida, verifique a versão recém-instalada:;

php --version
