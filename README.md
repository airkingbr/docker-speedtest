[![N|Solid](http://www.nexthop.net.br/static/images/logo.png)](http://www.nexthop.net.br)

# NextHop Servidor Ookla - SpeedTest

Container Docker para servidor do speedtest.net


A imagem por padrão, binda a porta 8080 no host do container.

Certifique-se que ela está liberada.

### Criando e inicializando o container:

```sh
$ docker run -dit --restart always --name nexthop-speedtest -d -p 8080:8080 nexthopsolutions/docker-speedtest
```

Para verificar o status:

```sh
$ docker ps
```
 
Dúvidas ou informações: <elizandro@nexthop.net.br>
