## Projeto docker web sites com suporte ao PHP
----
Este projeto nasceu para que fosse possivel eu administrar alguns sites de amigos que usa PHP para algumas finalidades


<br>
<br>

### Especificações
----
Este projeto conta com Nginx para processar arquivos PHP, container **PHP-FPM** para processar os arquivos PHP quando necessários, **MySQL** para que os arquivos dos projetos em PHP possam acessar a base de dados para testes e o PhpMyAdmin para gerenciar a base de dados se necessário.


Comando para rodar na raiz do projeto sempre que desejar iniciar o projeto, atualizar as configurações etc.

```Shell
$ docker compose -f "docker-compose.yaml" up -d --build --remove-orphans
```

<br>
<br>


## Requisitos
---
### **Docker**

1. Ter o Docker desktop instalado.
2. Ter algum terminal para rodar o docker-compose.yaml

ou pode usar uma extensão do VSCode para gerenciar o Docker que também permitirá rodar o docker-compose.yaml.

<br>

### **Colima**
Em breve.

<br>
<br>

## Outros projetos
---
Caso queira somente o MySQL para brincar com comandos e bases de dados, tabelas e etc.: existe no repositorio dos meus projetos em docker uma versão exclusiva do MySQL para essa finalidade.   
<br>
visite: <a href="https://github.com/grdonda/docker" target="_blank">github.com/grdonda/docker</a>
