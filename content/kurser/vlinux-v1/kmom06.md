---
author:
    - lew
revision:
    "2019-03-26": (A, lew) Ny inför HT19.
...
Kmom06: Docker Compose
==================================

Nu har vi koll på hur vi kan strukturera lite större Bash-script. Vi ska gå vidare med Docker och kika på *Docker Compose*. Det underlättar för oss när Docker konstruktionerna växer. Vi ska ta vår Mazerunner från förra kursmomentet och använda oss utav Docker Compose för att köra igång kontainrarna och nätverket. Vi ska även lägga till lite funktionalitet till Mazerunner. Utöver Bash och Docker Compose ska vi fortsätta titta på reguljära uttryck och verktyget "Awk".

<!--more-->

Du kommer skapa en spel-loop till din Mazerunner, likt nedan:

[ASCIINEMA src=244597]

Så kan det se alltså ut när ena delen är klar.



<small><i>(Detta är instruktionen för kursmomentet och omfattar det som skall göras inom ramen för kursmomentet. Momentet omfattar cirka **20 studietimmar** inklusive läsning, arbete med övningar och uppgifter, felsökning, problemlösning, redovisning och eftertanke. Läs igenom hela kursmomentet innan du börjar jobba. Om möjligt -- planera och prioritera var du vill lägga tiden.)</i></small>


### Video  {#video}

Titta på följande:

1. Till kursen finns en videoserie, "[vlinux](https://www.youtube.com/playlist?list=PLKtP9l5q3ce_oeXQlDtKv51tVM4Y8UtkF)", kika på de videor som börjar på "regex"



Läsanvisningar  {#lasanvisningar}
---------------------------------

###Lästips {#lastips}

Läs i dokumentationen om [Docker Compose](https://docs.docker.com/compose/).



Övningar & Uppgifter  {#ovningar_uppgifter}
-------------------------------------------

*(ca: 8-18 studietimmar)*



### Övningar {#ovningar}

Genomför följande övningar.

1. Gå igenom delen i guiden som handlar om "[Docker Compose](guide/docker/docker-compose)".

1. Läs i guiden om "[awk](guide/kom-igang-med-awk)".



### Uppgifter {#uppgifter}

Dessa uppgifter skall utföras och redovisas.

1. Gör uppgiften [awk script](uppgift/vlinux-awk) för att träna upp grundläggande färdigheter i verktyget awk. Du arbetar i mappen `awk/`.

1. Gör uppgiften [Spel loop i Mazerunner](uppgift/mazerunner-loop). Du arbetar i mappen `maze2/`.

1. Lägg till redovisningstexten i din me-sida.



Resultat & Redovisning  {#resultat_redovisning}
-----------------------------------------------

*(ca: 1-2 studietimmar)*

Läs [instruktionen om hur du skall redovisa](./../redovisa).

Se till att följande frågor besvaras i redovisningstexten.

* Kan du se fördelar/nackdelar med Compose?
* Hur väl har du fått ordning på begreppen kring klient och server?
* Känner du dig bekväm med Docker överlag?
* Kommer du använda Docker utanför kursens ramar?
* Gjorde du någon uppdatering av Mazerunnerns struktur?
* Beskriv dina tankar om awk.
