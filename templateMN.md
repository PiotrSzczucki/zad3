---
author: Piotr Szczucki
title: Gruzja
subtitle: Mój ulubiony kraj
date: 04.11.2023
theme: Warsaw
output: beamer_presentation
header-includes: 
    \usepackage{xcolor}
    \usepackage{listings}
---



## Slajd nr 1 

Przykładowy akapit tekstu - Pellentesque et sollicitudin velit. Proin eu euismod magna. Duis sapien nibh, posuere vel iaculis quis, laoreet in eros. Vestibulum sit amet aliquam turpis. Suspendisse at tincidunt est, eget placerat sem. 

Drugi Akapit - Aliquam nec turpis id arcu porttitor dapibus. Nam sagittis nunc magna, eget tristique leo luctus sed. Quisque a lacus vel est elementum accumsan ut in urna. Etiam congue mollis velit, in venenatis est imperdiet vitae.

**Tekst pogrubiony**

*Tekst pochylony*
<!--- Kolorowanie tekstu wymaga użycia komend Latexa -->
\textcolor{red}{Text Czerwony}, \textcolor{blue}{Tekst Niebieski}
<!--- Centrowanie wymaga użycia komend Latexa -->

\begin{center}Tekst wycentrowany \end{center}


## Slajd nr 2 - listy

Lista numerowana:
<!--- UWAGA WAŻNE pusta linia odstępu -->

1. Pierwszy
2. Drugi
3. Trzeci

Lista punktowana:

* Pierwszy 
* Drugi 
* Trzeci

Lista podrzędna:

* Pierwszy
    * Pierwszy wcięty
        * Kolejne wcięcie 

- ii
- ii

## Slajd 3 - bloki

### blok z tytułem
Przykładowa zawartość bloku z belką tytułową.

Druga linia bloku

###
Wyróżnienie - blok bez belki tytułowej

###
Wyróżnienie - kolejny blok bez belki tytułowej

<!--- Niestety pomiędzy tak zdefiniowanymi  blokami nie można umieszczać innych elementów-->

## Slajd 4 - bloki z Latexa

\begin{alertblock}{Uwaga:}
Tu jakiś tekst
\end{alertblock}

Tu jakiś tekst można teraz umieścić

\begin{block}{Jakiś tytuł}
Kolejny blok
\end{block}

\begin{exampleblock}{Przykładzik}
Jakiś kawałek przykładu
\end{exampleblock}

## Slajd 5 - umieszczanie kodu źródłowego

Python code:
```python
s = 2
print s
```
C code:

```c
#include<stdio.h>
int main(void)
{
    printf("Hello\n");
    return 0;
}
```


## Slajd 6 - obrazek

![](example.jpg){ height=50% width=50%}

## Slajg 7 - obrazek wycentrowany z podpisem

![&nbsp; Example 1](example.jpg){ height=50% width=50%}

## Slajd 8 - tabele

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

<!--- W kodzie można dowolnie używać Latexa -->

## Slajd 9 - wzory

<!--- wzory wstawiamy bezpośrednio jako jod Latex -->

Tu jest tekst ze wzorem: $c=\sqrt{a^2+b^2}$

A tu wzór pod tekstem: $$c=\sqrt{a^2+b^2}$$
