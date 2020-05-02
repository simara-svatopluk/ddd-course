# Kurz Domain-Driven Design

![DDD logo](ddd_sm.png)

Domain-Driven Design... praktický přístup k vývoji software zaměřený na cílovou problematiku - doménu. DDD je o přemýšlení, náhledu a modelování, není spojený s žádným frameworkem, a vlastně ani žádnou technologií či konkrétním programovacím jazykem.

## Cíle

* Jak přemýšlet nad problémy libovolné složitosti
* Jak je modelovat
* Na co se zaměřit a co zanedbat
* Jak psát kvalitní, udržovatelný a otestovaný kód

## Forma

* Záznamy + Materiály + Kód
* Zdarma

## Přednášky

1. **Přehled** -
  [materiály (en)](1-overview/overview.md) -
  [slidy](https://www.slideshare.net/Svatoplukimara/ddd-kurz-1-pehled) -
  [záznam Brno](https://www.youtube.com/watch?v=Bd_ntFcqN7M) - 
  [záznam Ostrava](https://www.youtube.com/watch?v=N1TfKRJd7Rs) -
  [Ostrava 12.9.](https://www.facebook.com/events/2221134194773795/) -
  [Brno 3.10.](https://www.facebook.com/events/1833155483466249)
1. **Jazyk** - 
  [materiály (en)](2-language/language.md) -
  [slidy](https://www.slideshare.net/Svatoplukimara/ddd-kurz-2-jazyk) -
  [záznam Brno](https://www.youtube.com/watch?v=-AEGHFC-Omw) -
  [workshop](2-language/workshop/workshop.md) -
  [Ostrava 10.10.](https://www.facebook.com/events/164359401137716) -
  [Brno 24.10.](https://www.facebook.com/events/2188601447877078)
1. **Model** -
  [materiály (en)](3-model/model.md) -
  [slidy](https://www.slideshare.net/Svatoplukimara/ddd-kurz-3-model) -
  [záznam Brno](https://www.youtube.com/watch?v=oKN9a6JL54o) -
  [workshop](3-model/workshop/workshop.md) -
  [Ostrava 7.11.](https://www.facebook.com/events/189432881986539/) -
  [Brno 21.11.](https://www.facebook.com/events/277038186350190/)
1. **Implementace** -
  [materiály (en)](4-implementation/implementation.md) -
  [demo](https://github.com/simara-svatopluk/ddd-course-workshop) -
  [slidy](https://www.slideshare.net/Svatoplukimara/ddd-kurz-4-implementace/) -
  [záznam Brno](https://www.youtube.com/watch?v=_9OyhJtebos) -
  [Brno 19.12.](https://www.facebook.com/events/1963793990589645)
1. **Persistence** - *Repozitáře + Doctrine* -
  [materiály (en)](5-persistence/persistence.md) -
  [demo](https://github.com/simara-svatopluk/ddd-course-workshop) -
  [slidy](https://www.slideshare.net/Svatoplukimara/ddd-kurz-5-persistence-doctrine) -
  [záznam Brno](http://bit.ly/ddd-5-cast) -
  [Brno 16.1.](https://www.facebook.com/events/226691471592602)
1. **Read model & CQRS** -
  [slidy](https://www.slideshare.net/Svatoplukimara/read-model-cqrs) -
  [záznam Brno](https://www.youtube.com/watch?v=tycbhj7kcQo) -
  [Brno 13.2.](https://www.facebook.com/events/376353809813879)

## Demo

Veškerý kód z dem a workshopů naleznete v repozitáři [ddd-course-workshop](https://github.com/simara-svatopluk/ddd-course-workshop).

## Probraná témata

1. **✓ Přehled** - přehled základních konceptů
1. **✓ Jazyk** - pár příkladů a pár doporučení jak přemýšlet v daném jazyce
1. **✓ Model** - jak přemýšlet jinak než v tabulkách, zjednodušení modelu (agregáty, entity, value objekty)
1. **✓ Implementace** - kód, testování, TDD
1. **✓ Repozitáře** - kde brát objekty, memory implementace
1. **✓ SQL/Doctrine Repozitáře** - Persistence, už skoro funkční aplikace
1. **✓ Read model** - Jak nad ním přemýšlet, více modelů v jedné aplikaci
1. **✓ Read model SQL Repozitář** - kde brát DTO v reálné aplikaci
1. **✓ Commandy** - Oddělení části aplikace měnící stav

## Cílová skupina

* Programátoři
* Projekťáci
* UXáci
* Testeři

Ano, DDD není jenom pro programátory, je pro celou IT sféru, a možná zasahuje i dále. Nelze totiž modelovat případy užití pokud má projekťák všechno jako tabulku. Musíme být všichni naladěni podobně.

## Další materiály

* EVANS, Eric. *Domain-driven design: tackling complexity in the heart of software*. Boston: Addison-Wesley, 2004. ISBN 0-321-12521-5. [kniha na Amazonu](https://www.amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215)
* FOWLER, Martin. UbiquitousLanguage. *MartinFowler.com* [online]. 2006 [2017-11-28]. Available: [https://martinfowler.com/bliki/UbiquitousLanguage.html](https://martinfowler.com/bliki/UbiquitousLanguage.html)
* VERNON, Vaughn. *Implementing domain-driven design.* Upper Saddle River, NJ: Addision-Wesley, 2013. ISBN 978-0-321-83457-7. [kniha na Amazonu](https://www.amazon.com/Implementing-Domain-Driven-Design-Vaughn-Vernon/dp/0321834577)
* CLEMSON, Toby. *Testing Strategies in a Microservice Architecture* [online]. 2014 [2018-01-11]. Available: [https://martinfowler.com/articles/microservice-testing/](https://martinfowler.com/articles/microservice-testing/)
* Sbírka materiálů od Honzy Kuchaře: https://gitlab.grifart.cz/jkuchar1/eventsourcing-cqrs-simple-app/tree/master
