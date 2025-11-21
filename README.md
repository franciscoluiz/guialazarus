# Guia Lazarus

Esse é um guia para orientar a todos aqueles que estão começando a desenvolver utilizando o Lazarus e também **muito útil para aqueles que estão vindo do Delphi**. Esse guia são para as pessoas que já possuem conhecimento técnico na área programação e não visa ensinar sintaxe ou lógica de programação (pelo menos não por enquanto).  

Com a devida dedicação, qualquer um pode se tornar um **lazarento**!

# Índice

- [O que é, o que é?](#O-que-&eacute;-o-que-&eacute;)
  * [O que é Lazarus?](#O-que-&eacute;-Lazarus)
  * [O que é FPC?](#O-que-&eacute;-FPC)
  * [Esclarecimentos](#Esclarecimentos)
- [Por que utilizar o Lazarus?](#Por-que-utilizar-o-Lazarus)
  * [É barato](#&Eacute;-barato)
  * [É rápido, simples e prático](#&Eacute;-r&aacute;pido-simples-e-pr&aacute;tico)
  * [É multiplataforma](#&Eacute;-multiplataforma)
  * [Cross Compiling](#Cross-Compiling)
  * [Dependências](#Depend&ecirc;ncias)
  * [Por que não utilizar o Lazarus?](#Por-que-n&atilde;o-utilizar-o-Lazarus)
- [Instalação](#Instala&ccedil;&atilde;o)
  * [Para os conservadores](#Para-os-conservadores)
  * [Para os ousados](#Para-os-ousados)
  * [Para os malucos](#Para-os-malucos)
- [Links Uteis](#Links-Uteis)
  * [Grupos no telegram](#Grupos-no-telegram)
  * [Grupos no whatsapp](#Grupos-no-whatsapp)
  * [Grupos no google groups](#Grupos-no-google-groups)
  * [Canais no YouTube](#Canais)
  * [Portais](#Portais)
- [Componentes](#Componentes)
  * [Brazucas](#Brazucas)
  * [Geral](#Geral)
  
# O que é, o que é?

## O que é Lazarus?
**Lazarus** é uma ferramenta, uma IDE com a finalidade de agilizar o desenvolvimento e produção de projetos com o **FPC**.

## O que é FPC?
**FPC** ou Free Pascal Compiler é o compilador pascal. Ele que interpreta e compila nosso código escrito em pascal.

## Esclarecimentos
É perfeitamente possível utilizar o FPC sem o Lazarus, basta utilizar a linha de comando e você compilará normalmente. É perfeitamente possível utilizar o Lazarus sem o FPC, você conseguirá editar seus projetos, mas não conseguirá compilar.  

Para todos os efeitos, quando nesse guia utilizarmos o termo **Lazarus**, estaremos nos referindo a todo o ecossistema de desenvolvimento, ou seja, Lazarus+FPC. Ok?

# Por que utilizar o Lazarus?

## É barato
Na verdade não é barato, é de graça. O Lazarus é gratuito e open-source. Para ficar mais claro: você não precisa comprar licença alguma para desenvolver, vender ou alugar seus projetos. Não é necessário hipotecar sua casa para adquirir o direito de uso. Você não precisa vender seu rim ou sua córnea para comprar uma licença. Basta instalar e usar.  

Não use crack. Use software livre. Seja livre! Lazarus na veia!

## É rápido, simples e prático
É uma linguagem relativamente fácil e simples de aprender. A curva de aprendizado do pascal é relativamente simples. **Pascal é verboso e gostoso!**

## É multiplataforma
O Lazarus suporta algumas tantas arquiteturas: AArch64, AMD64/x86-64, ARM, AVR, ECMASsript, i386, i8086, Intel i486, Intel x86, JVM, m68K, MIPS, mipsel, PowerPC, PowerPC64, SPARC, x86_64.

E alguns sistemas operacionais: AIX, Amiga, Android (32 e 64 bit), BeOS, Darwin, DOS (16 e 32 bit), emx, FreeBSD, Go32v2, Haiku, iOS, iPhoneSim, Linux, Mac OS, MorphOS, Motorola 68k, MSDOS, NDS, NetBSD, Netware, NetwLibC, Nintendo DS, Nintendo GBA, Nintendo Wii, OpenBSD, OS/2, PalmOs, QNX, Solaris, Symbian, Watcom, wdox, Wii, Win32, Win64, WinCE.

Confesso que tem coisa aí em cima que não faço nem ideia do que é, mas da pro gasto né? Ainda mais se levar em consideração que a maior parte dos sistemas são direcionados para o windows, linux, mac e android.

## Cross Compiling
Sim! Você pode compilar seus executáveis windows estando no linux. Sim! Você pode compilar seus binários linux estando no windows. Você pode gerar seus projetos em seu ambiente favorito direto para o ambiente do cliente!

## Dependências
Nenhuma. Você não precisa levar framework algum, tampouco instalar SDK ou bibliotecas externas, a não ser é claro, que você opte por isso, como por exemplo, bibliotecas de algum hardware especifico ou componentes específicos.

## Por que não utilizar o Lazarus?
Falta de vontade, preguiça, morbosidade é que faz uma pessoa não usar o Lazarus.

# Instalação
Futuramente teremos uma sessão detalhando cada um desses métodos.

## Para os conservadores
O método **conservador** consiste na instalação convencional, é o famoso "next, next, next". Para tal proeza basta acessar a [página oficial (https://www.lazarus-ide.org)](https://www.lazarus-ide.org), escolher o setup para o seu ambiente, baixar e instalar. Aqui, a última versão estável do Lazarus e do FPC são instalados e configurados automaticamente.

## Para os ousados
O método **ousadia** é para os intrépidos que querem a versão mais recente ou que necessitam de versões específicas.

Para tal, é necessário um mínimo de conhecimento a respeito, posteriormente basta baixar os repositórios:  
[Repositório do FPC (https://svn.freepascal.org/svn/fpc/trunk)](https://svn.freepascal.org/svn/fpc/trunk)  
[Repositório do Lazarus (https://svn.freepascal.org/svn/lazarus/trunk)](https://svn.freepascal.org/svn/lazarus/trunk)  

Baixar, compilar, configurar e ser feliz.

## Para os malucos
Diga-se de passagem **maluco** pois você estará outorgando o trabalho da instalação do Lazarus, para programas de terceiros. Existem projetos que auxiliam a instalação, automatizando praticamente tudo, inclusive facilitando o processo de crosscompiling. Algumas pessoas acham esse processo inseguro, outras, acham maluquice (*me gusta*). 

Nesse segmento o projeto mais popular é o [**fpcupdeluxe**](https://github.com/LongDirtyAnimAlf/fpcupdeluxe).

# Links Uteis

## Grupos no telegram
[D2Bridge](http://t.me/d2bridge)  
[FreePascal & Lazarus](https://telegram.me/freepascal_en)  
[LazarusBR](https://telegram.me/LazarusBR)  
[Lazarus Brazil](https://telegram.me/lazarusbrazil)  
[Lazarus Free Pascal](https://telegram.me/lazarusfreepascal1)  
[Lazarus & Delphi - Brasil](https://telegram.me/LazBrasil)  
[Pascal BR](https://t.me/pascalbrasil)  
[REST Dataware](https://telegram.me/restdatawareoficial)  
[RestDataWare Oficial](https://telegram.me/restdatawareoficial)  
[Vagas Delphi / Lazarus](https://telegram.me/vagasdelphibr)  
[WBotCe](https://telegram.me/wbotce)  

## Grupos no whatsapp
[D2Bridge](https://chat.whatsapp.com/Jz8ditsGyzl79eSI5tL5Cq)  
[D2Bridge for Lazarus](https://chat.whatsapp.com/BlFAhfOZPny3GFSSH4LPxI)  
[Lazarus Brasil](https://chat.whatsapp.com/DwEvGFmQyB3J2jLcTJblTn)  
[WBotCe](https://chat.whatsapp.com/HpgvHZ0iSzs6Svc6wouGzH)  

## Grupos no google groups
[Lazarus-BR (Google Groups)](https://groups.google.com/forum/#!forum/lazarus-br)  

## Canais
[99 Coders](https://www.youtube.com/@99coders)  
[Adriano Lima](https://www.youtube.com/@AdrianoLima)  
[Alberto Brito](https://www.youtube.com/@albertobrito829)  
[Anderson Fiori](https://www.youtube.com/@andersonfiori7230)  
[Anderson Junior](https://www.youtube.com/@andersonjunior264)  
[Alexandre Magno](https://www.youtube.com/@Alexandre_amds)  
[Aprenda Lazarus com Pedro Araújo](https://www.youtube.com/@aprendalazarus)  
[Ari Rodrigues](https://www.youtube.com/@arirodrigues5929)  
[D2Bridge](https://www.youtube.com/@talisjonatas)  
[Daniel Morais Infocotidiano](https://www.youtube.com/@infocotidiano)  
[Daniel Steckler](https://www.youtube.com/@DanielSteckler)  
[Eder Telhado](https://www.youtube.com/@edertelhado8246)  
[Eduardo Damasceno](https://www.youtube.com/@eduardodamasceno2354)  
[Fabio Luis Girardi](https://www.youtube.com/@flgirardi)  
[Gilberto Rocha - REST Dataware](https://www.youtube.com/@XyberSportGames)  
[Gladiston Santana](https://www.youtube.com/@gladistonsantana)  
[Insist Informatica](https://www.youtube.com/@InsistInformatica)  
[Isaque Pinheiro](https://www.youtube.com/@IsaquePinheirooficialbr)  
[Jardel da Costa](https://www.youtube.com/@jardelfsc)  
[JR Escola](https://www.youtube.com/@jrescola8453)  
[Humberto Sales - Rumble](https://rumble.com/c/c-1389652)  
[Humberto Sales - CosTv](https://cos.tv/channel/37299284183262208)  
[Marcos Douglas](https://www.youtube.com/@mdbs99)  
[MarcosMissel](https://www.youtube.com/@MarcosMissel)  
[Melissa Treinamentos](https://www.youtube.com/@melissatreinamentos)  
[MfrInfo](https://www.youtube.com/@mfrinfo4273)  
[Palm Sistemas](https://www.youtube.com/@palmsistemas2820)  
[Rai Duarte](https://www.youtube.com/@raijales)  
[RSC SISTEMAS](https://www.youtube.com/@RSC_SISTEMAS)  
[Ricardo Sierban](https://www.youtube.com/@blogueirosamurai)  
[SchoolFreeware](https://www.youtube.com/@SchoolFreeware)  
[Sergio Falco Daniel](https://www.youtube.com/@sergiofalcodaniel9445)  
[TWtutoriais](https://www.youtube.com/@TWtutoriais)  
[Valtran Silva](https://www.youtube.com/@InfoGames554)  
[Vinicius Sanchez](https://www.youtube.com/@ViniciusSanchez)  
[Warleyalex](https://www.youtube.com/@warleyalexcamargo)

## Sites em geral
[Academia do Código](https://www.youtube.com/@AcademiadoCodigo)  
[Aprenda Lazarus](https://aprendalazarus.com.br)  
[Formation FreePascal/Lazarus](https://github.com/NDXDeveloper/formation-freepascal-lazarus-fondamentaux)  
[Lazarus IDE – Guia de Sobrevivência](https://gladiston.net.br/programacao/lazarus-ide/)  
[Laz Planet](https://lazplanet.blogspot.com)  
[Neri](https://www.youtube.com/@nerineitzke)  
[ShowDelphi](https://showdelphi.com.br)  
[T2Ti](https://www.youtube.com/@T2Ti)  

# Componentes

## Brazucas
[ACBr](https://projetoacbr.com.br)  
[D2Bridge](https://d2bridge.com.br)  
[Brook Framework](https://github.com/risoflora/brookframework)  
[Fortes-CE](https://github.com/fortesinformatica/fortesreport-ce)  
[Open Source Community Brasil](https://github.com/OpenSourceCommunityBrasil)  
[PascalLibs](https://github.com/OpenSourceCommunityBrasil/PascalLibs)  
[REST Dataware SourceForge](https://sourceforge.net/projects/rest-dataware-componentes)  
[REST Dataware GitHub](https://github.com/OpenSourceCommunityBrasil/REST-DataWare)  
[WBotCe](https://github.com/OpenSourceCommunityBrasil/WBotCE)  

## Geral
[Awesome-Pascal](https://awesomeopensource.com/project/Fr0sT-Brutal/awesome-pascal)  
[Awesome-Pascal Github](https://github.com/Fr0sT-Brutal/awesome-pascal)  
[Awesome-delphi](https://awesomeopensource.com/project/Fr0sT-Brutal/awesome-delphi)  
[mORMot](https://github.com/synopse/mORMot)  
[ZeosLib](https://sourceforge.net/projects/zeoslib)  





