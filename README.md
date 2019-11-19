# Guia Lazarus

Esse é um guia para orientar a todos aqueles que estão começando a desenvolver utilizando o Lazarus e também **muito útil para aqueles que estão vindo do Delphi**. Esse guia são para as pessoas que já possem conhecimento técnico na área programação e não visa ensinar sintaxe ou lógica de programação (pelo não por enquanto).

# Índice

- [O que é, o que é?](#O-que-&eacute;-o-que-&eacute;)
  * [O que é Lazarus?](#O-que-&eacute;-Lazarus)
  * [O que é FPC?](#O-que-&eacute;-FPC)
  * [Esclarecimentos](#Esclarecimentos)
- [Por que utilizar o Lazarus?](#Por-que-utilizar-o-Lazarus)
  * [É barato](#&Eacute;-barato)
  * [É rápido, simples e prático](#&Eacute;-r&aacute;pido-simples-e-pr&aacute;tico)
  * [É multiplataforma](#&Eacute;-multiplataforma)
  * [Dependências](#Depend&ecirc;ncias)
  * [Por que não utilizar o Lazarus?](#Por-que-n&atilde;o-utilizar-o-Lazarus)
- [Instalação](#Instala&ccedil;&atilde;o)
  * [Para os conservadores](#Para-os-conservadores)
  * [Para os ousados](#Para-os-ousados)
  * [Para os malucos](#Para-os-malucos)

# O que é, o que é?

## O que é Lazarus?
**Lazarus** é uma ferramenta, uma IDE com a finalidade de agilizar o desenvolvimento e produção do **FPC**. 

## O que é FPC?
**FPC**, Free Pascal Compiler é o compilador pascal. Ele que interpreta e compila nosso código escrito em pascal.

## Esclarecimentos
É perfeitamente possível utilizar o FPC sem o Lazarus, basta utilizar a linha de comando e você compilará normalmente. É perfeitamente possível utilizar o Lazarus sem o FPC, você conseguirá editar seus projetos, mas não conseguirá compilar. 

Para todos os efeitos, quando utilizarmos nesse guia o termo **Lazarus**, estaremos nos referindo a todo o ecossistema de desenvolvimento, ou seja, Lazarus+FPC. Ok?

# Por que utilizar o Lazarus?

## É barato
Na verdade não é barato, é de graça. O Lazarus é gratuito e open-source. Para ficar mais claro: você não precisa comprar licença alguma para desenvolver e vender/alugar seus projetos. Você não precisa vender seu rim ou sua córnea para comprar uma licença. Basta instalar e usar.

## É rápido, simples e prático
É uma linguagem relativamente fácil e simples de aprender.

## É multiplataforma
O Lazarus suporta algumas tantas arquiteturas: AArch64, AMD64/x86-64, ARM, AVR, ECMASsript, i386, i8086, Intel i486, Intel x86, JVM, m68K, MIPS, mipsel, PowerPC, PowerPC64, SPARC, x86_64.

E alguns sistemas operacionais: AIX, Amiga, Android (32 e 64 bit), BeOS, Darwin, DOS (16 e 32 bit), emx, FreeBSD, Go32v2, Haiku, iOS, iPhoneSim, Linux, Mac OS, MorphOS, Motorola 68k, MSDOS, NDS, NetBSD, Netware, NetwLibC, Nintendo DS, Nintendo GBA, Nintendo Wii, OpenBSD, OS/2, PalmOs, QNX, Solaris, Symbian, Watcom, wdox, Wii, Win32, Win64, WinCE.

Da pro gasto né? Ainda mais se levar em consideração que a maior parte dos sistemas são direcionados para o windows, linux, mac e android...

## Dependências
Nenhuma. Você não precisa levar framework algum, tampouco instalar SDK ou bibliotecas externas, a não ser é claro, que você opte por isso, como por exemplo, bibliotecas de algum hardware especifico, ou componentes específicos.

## Por que não utilizar o Lazarus?
Preguiça.

# Instalação

Futuramente teremos uma sessão detalhando cada um desses métodos.

## Para os conservadores
Basta acessar a [página oficial](https://freepascal.org/download.html), escolher seu ambiente, baixar e instalar.

## Para os ousados
Basta acessar os repositórios:
[Repositório do FPC](https://svn.freepascal.org/svn/fpc/trunk)
[Repositório do Lazarus](https://svn.freepascal.org/svn/lazarus/trunk)
Baixar, compilar e ser feliz.

## Para os malucos
Basta acessar a [página do fpcupdeluxe](https://github.com/LongDirtyAnimAlf/fpcupdeluxe), encontrar o binário adequado e instalar.