servidor_LAMP
============================

Servidor web com volumes persistentes, arquivos no diretório "www" são acessados pelo endereço "http://localhost".

Versões:
- Apache: 2.4.38 (Debian)
- PHP: 7.2.34
- PHPMyAdmin: 5.1.1
- MariaDB: 10.7.1
- Postgress: 14

Portas encaminhadas:
- Apache: 80/tcp, 443/tcp
- PHPMyAdmin: 8080/tcp
- MariaDB: 3306/tcp
- Postgres: 5432/tcp

## QuickStart

1. Fazer o clone do repositório para a maquina local
2. Rodar o comando no diretório raiz.
```
docker-compose up -d
```

## Acesso e senha padrão
- MariaDB:
    - Usuário: root
    - Senha: mariadb
    - Host: db
- PHPMyAdmin:
    - Acesso: http://localhost:8080
    - Servidor: db
    - Usuário: root
    - Senha: mariadb
- Postgres:
    - Usuário: root
    - Senha: postgres