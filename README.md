# WordPress Docker Setup

Este projeto cria um ambiente simples e prático com WordPress e MySQL usando Docker Compose. É uma ótima solução para quem deseja configurar um ambiente de desenvolvimento WordPress rapidamente, sem a complexidade de instalação manual.

## Pré-requisitos

- **Docker** e **Docker Compose** instalados na máquina.

## Comandos

1. Acessar o ﻿MySQL:
docker exec -it wordpress_mysql mysql -u wordpress_user -p

2. ﻿Acessar os arquivos Wordpress:
﻿﻿docker exec -it wordpress /bin/bash
