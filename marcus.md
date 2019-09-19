Criaçã do Ambiente de Testes Automatizado 
2
## Instalação java  

Versão  java 1.8.xxx
JRE
JDK

Definir o JAVA_HOME 

## Instalando o JRE / JDK Padrão

atualizar lista de pacotes
```shell
sudo apt-get update
```
Instalar JRE
```shell
sudo apt-get install default-jre
```


## Instalando o Open JDK
```shell
*$* sudo apt-get install openjdk-8-jdke
```
verifique a versão do java 
```shell
*$* javac -version
```
A saida deve ser.
```shell
javac 1.8.0_222
```
verifique a versão do java 
```shell
*$* java -version
```
A saida deve ser.
```shell
openjdk version "1.8.0_222"
OpenJDK Runtime Environment (build 1.8.0_222-8u222-b10-1~deb9u1-b10)
OpenJDK 64-Bit Server VM (build 25.222-b10, mixed mode)

```



Depois que fizermos isso, precisaremos atualizar:

```
sudo apt-get update
```



## Instalando o Mongo Db V.4**

Importe a chave pública usada pelo sistema de gerenciamento de pacotes. 
```shell
wget -qO - https://www.mongodb.org/static/pgp/server-4.2.asc | sudo apt-key add -
```
A operação deve responder com um.
```shell
ok
```
Crie um /etc/apt/sources.list.d/mongodb-org-4.2.listarquivo para o MongoDB.
```shell
echo  "deb http://repo.mongodb.org/apt/debian stretch / mongodb-org / 4.2 principal"  | sudo tee /etc/apt/sources.list.d/mongodb-org-4.2.list
```
Verifique se o arquivo foi criado 
```shell
more /etc/apt/sources.list.d/mongodb-org-4.2.list
```
O conteudo do arquivo deve ser

```shell
deb http://repo.mongodb.org/apt/debian stretch / mongodb-org / 4.2 principal
```
Recarregue o banco de dados do pacote local.
```shell
sudo apt-get update
```

Instale os pacotes do MongoDB. 
```shell
sudo apt-get install -y mongodb-org = 4 .2.0 mongodb-org-server = 4 .2.0 mongodb-org-shell = 4 .2.0 mongodb-org-mongos = 4 .2.0 mongodb-org-tools = 4 .2.0
```

ngix 
## Instalando 
npm / node


ionic
