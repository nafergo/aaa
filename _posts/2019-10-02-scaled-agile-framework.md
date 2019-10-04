---
layout: post
title: Scaled Agile Framework (SAFe)
categories: [Agilní metodiky]
author: Lukáš Bednařík
author-link: https://lukasbednarik.cz
---

## Anotace

[SAFe](http://www.scaledagileframework.com/) framework je jednou
z odpovědí na škálování vývoje ve velkých organizacích.
SAFe je konfigurovatelný na 2 až 4 úrovně (levels) dle velikosti organizace.

Tyto úrovně zahrnují Portfolio level, který rozhoduje o strategii firmy,
Solution level pracující na "solution",
Program level škálující práci na konkrétním produktu
a koordinující týmy. Posledním článkem řetěžce je Team level.

## Historie

Autorem SAFe je Dean Leffingwell, bývalý vice president Rational Software (dnes součást IBM)
kdysi zodpovědný za vývoj a komercializaci frameworku [RUP](/rational-unified-process).

SAFe framework nejprve vznikal ve spolupráci Deana Leffingwella s agilní komunitou.
Prvotním cílem frameworku bylo nastínit proces vzniku produktu od produktového managementu,
skrz řízení projektů, až po vývojářské týmy. Framework byl poprvé formalizován
roku 2007 v knize *Scaling Software Agility: Best Practices for Large Enterprises*
(Leffingwell, Dean) a od té doby prodělal řadu revizí.
Současná verze z března 2018 je **SAFe 4.5**.

## Popis

### Lean mindset

![Scaled Agile Framework](/assets/safe-framework.jpg)

### Portfolio level

### Solution level

### Program level

### Team level


## Kritika

Kritika SAFe napadá agilní povahu SAFe frameworku.
Být "agile" neznamená používat [Scrum](/scrum) nebo [Kanban](/kanban), ale vyžaduje to změnu kultury
celé organizace. Zatímco úzká spolupráce vývoje a obchodu je u malých organizací
přirozená, u velkých korporátů se stává mimořádnou výzvou, kterou SAFe nijak neřeší.

SAFe nesplňuje dva ze čtyř bodů [agilního
manifestu](/agile) a třetí bod (spolupráce se zákazníkem) nijak nekomentuje.

Kritici SAFe také uporozňují na to, že komerční úspěch metodik nebo frameworků
nemusí být v žádném vztahu k jejich kvalitě.

### Proč SAFe není agilní?

První bod agilního manifestu: Jednotlivci a interakce před procesy a nástroji.
SAFe je framework definující právě procesy a pracovní postupy
pro dodávání softwaru. Portfolio level se nejprve rozhodne, co se má udělat,
a předá toto rozhodnutí níže na Program level. Program level deleguje práci
vývojářským týmům, tedy Scrum Master, Product Owner a vývojáři jsou jen
pěšáky v mnohem větší hře. Zpětná vazba k rozhodnutím na Portfolio úrovni
je jen stěží možná.

Dalším bodem agilního manifestu je: Reagování na změny před dodržováním plánu.
Jenže každá změna musí být zaznamenána na Product level, komunikována nahoru
na Portfolio level a delegována dolů na Team level. Věci se v SAFe
relativně komplikují.

Detailnější analýza SAFe nakonec odhaluje, že role Scrum Mastera svou definicí
velmi připomá roli tým lídra. Scrum Master v SAFe frameworku chodí na koordinační
meetingy, kde se potkává se svým nadřízeným Release Train Engineer
(popisovaným jako "chief Scrum Master"). Výsletky koordinačních meetingů musí Scrum Master
komunikovat týmu a velmi pravděpodobně také tým organizovat. Tím se popírá
princip samoorganizovaných týmů propagovaných v agilním vývoji.
