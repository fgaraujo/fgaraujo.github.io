---
layout: post
title: "Linux Essentials #2 - As Principais Aplicações Open Source"
---

*Este conteúdo tem Peso 2 no exame de certificação Linux Essentials, produzido pelo LPI (Linux Professional Institute)*

## Suíte de Escritório

Denominamos por **suíte de escritório** ao conjunto integrado de aplicações voltadas para as tarefas de escritório, tais como editores de texto, editores de planilhas, editores de apresentação, aplicativos, agenda de compromissos, contatos, entre outros. Visam a dinamizar as tarefas do dia-a-dia de um escritório. A maior parte das distribuições Linux utiliza o **LibreOffice** como esta solução, tendo em vista que a proposta de licenciamento desta suíte está alinhada com as propostas de desenvolvimento do próprio Linux.

O LibreOffice surgiu como uma ramificação do projeto original OpenOffice.org que, por sua vez, é oriundo do StarOffice 5.1, adquirido pela Sun Microsystems com a compra da Star Division em agosto de 1999. O código fonte da suíte foi liberado para que fosse possível a participação de contribuintes para desenvolvê-lo, dando início ao projeto de desenvolvimento de um software de código aberto em 13 de outubro de 2000, o OpenOffice.org. O principal objetivo era fornecer uma alternativa de baixo custo, de alta qualidade e de código aberto.

Estão incluídas como as principais soluções desta suíte:

### Base

