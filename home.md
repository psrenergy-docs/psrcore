---
layout: default
title: Home
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---

## Welcome to PSRIO

PSRIO is a scripting language develop on top of LUA designed for:
1. Querying data held in PSR databases (inputs and outputs)
2. Perform several user-specified mathematical, statistical and data processing operations
3. Produce new customized outputs in the same format as the SDDP outputs, that can be processed by the plotting tool

The main objective of this tool is to automate and standardize everyday operations by delegating tasks to an easy-to-use and secure language, avoiding manual errors and repeated work.

Additionally, PSRIO also enables the direct creation of dashboards.

### What is a Scripting Language?

- Dynamic typing, structures, and binding (vs static)
- Flexibility (vs robustness)
- Programmer efficiency (vs computer efficiency)
- Interpreted (vs compiled)
- Faster cycle “edit-run-test”
- Automatic memory management
- Avoids several common bugs (overflows)
- Interface to other languages/programs

### Why Scripting?

- No language is optimal for everything
- Programming languages are complex engineering projects
- Extend your application beyond compile time (“glue language”):
  - System language implements the hard parts (components change little)
  - Scripting language connects those parts (final applications change much)
- Quick-and-dirt programming (exploratory and rapid prototyping)
- Friendliness and easiness to end-user programming
- Examples: Shell/Bash in Unix, NumPy in Python

### LUA

<div style="text-align:center">
    <img src="images/lua.svg" width="160"/>
</div>

- A scripting language designed by Roberto Ierusalimschy, Luiz H. de Figueiredo, and Waldemar Celes at Tecgraf/PUC-Rio
- "The simplest thing that could possibly work"
- Simple, yet powerful, language for embedding and extending applications
- Portable and small, written in ANSI C, easy to integrate with C/C++
- TIOBE Index for March 2021:
  - 1st C; 2nd Java; 3rd Python; 4th C++; 5th C#; 7th JavaScript; 22nd Fortran; 34th Julia; **38th Lua**
- Widely used in Triple-A games and small devices (embedded systems and IoT)

### Scripting + LUA + PSR = PSRIO

- Treating code as data: every time you build a query, you're treating code as data
- C++ code implements the complex and stable parts:
  - Data reading and processing, relationships, data structures, unit converting, and dashboarding
- Lua connects those parts: flexible, easy to change

### Support or Contact

Having trouble with PSRIO? Contact our support team via `sddp@psr-inc.com` and we’ll help you sort it out.


 <!-- O processamento de dados de entrada e saída é uma etapa fundamental para a compreensão dos resultados, elaboração de estudos e encadeamento com outros modelos. As ferramentas tradicionalmente utilizadas como o Excel ou rotinas feitas sob medida para o processamento de arquivos específicos, além de trabalhosas, repetitivas e sujeitas a erro, possuem limitações relacionadas a escalabilidade devido ao aumento no volume de resultados originado da maior complexidade e detalhamento na representação dos modelos.
Para complementar o conjunto de ferramentas da PSR, foi desenvolvido o PSRIO. Ele é um interpretador de scripts Lua que permite manipular bases de dados da PSR (entrada e resultados) e realizar todas as operações matemáticas e cálculos de estatísticas necessários de forma rápida, customizável e extremamente amigável. Operações como a soma de agentes, média dos cenários, cálculo de percentis, conversão de unidades e diversas outras podem ser realizadas em menos poucas linhas de script, sem a preocupação com fórmulas ou programação de loops para leitura, processamento e escrita de arquivos. Os resultados são salvos no formato padrão e podem ser utilizados pelo graficador, para criação de dashboards, no Excel, diretamente em relatórios ou até mesmo como dado de entrada para outro modelo.
O PSRIO já está integrado aos principais modelos e interfaces da PSR, o que permite gerar resultados customizados automaticamente após a execução dos modelos no computador local ou no PSRCloud.
A apresentação será na tarde desta terça feira com discussão de exemplos e aplicações. Contamos com a sua presença! -->