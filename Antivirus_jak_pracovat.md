# Jak pracovat s antivirem

Dnes se podáme na to jak prakticky pracovat s antivirem a co všechno v něm můžeme nastavit. Já budu používat licencovaný antivir od slovenské společnosti ESET -- ESET HOME ESSENTIAL. Stojí pouze cca 1000 Kč/rok, pro 1 zařízení, což je dle mého názoru adekvátní cena. Taktéž pracuji na Windows 11.

## Znak štítu
První co zmíním je znak štítu. Pokud uvidíte šachovnicový štít, znamená to že budete muset změny povolit s právy správce. Pokud nevíte co to znamená podívejte se na toto [video](https://www.youtube.com/watch?v=5KhnG7F4GdE) od HSB - Davida Šetka.

## Virus Total
Za zmínku taktéž stojí webová služba [Virus Total](https://www.virustotal.com/gui/home/upload), která slouží ke skenování souborů, url adres nebo klidně jenom hash souboru. Po nahrání stránka zkontroluje zda je např. url adresa na černý listině či může obsahovat phising nebo jiné nakažené soubory. Více práce s Virus Total a použití API výjde v nějakém dalším článku.

## Typy aplikací
Pro začátek [zde](https://help.eset.com/eea/10.1/en-US/idh_home.html) najdete documentaci AV produktu ESET. 


## SysInspector
Tento nástroj slouží k diagnostice Windows, zjistění nestabilního nebo podezřelého chování. Hodí se např. po útoku na počítač nebo síť jako aktuální otisk, obraz toho jak počítač vypadá, co probíhá, k jakým sítím je připojen apod.

V Kartě Domů máme 4 možnosti. Uložit -- uloží vygenerovanou diagnostiku. Otevřít -- otevře uloženou vygenerovanou diagnostiku. Generovat osobní protokol -- vygeneruje detailní výpis procesů, síťových spojení a mnohem více, pracující i s daty uživatele, nedoporučuje se sdílet tento výpis s diagnostiky. Pro větší soukromí uživatelů slouží generace anonymního protokolu, který data uživatelů již neobsahuje.


### Generovat anonymní protokol
Po vygenerování protokolu můžeme najít informace rozdělená do kategorií.

**Spuštěné procesy**        
Je to takový Task Manager s více údaji a kontrolou jestli náhodou neobsahuje nechtěný nebo rizikový proces. Rád bych vysvětlil jeden řádek pro neznalé jedince.     
`System prcess` => název aplikace, která proces volá či její podprocesy.      
`PID` => pouze ID procesu, můžeme jej využít když chceme v terminálu zabít tento proces.        
`Uživatelské jméno` => jméno uživatele, jenž proces spustil, můžeme najít že to spustil `NT Authority/System`, což pouze znamená že to spusil samotný systém (OS).      
`Stav` => Může být: V pořádku(zelené), Neznámý(žluté), Rizikové(červené)        
`Popis souboru` => Normální popis souboru

### Generovat osobní protokol
Karty budou stejné, ale obsah bude rozšířenější o uživatelské data.


## ESET Zabezpečené bankovnictví

## ESET Security