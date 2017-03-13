---
layout: post
title:  "Linux Essentials #1 - A Evolução do Linux e suas Distribuições mais Populares"
---

![gnu-linux](https://cloud.githubusercontent.com/assets/12460407/23873522/1b18ea6c-0811-11e7-9dfa-8abb0074f209.png)

*Este conteúdo tem Peso 2 no exame de certificação Linux Essentials, produzido pelo LPI (Linux Professional Institute).*

## O Projeto GNU

Em 1971, quando Richard Stallman começou sua carreira no MIT, trabalhava em um grupo que usava exclusivamente software livre. Até mesmo empresas de informática frequentemente distribuíam software livre. Programadores eram livres para cooperar uns com os outros, e frequentemente o faziam. Já na década de 1980, quase todo o software era proprietário, o que significa que ele possuía donos que proibiam e evitavam a cooperação dos usuários. Isso tornou o Projeto GNU necessário.

Por volta de 1990 estavam escritos praticamente todos os componentes principais, exceto um — o kernel. Então o Linux, um kernel do tipo Unix, foi desenvolvido por Linus Torvalds em 1991 e transformado em software livre em 1992. Combinar o Linux com o quase completo sistema GNU resultou num sistema operacional completo: o sistema GNU/Linux.

> “O objetivo derradeiro é prover software livre para fazer tudo aquilo que os usuários de computadores desejam fazer — e assim tornar o software proprietário algo do passado.”

## Código Aberto

Código aberto, ou **open source** em inglês, é um modelo de desenvolvimento que promove um licenciamento livre para o design ou esquematização de um produto, e a redistribuição universal desse design ou esquema, dando a possibilidade para que qualquer um consulte, examine ou modifique o produto.

## As Distribuições do Linux

Uma Distribuição Linux (ou simplesmente distro) é um sistema operacional baseado no Linux, e que inclui também um conjunto de software varíavel, um sistema gestor de pacotes e um repositório. Numa típica distribuição Linux, a maior parte do software é livre e de código aberto, estando disponível na forma de pacotes compilados previamente (binários), e de código-fonte.

Estão inclusas entre as distribuições Linux mais famosas:

* Debian
* Red Hat
* Ubuntu
* Fedora
* Linux Mint
* OpenSUSE

## Gerenciadores de Pacotes

Basicamente, um **gerenciador de pacotes** é uma coleção de ferramentas que oferece um método automático para instalar, atualizar, configurar e remover pacotes do sistema operacional. Cada tipo de distribuição conta um sistema gerenciador para dar suporte às suas aplicações e ao seu uso.

Veja a tabela abaixo:

| Distribuições baseadas em Red Hat                           | Distribuições baseadas em Debian                                |
|-------------------------------------------------------------|-----------------------------------------------------------------|
| Arquivos RPM                                                | Arquivos DEB                                                    |
| Repositórios YUM                                            | Repositórios APT                                                |
| Atualização de pacotes com "yum makecache"                  | Atualização de pacotes com "apt-get update"                     |
| Instalação e/ou remoção de pacotes com "yum install/remove" | Instalação e/ou remoção de pacotes com "apt-get install/remove" |
| Busca de pacotes com "yum search"                           | Busca de pacotes com "apt-get search"                           |

## Sistemas Embarcados

Chamamos de sistema embarcado a todo aquele que atende a requisitos específicos. Alguns exemplos são: Roteadores, celulares, smartphones, etc. É necessário um conjunto de mudanças no kernel Linux de forma que este atenda aos requisitos do sistema.

> [Rafael Alves](https://www.facebook.com/rafael.s.finha) é estagiário de Redes da GigaCom. Atualmente estuda tecnologias Mikrotik e Linux.




