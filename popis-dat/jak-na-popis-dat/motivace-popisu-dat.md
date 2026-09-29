---
layout: contained
title: Motivace popisu dat
ref: DataModelling-Methodology-Motivation
lang: cs
---

<div class="methodology-document">
<span id="_Úvod_popisu_dat"></span><span id="_Úvod_do_popisu"></span><span id="_Motivace_popisu_dat"></span><span id="_Toc180400066"></span><span id="_Toc185597967"></span><span id="_Toc228267996"></span>

<p>Kvalitní správa dat veřejné správy představuje základ pro to, aby je bylo možné sdílet a využít pro poskytování služeb veřejnosti, k naplňování klíčových zákonných povinností, plánování politik státu nebo k tvorbě analytických materiálů potřebných pro výkon veřejné správy. Data nelze kvalitně spravovat bez znalosti jejich obsahu a významu.</p>

<p>Představte si například, že máte za úkol zjistit „kolik vozidel je průměrně na silnicích Prahy 5 každé ráno“ k analýze toho, jak jsou využívány aktuální kapacity pozemních komunikací. Ta by měla sloužit k budoucímu plánování dopravní infrastruktury. Takový úkol zní na první pohled jednoduše – možná se vám i rychle podaří najít relevantní datové sady, ale poté se dozvíte, že se v těchto datech „vozidly“ myslí <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-10-01/dokument/norma/cast_1/hlava_1/par_2/pism_f">vozidla podle zákona č. 361/2000 Sb.</a>, ale vy jste chtěli informace o <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-10-01/dokument/norma/cast_1/hlava_1/par_2/pism_g">motorových vozidlech</a>, a „Praha 5“ v datové sadě není městský obvod, ale znatelně větší městská část. Výsledkem by tak byly zavádějící podklady pro analýzu, což by při rozhodování mohlo vést k nepřiměřenému přidělování zdrojů na určité projekty nebo oblasti.</p>

<aside class="methodology-callout methodology-callout--note">Vozidlo je typickým příkladem slova, kdy se v běžné mluvě myslí jedna věc (motorová vozidla) ale v zákoně jiná – vozidlo je podle zákona č. 361/2000 Sb. i kolo. Řidič podle tohoto zákona může být i cyklista, ale typicky si pod tímto výrazem lidé představí řidiče motorového vozidla. <a href="https://www.e-sbirka.cz/czechvoc/POJMREJ/termin/110825?f=vozidlo">Další zákony definují „vozidlo“ i</a> jinak.</aside>

<p>Problematika hledání správných dat pro své potřeby však není pouze zodpovědností uživatelů, kteří data přebírají, ale také poskytovatelů. Jenom oni dokáží popsat, o čem nebo o kom (např. o řidiči podle zákona/řidiči jako vlastníkovi řidičského průkazu) přesně datové sady jsou.</p>

<p>Základní součástí kvalitní správy dat je tedy jejich dobrá znalost ze strany úřadu, který tato data shromažďuje. Právě k tomu, aby měl o svých datech přehled, věděl, jaká data sbírá, k čemu je využívá a mohl je sdílet dle potřeb s ostatními úřady, je nezbytně nutné, aby si svá data kvalitně popsal (věděl, o kom/o čem přesně jsou). Při dodržení pravidel pro popis dat tak daný úřad výrazně sníží možnost, že by tato data byla interpretována nesprávným způsobem. Popis dat je klíčový také pro správnou evidenci údajů v Registru práv a povinností (RPP), kterou jsou úřady ze zákona povinny naplňovat a získají tím oprávnění pro čtení a zápis údajů taktéž evidovaných v RPP. Dalšími příklady zákonných povinností, pro které je popis dat důležitý, jsou:</p>

<ul>
<li>popisy publikovaných otevřených dat v Národním katalogu otevřených dat</li>
<li>a sdílení dat v rámci Propojeného datového fondu (navazuje na evidenci do RPP).</li>
</ul>

<p>Každý úřad vykonávající agendu si potřebuje pro své efektivní fungování udělat pořádek ve svých datech, pro digitalizaci agend to platí dvojnásob. Mimo jiné i proto je důležité, aby byl popis dat strojově čitelný. Pokud se takto popíšou data, která „tečou“ informačními systémy a rozhraními, pomůže se tím k zajištění dohledatelnosti a využitelnosti dat napříč systémy – i těch, které jsou ve správě třetích stran.</p>

<p>Popis dat má i další benefity, například:</p>

