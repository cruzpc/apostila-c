---
title: Apostila de Linguagem C
author: Gabriel Cruz
date: 01 de Agosto de 2020
abstract: Uma apostila de linguagem C sem frescura! Destinada a quem já tem uma base de programação.
---

# O básico

Esse capítulo vai ser sobre o básico: variáveis, sintaxe, controle de fluxo, loops, switch case.

## O primeiro programa em C

Escrever isso:


```
#include <stdio.h>

void main ()
{
	/*O comando a seguir imprime no terminal*/
	printf ("Hello World!\n");
}
```
Use seu editor de texto favorito...

Para compilar:

$ gcc main.c -o main

Para rodar:

./main

## Variáveis básicas

Para declarar variáveis, basta:

```
int a;
float b;

a = 5;
b = 5.6;

printf("O resultado de %d e %f é %f!\n", a, b, a+b);
```
## Condições e Comparações

### If Else

```
include <stdio.h>

void main ()
{
	int a = 0;

	if (a == 0)
	{
		printf ("a é igual a 0\n");
	}

	else
	{
		printf ("a não é igual 0\n ");
	}
}
```

### For Loop




# Ponteiros


# Funções


# Arrays e Strings


# User Input


# Arquivos


# Mais alguns tipos e variáveis


# Header e Pré-Processador


# GTK


# Botões em GTK


# Layouts e Labels


# Layouts Avançados


# GUI input


# Tree View


# Menus


# Diálogos


# Widgets Customizados


# Referência
