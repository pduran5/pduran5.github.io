<!-- .slide: class="intro" -->
# M05. Entorns de Desenvolupament 
### CFGS DAW-BIO
<small>Pedro Durán / <pduran5@xtec.cat></small>

---

# UF1. NF1. Cicles de vida, metodologies i IDEs
## A1. Cicles de vida i metodologies

---

## Desenvolupament de programari

*   Tota **aplicació informàtica** ha seguit un **procediment** planificat i desenvolupat detall per detall **per a la seva creació**:

    *   Analitzar les necessitats.
    *   Dissenyar una solució.
    *   Desenvolupar el programari.
    *   Dur a terme les proves.
    *   Implantar el programari.

---

## Concepte de programa informàtic

*   Un **programa informàtic** és un conjunt d'esdeveniments ordenats de manera que se succeeixen de forma seqüencial en el temps, un darrere l'altre.

*   Per **executar un programa** s'entén fer que l'ordinador segueixi totes les seves ordres, des de la primera fins a la darrera.

--

## Codi font i compilació

* Un cop s'ha acabat d'escriure el programa, el conjunt de fitxers de text resultants, on es troben les instruccions, es diu que contenen el **codi font**.

* La **compilació** és la traducció del codi font en fitxers en format binari que contenen les intruccions en un format que el processador pot entendre.

--

## Codi objecte i codi executable

* El **codi objecte** és el codi font traduït (pel compilador) a codi màquina, però aquest encara no pot ser executat per l'ordinador.

* El **codi executable** és la traducció completa a codi màquina, duta a terme per l'enllaçador (o **linker**). El codi executable és interpretat directament per l'ordinador.

--

## Linker i llibreria

* El **linker** és l'encarregat d'inserir al codi objecte les funcions de les llibreries que són necessàries per al programa generant un arxiu executable.

* Una **llibreria** és una col·leció de codi predefinit que facilita la tasca del programador a l'hora de codificar un programa.

--

## Procés de transformació codi font a executable

![](/img/ic10m05u1_01.png)