<ul>
<li>Zachová se tak co největší množství informací o agendě úřadu, procesech, správě dat apod. Úřad si tím navíc zajistí větší nezávislost na dodavatelích a zabrání tomu, aby dodavatelé měli nepřiměřeně velkou kontrolu nad daty a procesy agend.</li>
<li>Interní znalosti úřadu má smysl s popisem dat udržovat i pro případ odchodu/pracovní neschopnosti klíčových zaměstnanců nebo pro zaškolení nových zaměstnanců.</li>
<li>Mít popsaná data je důležité také při řízení kvality a rizik, která s nimi souvisí, například z hlediska bezpečnostního managementu a nakládání s osobními údaji – pokud nebudou mít úřady o svých datech přehled a nebudou je dobře znát, nebudou schopny tato rizika identifikovat a svá data efektivně chránit.</li>
</ul>

<span id="_Správa_dat_a"></span><span id="_Návaznost_na_správu"></span><span id="_Toc180400067"></span><span id="_Toc185597968"></span><span id="_Toc228267997"></span><h2 id="navaznost-na-spravu-dat">Návaznost na správu dat</h2>

<p>V případě, že úřad naplňuje standard správy dat tak, jak jej uvádí <a href="https://data.gov.cz/správa-dat/strategie-správy-dat/">Strategie pro správu dat ve veřejné správě ČR (2024—2030)</a> (dále jen Strategie) v části 4.1.1, bude zaručena spolehlivost a důvěryhodnost jím spravovaných dat, která je nezbytným předpokladem pro další práci s nimi a také pro jejich sdílení. Oblasti popisu dat se věnuje Strategie podrobněji ve specifickém cíli 1.3 Zajištění dohledatelnosti, srozumitelnosti a kategorizace dat, respektive v opatření 1.3.1 Popsat data a definovat jejich význam.</p>

<p>Toto opatření cílí na to, aby úřad vytvořil a následně také udržoval aktuální popis struktury a významu dat v informačních systémech dle standardů a metodických doporučení DIA, a to alespoň ve všech prioritních oblastech v tzv. <em>datový</em><em>ch</em> slovnících. Konkrétně by měl úřad vytvářet datové slovníky, které jsou katalogizovány v lokálním katalogu dat (viz opatření 1.3.2 Strategie) v podobě datové sady podle odpovídajícího standardu (otevřené formální normy pro slovníky). Tento katalog doplňuje k popisu dat další informace nutné pro jejich dohledatelnost a práci s nimi. Naplnění tohoto opatření bude podle <a href="https://odok.cz/portal/veklep/material/KORND4KLAAG6/">navrhovaného zákona o správě dat a řízeném přístupu k datům</a> povinné pro subjekty definované tímto zákonem.</p>

<p>Z pohledu správy dat jsou popis dat a jeho pravidelná aktualizace důležité i při udržování přehledu o datových potřebách, a to jak uvnitř samotného úřadu, tak i ze strany dalších úřadů (opatření 1.2.2 Strategie). Díky popisu a tím i dobré znalosti dat může úřad identifikovat příležitosti k získávání dat z jiných agend nebo úřadů a také zjistit, kde jsou možnosti využití dat pro lepší digitalizaci poskytovaných služeb veřejnosti nebo efektivnější výkon jeho procesů. Zároveň díky tomu, že budou mít úřady svá data popsána, mohou reagovat na požadavky na získání, využívání nebo sdílení dat, které k nim přicházejí ze strany dalších úřadů nebo odborné veřejnosti pro výzkumné a analytické účely (opatření 1.4.1). Nezanedbatelnou roli hraje popis dat také při řízení změn informačních systémů veřejné správy (této oblasti se věnuje opatření 1.4.2 Strategie), ve kterých se data shromažďují a uchovávají.</p>

<span id="_Zákon_a_popis"></span><span id="_Koncepty_popisu_dat"></span><span id="_Základy_popisu_dat"></span><span id="_Ref167016596"></span><p>Pro popis dat má význam stanovit v úřadě také role, které jsou odpovědné za data (opatření 1.1.1 Stanovit odpovědnost za data úřadu a jejich správu Strategie). Klíčová je role datového architekta, který drží a rozvíjí celkový přehled o datech úřadu. Vytvoření a udržování popisu dat by proto mělo být jedním z jeho prvořadých zájmů, měl by jej koordinovat a vést po odborné stránce. Aby byl popis přesný a odpovídal tomu, jaký je význam popisovaných dat, je nutné zapojit i toho, kdo má věcnou znalost dané datové oblasti. Konkrétně jde o tyto osoby:</p>

<ul>
<li>zástupce vedení úřadu v roli, která je manažersky a věcně odpovědná za data v konkrétní věcné oblasti („vlastník dat“),</li>
<li>zástupce úřadu v roli, která je věcně odpovědná za data v konkrétní věcné oblasti a na každodenní bázi vykonává činnosti související s jejich věcnou správou, např. kontrolu jejich správnosti a úplnosti („věcný správce dat“).</li>
</ul>

</div>