![libreoffice-base](https://upload.wikimedia.org/wikipedia/commons/thumb/9/92/LibreOffice_4.0_Base_Icon.svg/256px-LibreOffice_4.0_Base_Icon.svg.png)

O LibreOffice Base é um gerenciador de banco de dados, semelhante ao Access, disponível no Microsoft Office, e destina-se à criação e gerenciamento de bancos de dados, tendo suporte para a criação e modificação de tabelas, consultas, macros, relatórios e formulários.

### Calc

![libreoffice-calc](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6a/LibreOffice_4.0_Calc_Icon.svg/256px-LibreOffice_4.0_Calc_Icon.svg.png)

O LibreOffice Calc é um programa de planilha eletrônica e assemelha-se ao Lotus 1-2-3, da IBM, e ao Excel, da Microsoft. O Calc é destinado à criação de planilhas e tabelas, permitindo ao usuário a inserção de equações matemáticas e auxiliando na elaboração de gráficos de acordo com os dados presentes na planilha.

O Calc utiliza o formato ODF como padrão, embora reconheça e exporte arquivos em formatos de outras planilhas eletrônicas, além de exportar arquivos em PDF sem a necessidade de instalação de uma extensão, assim como todos os aplicativos da suíte LibreOffice.

### Writer

![libreoffice-calc](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e6/LibreOffice_4.0_Writer_Icon.svg/256px-LibreOffice_4.0_Writer_Icon.svg.png)

O LibreOffice Writer é o processador de textos da suíte, semelhante ao Word, presente na suíte de escritório Microsoft Office. Assim como os demais programas semelhantes, utiliza o sistema WYSIWYG para a elaboração de textos complexos, com imagens e diversas opções de formatação.

O Writer pode ser utilizado para escrever textos curtos, como cartas e memorandos, textos longos, com imagens e gráficos, e até livros. O aplicativo também é um editor de HTML, sendo possível criar hiperligações e inserir outras características presentes nesse tipo de arquivo, embora essas características também possam ser mantidas ao salvar em outros formatos.

## Aplicações Web

Denominamos como **aplicação web** a todo sistema computacional projetado para utilização através de um navegador, através da internet ou aplicativos desenvolvidos utilizando tecnologias web HTML, JavaScript e CSS. Pode ser executado a partir de um servidor HTTP ou localmente, no dispositivo do usuário.

Uma aplicação web também é definida em tudo que se é processado em algum servidor. Quando você entra em um e-commerce, a página que você acessa antes de vir até seu navegador é processada em um computador ligado a internet, que retorna o processamento das regras de negócio nele contido. Por isso chama-se aplicação, e não simplesmente site web.

Entre as aplicações Web mais conhecidas no Linux, estão:

### Mozilla Firefox

![mozilla-firefox](https://upload.wikimedia.org/wikipedia/commons/thumb/7/76/Mozilla_Firefox_logo_2013.svg/352px-Mozilla_Firefox_logo_2013.svg.png)

Mozilla Firefox é um navegador livre e multi-plataforma desenvolvido pela Mozilla Foundation com ajuda de centenas de colaboradores. A intenção da fundação é desenvolver um navegador leve, seguro, intuitivo e altamente extensível.

### Apache HTTP Server

![apache-server](https://upload.wikimedia.org/wikipedia/commons/4/45/Apache_HTTP_server_logo_%282016%29.png)

O Apache HTTP Server é o servidor web livre mais utilizado do mundo. Em maio de 2010, serviu aproximadamente 54,68% de todos os sites e mais de 66% dos milhões de sites mais movimentados. É a principal tecnologia da Apache Software Foundation, responsável por mais de uma dezena de projetos envolvendo tecnologias de transmissão via web, processamento de dados e execução de aplicativos distribuídos.

## Software Multimídia

![blender](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0c/Blender_logo_no_text.svg/294px-Blender_logo_no_text.svg.png)

Denominamos por software multimídia os softwares de edição, criação e execução de áudio, vídeo e imagens. Temos como principais representes desta categoria de aplicação em Linux:

* Blender: Criação e animação 3D.
* Gimp: Criação e edição de imagens, alternativo ao Photoshop.
* Inkscape: Editor de imagens vetoriais.
* Audacity: Edição de áudio.
* Imagemagick: Conversor e editor de imagens.

## Compartilhamento de Arquivos

![samba-server](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f9/Samba.png/640px-Samba.png)

Em redes do tipo cliente/servidor, também é possível o compartilhamento de arquivos tais como ficheiros USB e cópias em CD/DVD. Porém, para compartilhamento em disco é necessário o uso de mecanismos para tal. Entre sistemas Linux o compartilhamento é feito através do NFS ( Network File System), e em ambientes misto como Linux e Windows utiliza-se o **Samba File Server**.

## Linguagens de Programação

![linguagens-programacao](https://upload.wikimedia.org/wikipedia/commons/0/0d/Prog-languages.png)

Todos os programas, aplicativos e o próprio sistema operacional são criados através de linguagens de programação. Existem diversas linguagens de programação, e um ponto forte do Linux é oferecer suporte para programas e desenvolvimento de software em diversas linguagens.

Existem dois tipos principais de linguagens de programação:

### Linguagens Interpretadas

Linguagem interpretada é uma linguagem de programação em que o código fonte nessa linguagem é executado por um programa de computador chamado interpretador, que em seguida é executado pelo sistema operacional ou processador. Mesmo que um código em uma linguagem passe pelo processo de compilação, a linguagem pode ser considerada interpretada se o programa resultante não for executado diretamente pelo sistema operacional ou processador. 

### Linguagens Compiladas

Linguagem compilada é uma linguagem de programação em que o código fonte nessa linguagem é executado diretamente pelo sistema operacional ou pelo processador, após ser traduzido por meio de um processo chamado compilação, usando um programa de computador chamado compilador para uma linguagem de baixo nível, como linguagem de montagem ou código de máquina.

### LAMP

Chamamos de LAMP a uma pilha de serviços web nomeada como uma sigla dos nomes originais de seus componentes de software livre: O sistema operacional **Linux**, o servidor Web **Apache**, o banco de dados **MySQL** e a linguagem de programação **PHP**. Estes componentes não estão restritos aos citados, podendo ser substituídos por soluções livres equivalentes. Como uma pilha de soluções, o LAMP é fornecido para a construção de sites dinâmicos e aplicações web. 

> [Rafael Alves](https://www.facebook.com/rafael.s.finha) é estagiário de Redes da GigaCom. Possui as Certificações Cisco CCENT e LPI Linux Essentials.




