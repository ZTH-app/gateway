# Gateway ZTH-app

Gateway permettant de relier les microservices : 
- MS-user, 
- MS-course, 
- MS-chapter

### Clone du dépôt

```bash
$ git clone https://github.com/ZTH-app/gateway.git
$ cd gateway
```


### Execution du projet

```bash
$ npm install
$ npm start
```


Par défaut, le serveur s'executera sur `http://localhost:80` 

### Configuration

Pour toutes modifications de la configation de la gateway

```
$ cd ./config/gateway.config.yml
```

### Accèder aux différents services

Accès au MS-user :
`http://localhost:80/user`

Accès au MS-course :
`http://localhost:80/course`

Accès au MS-chapter :
`http://localhost:80/chapter`

