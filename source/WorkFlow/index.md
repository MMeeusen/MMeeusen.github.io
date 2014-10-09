title: WorkFlow
date: 2014-10-08 15:19:58
---
Om te beginnen is het vereist dat je Git en npm installeerd.
Met npm kan je gemakkelijk hexo installeren via dit commando:
```bash
$ npm install -g hexo
```

Wanneer dit gebeurd is, ga je naar *themes/landscape* en open je het  *_config.yml* bestand.
Hiervoor heb ik Brackets geïnstalleerd zodat je makkelijk van bestand naar bestand kan gaan en ze bewerken.
Daar voeg je onder *menu* bij: *WorkFlow: /WorkFlow*.
Om rechtsboven het RSS logo weg te halen moet je in dezelde *_config.yml* de regel met *rss: /atom.xml* verwijderen.
Als je nu de server opstart met het commando hieronder, kan je de site bekijken door naar het gegeven adres: *localhost:4000* te gaan.

```bash
$ hexo server
```
Als je eenmaal op de site bent staat er bovenaan naast *Home* en *Archives* een nieuw menu-item met de naam WorkFlow.
Nu moet je echter nog een pagina maken zodat je geen foutmelding krijgt als je erop klikt.
Dit kan je doen door het volgende commando in te geven:
```bash
$ hexo new page "WorkFlow"
```

Nu is er een map *WorkFlow* aangemaakt in de hoofd *source* map.
Daarin vind je een MD-bestand genaamd *index*. Hierin zet je de tekst die je op de pagina wilt zetten. Je kan de tekst eventueel opmaken met MarkDown.