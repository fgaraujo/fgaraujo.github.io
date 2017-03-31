---
layout: post
title: "Linux Essentials #5 - Começando a trabalhar com o Shell do Linux"
---

*Este conteúdo tem Peso 3 no exame de certificação Linux Essentials, produzido pelo LPI (Linux Professional Institute)*

## O Básico

Quando falamos de Sistemas GNU/Linux, a primeira coisa que vem à nossa mente é a "linha de comando", especialmente em servidores. Trata-se do **Shell** do sistema, que é responsável pela interação entre o usuário e a máquina através de comandos responsáveis pela execução das ações requeridas.

Temos como principais indicadores de prompt os dois abaixo:

```$``` - Usuário comum

```#``` - Usuário raiz (root)

## O Usuário Root

Para a segurança do sistema contra ações maliciosas ou mesmo dos próprios usuários do sistema, todos os arquivos tem seu “dono”, e este é capaz de interferir somente em seus arquivos. Entretanto, o usuário root pode realizar todas e quaisquer ações no sistema, até mesmo em arquivos em que não lhe pertencem.

## Tipos de Shell

O shell faz o "meio campo" entre o usuário e os recursos do computador. Em diversas distribuições dos Sistemas GNU/Llinux, o Shell padrão é o **BASH - BOURNE AGAIN SHELL**. Além dos programas presentes no computador, existem programas embutidos no shell tais como o ***echo***, utilizado para enviar texto para a saída padrão do sistema (Neste caso, na tela).

```
$ echo Linux Student
Linux Student
```

## Variáveis de Ambiente

Variáveis são “expressões” que guardam valores, dados e informações usadas pelos programas e pelo shell. Elas são alfanuméricas, porém, devem sempre começar com letras. Variáveis criadas pelo sistema estão presentes em caixa alta.

Existem dois tipos de váriáveis de ambiente:

* **Variável Local**: Existe somente na sessão atual do Shell.
* **Variável Global**: Existe para todo o sistema e/ou várias sessões do Shell, tais como:
    * **$HISTFILE** – Contêm o histórico de comandos.
    * **$PATH** - Contém localização de comandos.

Como poderíamos criar estas variáveis? Façamos um breve exemplo. Primeiro, criaremos uma variável de escopo local.

```
eu = ”Linux Essentials Certified 2017”
```

Podemos visualizar o conteúdo desta variável, com a utilização do comando *echo*:

```
echo $eu
```

E se quiséssemos transformar esta variável, passando-a do escopo local para o global? Faremos uso do comando *export*:

```
export eu
```

Finalmente, para remover a variável do sistema, utilizaremos o comando *unset*:

```
unset eu
```

> [Rafael Alves](https://www.facebook.com/rafael.s.finha) é estagiário de Redes da GigaCom. Possui as Certificações Cisco CCENT e LPI Linux Essentials.




