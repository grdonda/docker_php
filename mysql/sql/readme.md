## MySQL/SQL
Esta pasta deverá conter todoas as instruções SQL para ser executada dentro da maquina virtual/container docker
uma vez que está mapeada nos volumes para que possa ser gerida externamente e internamente

### Acessando o bash da maquina
```Shell
$ docker exec -it mysql bash
```

> Ao executar o comando acima, o acesso será concecido na raiz da maquina, na pasta  
configurada no docker-compose.yaml como `working_dir: /app/sql`  
