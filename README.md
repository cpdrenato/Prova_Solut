# Prova Soluti - pleno
### Zend framework 2
### apigility-doctrine-PHPSECLIB
### "requisitos obrigatórios"
### Installation
Install the dependencies and devDependencies and start the server.
- composer 
https://getcomposer.org/download/
- 1º API de Certificados
```sh
$ 1º API de Certificados
$ zf-apigility - vendor vai phpseclib - e doctrine.
$ projeto rb-sphinx-hmac-zf2 - nao terminei a implementacao. 
```
- 2º FRONTEND 
```sh
$ 2º FRONTEND
$ zf2-front
$ MySQL como RDBMS
```
```sh
$ SQL para criar a tabela:
CREATE TABLE `certificados` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `nome` varchar(255) NOT NULL,
  `certificado` TEXT NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB;
```
- ***************************
- Deverá ser desenvolvida com
- https://getcomposer.org/
- https://apigility.org/
- https://github.com/zendframework/ZendSkeletonApplication
- https://github.com/reinaldoborges/
- https://github.com/phpseclib/phpseclib
- http://phpseclib.sourceforge.net/
```sh
$ php -S 127.0.0.1:8000 -t public/ public/index.php
```

<p align="center"><img src="apigility.png"></p>
<br>
<p align="center"><img src="front end zend.png"></p>
<br>
<p align="center"><img src="zend hmac.png"></p>

> Agora e so desenvolver,
> Nos requisitos usei ubuntu 16.04 lts.
> Os programas sao faceis de instalar, mas,
> por falta de conhecimento dos frameworks mais aprofundado, nao consegui implementar.
>cpdrenato@gmail.com, 
>Grande abraço e até a próxima.

- Exemplo: https://github.com/reinaldoborges/rb-sphinx-hmac-zf2-examples-server


- Renato Lucena  - Outubro de 2017


