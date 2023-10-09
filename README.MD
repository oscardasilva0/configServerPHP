Como instalar o PHP 8 no Ubuntu 8 e derivados

Como instalar o PHP 8 no Ubuntu e sistemas derivados
Como instalar o PHP 8 no Ubuntu e sistemas derivados

Para instalar o programa no Ubuntu e ainda poder receber automaticamente as futuras atualizações dele, você deve fazer o seguinte:

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
