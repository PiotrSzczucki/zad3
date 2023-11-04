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



## Wstęp

Gruzja jest moim ulubionym krajem. Ten mało znany kraj jest zaskakująco bogaty w piękne zabytki, widoki i inne atrakcje. **To czyni go jedną z najlepszych destynacji na wakacje w Europie.**

Gruzja jest świetnym miejscem dla miłośników zabytków. Możemy tam znaleźć mnóstwo pozostałości dawnego ZSRR, jak i prastare budowle z epoki bronzu. Miasta Gruzji mają swój własny, unikatowy styl, którego nie znajdziemy nigdzie indziej na świecie. Bardzo kolorowe ceglane budynki ze zdobionymi,  drewnianymi balkonami wyglądają jak połączenie architektury Kuby i Włoch. W całym kraju możemy też znaleźć bardzo charakerystyczne kamienne wieże, które były używane do obrony przed najeźdźcami.

Atrakcje Gruzji

Oto lista najciekwszych atrakcji Gruzji:

* Kanion Martvili - spływ kajakowy pośród skał 
* Vardzia - miasto wykute w skalnym klifie
* Klasztor Katskhi - świątynia na słupie skalnym
* Tbilisi - kolorowa stolica Gruzji
* Mestia - górska wioska pełna kamiennych wież
* Uplistsikhe - rozległe ruiny skalnego miasta
* Cminda Sameba - piękny kościół na szczycie góry
* Zamek Chertwisi - ponure ruiny twierdzy na skale

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
