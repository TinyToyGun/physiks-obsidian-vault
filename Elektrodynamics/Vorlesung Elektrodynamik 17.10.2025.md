### Gradient & Nabla Operator
>Def: $dU = \text{grad} \, U d \bar{r} = \bar{\nabla} U d \bar{r}$

Der Gradient kann nur von einem Skalar feld geformt werden, und ist wiederrum ein vektorfeld, welches in jedem Punkt die richtung des Grössten anstiegs gibt. Also wenn man dem Gradienten folgt, kommt man immer auf ein Lokales Maximum.
### Divergenz eines Vektorfeldes
>$\text{div} \, \bar{a} (\bar{r}) = \bar{\nabla} \bar{a}(\bar{r})$

Die Divergenz wird geformt durch skalar multiplikation des Nabla-operators mit einem Vektorfeld, und ist wiederrum ein Skalarfeld, welches zeigt sozusagen die quellen eines Vektorfeldes.
Quellenfeld von $\bar{a}(\bar{r})$. Es zeigt wo die quellen von einem Vektorfeld stehen. 
###### Deutung:
Kleine Fläche $\Delta f$ mit einer Oberflächennormale $\underline{\hat{\nu}}$  und ein vektorfeld $\underline{a}(\underline{r})$, Was ist der fluss induziert vom vektorfeld durch die kleine flaeche? $\underline{a} \cdot \underline{\hat{\nu}} \cdot \Delta f$.
Bei einem Kleinem Volumen $\Delta V$ bei $\underline{r}$:
>$q(r) \Delta V$ mit $q(\underline{r}) = \text{div} \cdot \underline{a} = \underline{\nabla} \cdot \underline{a}$ 

Jetzt direkt an die Elektrodynamik angewendet kann man beispiele finden, wofür diese berechnung benutzt werden, und zwar in den Maxwell gleichungen: 
- $\text{div} \; \underline{D} = \rho$ .... Ladungen sind Quellen des Elektrischen Feldes
- $\text{div} \; \underline{B} = 0$ .... Es existieren keine Magntischen Monopole.
Wie dies dann in Krummlinige Koordinaten aussieht, wird dann noch in der übung erleutert. 
### Rotation eine Vektorfeldes

>Def: $\text{rot} \; \underline{a}(\underline{r}) = \underline{\nabla} \times \underline{a}(\underline{r})$ 

Es ist dass wirbelfeld von $\underline{a} (\underline{r})$, und zwar wie doll ein Vektorfeld um ein punkt rotiert. 


##### Anwendungen:
>Gradienten felder sind wireblfrei
>$$\underline{a} = \text{grad} \; U \Leftrightarrow \text{rot} \; \underline{a} = 0$$

>[!note] Einfach zusammenhängendes gebiet: eine gebiet wo ich jeder kurve zu einem punkt zusammenziehen kann.

>Wirbelfelder sind quellfrei:
>$$\text{div} \; \underline{B} = 0 \Leftrightarrow \underline{B} = \text{rot} \; \underline{A}$$

>Laplace-Operator

## Fundamentalsatz der Vektoranalyis
Wenn wir die quellen und wirbel eines vektorfeldes kennen, dann können wir dass ganze vektorfeld bestimmen.

#### Helmholtz Satz


# Integration von Feldern
## LinienIntegrale
Weg C:
# Satz von Stokes
>$\int \text{rot} \; \underline{a} \cdot d \underline{f} = \int_{C = \partial F} \underline{a} \cdot d \underline{r}$ 

Beweis: man nehme eine schleife, und zerlege sie in infinitesimale kleine flächen. Jede kleine fläche wird dann die zirkulation berechnet, aber benachbarte flächen heben sich die beträge auf, bis zum rand, wo dann die rand zirkulation hervorkommt, Bedeutend dass die zirkulation interne komplett irrelevant ist, und nur der rand zur zirkulation beiträgt.

## Satz von Gauss
>$\int_{V} \text{div} \; \underline{a} \, dV = \int_{\partial V} \underline{a} \cdot d \underline{f}$ 

