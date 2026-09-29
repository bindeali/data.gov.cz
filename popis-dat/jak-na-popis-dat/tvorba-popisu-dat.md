---
layout: contained
title: Tvorba popisu dat
ref: DataModelling-Methodology-Creation
lang: cs
---

<div class="methodology-document">
<span id="_Proces_popisu_dat_2"></span><span id="_Toc180400076"></span>

<span id="_Toc185597977"></span><span id="_Toc228268006"></span>

<p>V této kapitole se dozvíte, jak tvořit slovníky. Proces této tvorby je navržen tak, aby procházel jednotlivými úrovněmi detailu podle možného využití výsledného slovníku (viz níže). Proces popisu dat ukážeme na komentovaném příkladu. Příklad si projdeme od začátku (sběr zdrojů) do konce (publikace vzniklého slovníku).</p>

<p>V prvé řadě je nutné uvést pro ty, co se popisu dat obávají (buď z hlediska kapacit nebo správnosti), že popis dat je průběžná činnost. Je jasné, že se legislativa a podpůrné dokumenty časem mění – kromě toho je pochopitelné, že není reálné provést vše do největšího detailu ihned bez chyby. Proto vám doporučujeme, abyste si nejdříve popis dat zkusili na malé oblasti (resp. její malé části) v malém detailu, který pak můžete společně se získanými zkušenostmi rozvíjet.</p>

<aside class="methodology-callout methodology-callout--note">Nedokončený popis dat je mnohem lepší, než žádný popis dat! Již částečný popis dat totiž umožňuje sdílet jejich význam.</aside>

<span id="_Úrovně_popisu_dat_2"></span><span id="_Toc180158430"></span><span id="_Toc180400077"></span><span id="_Ref181112592"></span><span id="_Ref181112595"></span><span id="_Toc185597978"></span><span id="_Toc228268007"></span><h2 id="urovne-popisu-dat">Úrovně popisu dat</h2>

<p>Vytvořením pojmů popisujících subjekty a objekty práva z dané oblasti získáte slovník v jeho minimální podobě. Taková podoba se dá využít jako <a href="využití-popisu-dat#_Proces_publikace_slovníku">Výkladový slovník</a> nebo pro základní <a href="využití-popisu-dat#_Popis_datových_sad">Popis datových sad</a>. Dodáním <a href="#_Ekvivalentní_pojmy_1">vlastností</a> k subjektům a objektům práva se využitelnost rozšiřuje dále na evidenci do RPP (viz 3.3 <a href="využití-popisu-dat#_Evidence_údajů_agendy">Evidence do Registru práv a povinností</a>). Dodáním <a href="#_Vztahy">vztahů</a> mezi subjekty a objekty práva vzniká plnohodnotný popis, který je potom využitelný mj. na datové specifikace (viz 3.4 <a href="využití-popisu-dat#_Využití_v_Národním">Tvorba datových specifikací</a>).</p>

<span id="_Toc180400078"></span><span id="_Toc185597979"></span><span id="_Toc228268008"></span><h2 id="proces-popisu-dat">Proces popisu dat</h2>

<span id="_Subjekty_a_objekty"></span><span id="_Tvorba_popisu_dat"></span><span id="_Úrovně_popisu_dat_1"></span><span id="_Úrovně_popisu_dat"></span><span id="_Nástroje_pro_popis"></span><p>Proces je stručně uveden v následující tabulce, která sleduje posloupnost následujících podkapitol. Vedle každého kroku je odkaz na příslušnou část metodiky, kde je tento krok rozebírán ve větším detailu.</p>

<aside class="methodology-callout methodology-callout--note">Tabulka popisuje jednu <em>iterac</em><em>i</em> popisu – jak je zmíněno výše, nenaléháme na vytvoření kompletního popisu v jediné iteraci.</aside>

<p>Proces je v tabulce rozdělen na 4 fáze, přičemž je možné některé kroky provádět souběžně (například evidence subjektů a objektů práva společně s vlastnostmi a vztahy) nebo v jiném pořadí (například výběr nástroje před výběrem oblasti).</p>

<div class="methodology-table-wrapper"><table><tbody><tr><td rowspan="3">Příprava iterace</td><td>Vyberte oblast (nebo její část), kterou budete v rámci slovníku popisovat a určete osobu/osoby, která bude naplňovat role důležité pro popis dat (především znalec dané oblasti a tvůrce samotného popisu).</td><td><a href="#_Ref181112200">5.3</a> <a href="#_Ref181112203">Výběr oblasti pro popis dat</a>, <a href="#_Ref181112191">5.4</a> <a href="#_Ref181112195">Role potřebné pro popis dat</a></td></tr><tr><td>V rámci této oblasti vyberte autoritativní zdroje definic pojmů (zákony, dokumentace, metodiky, směrnice apod.).</td><td><a href="#_Ref181112275">5.5</a> <a href="#_Ref181112278">Zdroje popisu dat</a></td></tr><tr><td>Vyberte nástroj, ve kterém budete popis dat vytvářet. Doporučujeme podporované nástroje (viz podkapitola <a href="#_Ref181112306">5.6</a> <a href="#_Ref181112308">Nástroje pro tvorbu popisu dat </a>).</td><td><a href="#_Ref181112306">5.6</a> <a href="#_Ref181112308">Nástroje pro tvorbu popisu dat </a></td></tr><tr><td rowspan="3">Základní slovník</td><td>Ve zdrojích identifikujte subjekty práva (osoby) a objekty práva (věci, koncepty, skutečnosti), které jsou v oblasti důležité a popisují data evidovaná vaší organizací (kromě provozních údajů) v rámci informačních systémů veřejné správy.</td><td><a href="#_Ref181112371">5.8</a> <a href="#_Ref181112330">Výběr pojmů</a>, <a href="#_Ref181112364">5.9</a> <a href="#_Ref181112332">Subjekty a objekty práva</a></td></tr><tr><td>Ke každému subjektu a objektu práva, pokud je to možné, doplňte následující informace:<br>Název: jednoznačný, přesný, bez zkratek a nespisovného jazyka, v prvním pádě jednotného čísla. Píše se v lidsky čitelné podobě; nejde o názvy databázových tabulek.<br>Definice: text ze zdroje určující význam pojmu. Pokud zdroj definici nijak neuvádí (pojem pouze zmiňuje), lze definici vynechat a vytvořit popis (bod d).<br>Zdroj: nejlépe ve formě strukturovaného, strojově čitelného odkazu na veřejně dostupný web, kde si každý může definici zkontrolovat. Pokud však žádný odkaz neexistuje, lze zdroj uvádět v podobě textu - např. název materiálu se stranou.<br>Popis: dále upřesňuje význam pojmu nad rámec definice nebo vysvětluje definici jinými slovy. Může to být vlastní popis tvůrce slovníku, tj. nemusí pocházet ze zdroje.</td><td><a href="#_Ref181112383">5.10</a> <a href="#_Ref181112386">Charakteristiky pojmu</a></td></tr><tr><td>Kde je to vhodné, doplňte nadřazené pojmy. Nadřazený pojem je obecnější vůči pojmům jemu podřazeným, které ho rozdělují na různé „druhy“ (například „Vozidlo“ a „Motorové vozidlo“, „Nemotorové vozidlo“).</td><td><a href="#_Ref181112477">5.11</a> <a href="#_Ref181112479">Nadřazené pojmy</a>,</td></tr><tr><td></td><td><em>Splněna úroveň</em><em> </em><em>z</em><em>ákladního</em><em> </em><em>slovníku</em> – následující kroky nejsou pro tvorbu slovníku povinné, ale jejich vyplnění rozšiřuje možnosti využití slovníku (viz podkapitola <a href="#_Ref181112592">5.1</a> <a href="#_Ref181112595">Úrovně popisu dat</a>). Můžete se tedy rozhodnout, jestli pokračovat s popisem vlastností a vztahů, nebo tuto iteraci popisu ukončit publikací slovníku podle instrukcí níže v části „Konec iterace“.</td><td><a href="#_Ref181112592">5.1</a> <a href="#_Ref181112595">Úrovně popisu dat</a></td></tr><tr><td rowspan="2">Vlastnosti a vztahy (volitelné)</td><td>Dále ze zdrojů vyberte vlastnosti; vlastnost se vždy váže na konkrétní subjekt nebo objekt práva. V názvu vlastnosti je i subjekt nebo objekt práva, ke kterému se vlastnost vztahuje – například <em>Jméno řidiče</em> namísto <em>Jméno</em>. Stejně, jako u subjektů a objektů práva, se i k vlastnostem doplňují výše zmíněné charakteristiky (název, definice, zdroj, popis).<br>Každá vlastnost popisuje dále nedělitelnou informaci daného pojmu. Vlastnost nesmí kombinovat více informací najednou, tj. nelze vytvořit vlastnost „Jméno a příjmení žadatele o řidičské oprávnění“. Pro kontrolu byste měli ke každé vlastnosti dokázat vymyslet příkladovou hodnotu (například „Jméno“ – „Jan“).<br>Vlastnostmi nejsou provozní data informačních systémů – identifikátory, databázové klíče apod.</td><td><a href="#_Ref181112698">5.13</a> <a href="#_Ref181112689">Vlastnosti</a></td></tr><tr><td>Dále ze zdrojů vyberte vztahy; vztahy se vždy vážou na dva subjekty nebo objekty práva. Stejně, jako u subjektů a objektů práva, se i ke vztahům doplňují výše zmíněné charakteristiky (název, definice, zdroj, popis).<br>V názvu vztahu je i alespoň jeden ze dvou pojmů, ke kterému se vztah váže – například <em>řídí vozidlo </em>namísto <em>řídí</em>.<br>Vztahy je vhodné využít pro kontrolu rozsahu slovníku. Pokud považujete slovník za hotový (resp. jste přesvědčeni, že zachycuje celou zvolenou oblast/část oblasti) a máte v něm pojem, který není s žádným jiným navázaný (vztahem ani nadřazeností), tak je s velkou pravděpodobností pojem přebytečný, nebo jsou vztahy ve slovníku chybně vyjádřeny.</td><td><a href="#_Ref181112665">5.14</a> <a href="#_Ref181112670">Vztahy</a></td></tr><tr><td rowspan="2">Konec iterace</td><td>Vytvořte <em>název </em>a <em>popis</em> slovníku. Z názvu by mělo být jasné, jakou oblast slovník popisuje. Popis obsahuje doplňující poznámky k vybraným zdrojům a/nebo účelům použití.</td><td rowspan="2"><a href="#_Ref181112708">5.18</a> <a href="#_Ref181112718">Publikace slovníku</a></td></tr><tr><td>Slovník zaregistrujte do lokálního katalogu dat, aby byl katalogizovaný i v Národním katalogu dat a následně využívejte podle dosažené úrovně popisu.</td></tr></tbody></table></div>

<span id="_Role_popisu_dat"></span><span id="_Role_potřebné_pro"></span><span id="_Výběr_oblasti_pro_1"></span><span id="_Toc180400080"></span><span id="_Ref181112126"></span><span id="_Ref181112135"></span><span id="_Ref181112200"></span><span id="_Ref181112203"></span><span id="_Toc185597980"></span><span id="_Toc228268009"></span><h2 id="vyber-oblasti-pro-popis-dat">Výběr oblasti pro popis dat</h2>

<p>Velikost oblastí se může řídit tím, jaké zdroje jsou pro ni k dispozici. Máte volbu členit oblasti například podle agend, procesů, nebo jednotlivých informačních systémů. Problematika vymezení věcných oblastí se více rozebírá v <a href="https://data.gov.cz/p%C5%99%C3%ADlohy/spr%C3%A1va-dat/Vymezen%C3%AD%20a%20prioritazice%20oblast%C3%AD.pdf">podpůrném materiálu správy dat 1.1-1: Vymezení a prioritizace věcných oblastí dat</a>. Tyto oblasti doporučujeme dále rozdělit na jednotlivé části – abyste si mohli popis rozvrhnout a publikovat postupně podle vašich schopností a kapacit.</p>

<span id="_Ref167015837"></span><p>Pro komentovaný příklad jsme si vybrali oblast řidičů, kde budeme popisovat <a href="https://www.zakonyprolidi.cz/cs/2000-361">zákon č. 361/2000 Sb. o provozu na pozemních komunikacích a o změnách některých zákonů</a>.<s> </s></p>

<span id="_Toc172732889"></span><span id="_Toc180400079"></span><span id="_Ref181112191"></span><span id="_Ref181112195"></span><span id="_Toc185597981"></span><span id="_Toc228268010"></span><h2 id="role-potrebne-pro-popis-dat">Role potřebné pro popis dat</h2>

<p>Tvorbě slovníku by se měly přinejmenším účastnit role:</p>

<ul>
<li>věcného znalce vybrané oblasti,</li>
<li>samotného tvůrce slovníku – za pomoci zdrojů a konzultací se znalcem vytváří slovník ve zvoleném nástroji.</li>
</ul>

<p>Obě role může naplňovat tatáž osoba. Popisu dat celého úřadu by se měly také věnovat role stanovené v sekci 2.1 <a href="motivace-popisu-dat#_Návaznost_na_správu">Návaznost na správu dat</a>, které koordinují, zprostředkovávají a zodpovídají za dodržení pravidel kvalitní správy dat.</p>

<span id="_Zdroje_popisu_dat_1"></span><span id="_Toc180400082"></span><span id="_Ref181112275"></span><span id="_Ref181112278"></span><span id="_Toc185597982"></span><span id="_Toc228268011"></span><h2 id="zdroje-popisu-dat">Zdroje popisu dat</h2>

<p>Hlavním předpokladem pro popis dat je sběr autoritativních zdrojů, ze kterých se pojmy slovníků budou vytvářet. Pojmy vždy mají nějaký zdroj – viz sekce <a href="#_Charakteristiky_pojmu_1">Charakteristiky pojmu</a>. Mezi hlavní druhy zdrojů patří:</p>

<ul>
<li><strong>Ustanovení </strong>zákona, vyhlášky, nebo usnesení. Ta přestavují<strong> </strong>oblíbený startovní bod pro popis dat, díky kterému je možné určit nejdůležitější pojmy a vztahy dané oblasti. Popis vlastností je však typicky poměrně omezený a někdy jsou ustanovení psána takovým způsobem, který umožňuje popis jen těch nejzákladnějších pojmů.</li>
<li><strong>Formuláře</strong>, které<strong> </strong>jsou velmi nápomocné pro určení vlastností i vztahů. Před jejich evidencí do datových slovníků by měl být potvrzen soulad s daty v informačních systémech veřejné správy.</li>
<li><strong>Metodické pokyny</strong><strong>,</strong><strong> směrnice</strong><strong> a řády</strong>, které<strong> </strong>jsou vhodné pro získání dalšího detailu z praktického využití zákona.</li>
<li><span id="_Podpora_ze_strany"></span><strong>Dokumentace informačních </strong><strong>systémů</strong><strong>.</strong> Dávejte si však pozor, abyste místo popisu věcných subjektů/objektů práva, vlastností a vztahů nepopisovali striktně provozní data anebo obecně aspekty databázového modelu navržené pro konkrétní informační systém – tato specifika do slovníků nepatří.<s> </s></li>
</ul>

<span id="_Toc180400083"></span><span id="_Toc185597983"></span><span id="_Toc228268012"></span><h3 id="pouzivani-databazovych-modelu-pro-popis-dat">Používání databázových modelů pro popis dat</h3>

<p>Jelikož tvorba slovníků (obzvlášť ve specializovaných nástrojích) připomíná tvorbu logických modelů nebo diagramů tříd a cílem datových slovníků je popsat data ISVS, je možné pro usnadnění popisu dat postupovat „odspodu“ a využít pojmy z existujících databázových schémat – např. názvy a definice tabulek a „sloupců“.</p>

<p>Je ovšem důležité vzít v potaz následující:</p>

<ul>
<li>Aby byl popis dat využitelný pro porozumění datům, jejich prezentaci netechnickému publiku a integraci s daty ostatních, musí být pojmy srozumitelné a řádně definované s pomocí zdrojů. Databázová schémata toto většinou nesplňují, navíc mohou obsahovat technická a provozní data, která nejsou relevantní pro datový popis, případně i duplicity. Je tak velmi pravděpodobné, že budete muset potřebné informace dále hledat v materiálech, které jsou zmíněny v podkapitole výše.</li>
<li>Záměrem slovníků je i to, aby se mohly do jejich tvorby a využívání zapojit i věcné (netechnicky založené) osoby. Tyto osoby mohou mít lepší věcný vhled do popisované oblasti (resp. dokáží lépe určit zdroje) a vědí, jak věcně navazují na jiné oblasti a jakým způsobem se dají využívat. Technický podklad může pro tyto osoby do popisu představit překážku k efektivní účasti na popisu.</li>
<li><em>Přímá</em> vazba na konkrétní návrh databáze není žádoucí, jelikož se může často měnit, a to nejen v závislosti na změně věcné podstaty uchovávaných dat - např. aktualizaci/změnách IS. Může podléhat také určitým podmínkám zamezujícím jeho zveřejnění (např. z důvodu ochrany duševního vlastnictví, kybernetické bezpečnosti), nebo může neoddělitelným způsobem zachycovat více nesourodých oblastí.</li>
</ul>

<span id="_Výběr_oblasti_pro"></span><span id="_Nástroje_pro_tvorbu"></span><span id="_Toc180400084"></span><span id="_Ref181112306"></span><span id="_Ref181112308"></span><span id="_Toc185597984"></span><span id="_Toc228268013"></span><h2 id="nastroje-pro-tvorbu-popisu-dat">Nástroje pro tvorbu popisu dat</h2>

<p>Aby byly slovníky strojově čitelné, je potřeba je tvořit v jednotném formátu. Pro slovníky byla proto vytvořena otevřená formální norma. Otevřené formální normy (OFN) jsou definovány v zákoně č. 106/1996 Sb. o svobodném přístupu k informacím. Jedná se o technická doporučení zaměřená na vybrané datové sady (slovníky, turistické cíle, úřední desky apod.), jejichž následování zajišťuje, že se stejná data publikovaná různými poskytovateli mohou jednoduše využívat nezávisle na tom, kdo je poskytl. Více informací naleznete na <a href="https://data.gov.cz/ofn/">https://data.gov.cz/ofn/</a>. Nejnovější verze otevřené formální normy pro slovníky (v době vydání této verze metodiky ve verzi draftu) se nachází na <a href="https://ofn.gov.cz/slovníky/">https://ofn.gov.cz/slovníky/</a>. Zveřejňování slovníků podle této OFN uloží jako povinnost připravovaný zákon o správě dat.</p>

<p><strong>T</strong><strong>vůrc</strong><strong>i</strong><strong> slovníků ale OFN</strong><strong> nemusí</strong><strong> nijak studovat.</strong> Připravili jsme několik způsobů a nástrojů, ve kterých je možné slovníky tvořit, aniž by bylo potřeba se v OFN orientovat nebo se příliš starat o technickou stránku popisu dat. Jde o:</p>

<ul>
<li>tabulkový popis (např. v Excelu),</li>
<li>nástroj Archi,</li>
<li>nástroj Enterprise Architect,</li>
<li>Výrobní linku.</li>
</ul>

<p>Vedle námi poskytnutých a podporovaných nástrojů lze využít i jiné. Jediný požadavek, který musí nástroje splnit je, že umožňují vytvořit soubor se slovníkem, který je kompatibilní s otevřenou formální normou pro slovníky.</p>

<aside class="methodology-callout methodology-callout--note">Aktuální informace, včetně šablon, návodů a doporučení pro jednotlivé nástroje naleznete na domovské stránce popisu dat: <a href="https://data.gov.cz/popis-dat">https://data.gov.cz/popis-dat</a>.</aside>

<span id="_Toc185597985"></span><span id="_Toc228268014"></span><h3 id="tabulka-pro-popis-dat">Tabulka pro popis dat<s> </s></h3>

<p>Tabulkové řešení jsme připravili především pro ty, kteří s popisem dat začínají a v úřadě nemají zkušenosti s nástroji na tvorbu popisu dat v grafické podobě (neboli s diagramy/pohledy). Tabulka je nejjednodušší řešení pro základní popis dat. Nevyžaduje vynaložení speciálních kapacit kromě znalce oblastí, které jste zvolili pro tvorbu slovníků. Berte však na vědomí, že s růstem počtu pojmů, vlastností a vztahů ale roste komplikovanost a klesá srozumitelnost tabulky. Šablona je připravena ve formátu XLSX (pro Microsoft Excel).<s> </s><s>  </s></p>

<span id="_Toc180400086"></span><span id="_Toc185597986"></span><span id="_Toc228268015"></span><h3 id="archi">Archi</h3>

<p><a href="https://www.archimatetool.com/">Archi</a> je nástroj na modelování v jazyku <a href="https://www.opengroup.org/archimate-forum/archimate-overview">ArchiMate</a>. Nástroj je zdarma ke stažení i k jakémukoliv využití (podle permisivní licence MIT) a dostupný je pro Windows, Linux i macOS. Jazyk ArchiMate se používá pro vyjádření architektury podniku. Mimo jiné i kvůli jeho otevřenosti a nezávislosti jej využívá odbor Hlavního architekta eGovernmentu (OHA) v žádostech o stanovisko projektů eGovernmentu – více informací na <a href="https://archi.gov.cz/uvod_schvalovani">https://archi.gov.cz/uvod_schvalovani</a>. Slovníky tak můžete tvořit i ve vazbě s vaší podnikovou architekturou.</p>

<aside class="methodology-callout methodology-callout--note">V žádostech o stanovisko OHA je potřeba uvádět i subjekty a objekty, jejichž data se zpracovávají v plánovaném informačním systému.</aside>

<p>Pro Archi jsme vytvořili šablonu pro popis dat, se kterou můžete začít nový projekt, nebo ji naimportujete do vašeho existujícího projektu.</p>

<span id="_Toc180400087"></span><span id="_Toc185597987"></span><span id="_Toc228268016"></span><h3 id="enterprise-architect">Enterprise Architect</h3>

<p><a href="https://sparxsystems.com/products/ea/index.html">Sparx Enterprise Architect</a> je oproti Archi komerční nástroj, který podporuje několik modelovacích jazyků, včetně ArchiMate a UML. Připravili jsme šablonu a MDG technologii pro popis dat, pomocí které můžete tvořit slovníky.</p>

<span id="_Výrobní_linka_1"></span><span id="_Toc180400088"></span><span id="_Toc185597988"></span><span id="_Toc228268017"></span><h3 id="vyrobni-linka">Výrobní linka</h3>

<aside class="methodology-callout methodology-callout--note">Výrobní linka je sada <em>prototypů</em> a není tedy momentálně možné garantovat stálou dostupnost těchto nástrojů.</aside>

<p><a href="https://slovník.gov.cz">Výrobní linka</a> je balíček softwarových nástrojů, vytvořený jako výstup projektu KODI (dokumentováno ve výstupech cíle 5 projektu), který slouží k vytváření slovníků a jejich následné publikaci. Jeho součástí jsou</p>

<ul>
<li>nástroje na tvorbu slovníků TermIT a OntoGrapher,</li>
<li>prohlížecí nástroj ShowIT,</li>
<li>nástroj pro tvorbu datových specifikací Dataspecer.</li>
</ul>

<p>Ukázku těchto nástrojů naleznete ve školení <a href="https://data.gov.cz/vzd%C4%9Bl%C3%A1v%C3%A1n%C3%AD/e-learning/modelov%C3%A1n%C3%AD-v%C3%BDznamu-dat-ve-ve%C5%99ejn%C3%A9-spr%C3%A1v%C4%9B/">Modelování popisu dat ve veřejné správě</a>.</p>

<span id="_Zdroje_popisu_dat"></span><span id="_Výrobní_linka"></span><span id="_Proces_popisu_dat"></span><span id="_Popis_dat_"></span><span id="_Toc185597989"></span><span id="_Toc228268018"></span><h2 id="uvedeni-prikladu">Uvedení příkladu</h2>

<p>Po výběru oblasti, zdrojů a nástroje můžeme začít se samotným popisem dat.</p>

<aside class="methodology-callout methodology-callout--note">Cílem příkladu je ukázat popis dat v praxi – negarantujeme soulad výsledného slovníku s aktuálními zákony a jinými zdroji z této oblasti.</aside>

<p>Zdroj jsme pro náš příklad vybrali jeden: <a href="https://www.e-sbirka.cz/sb/2000/361?zalozka=text">Zákon o provozu na pozemních komunikacích a o změnách některých zákonů (č. 361/2000 Sb.)</a>. Z tohoto zákona budeme postupně vytahovat subjekty a objekty práva, poté vlastnosti a na konec vztahy.</p>

<span id="_Subjekty_a_objekty_1"></span><span id="_Výběr_pojmů"></span><span id="_Toc180400092"></span><span id="_Ref181112330"></span><span id="_Ref181112371"></span><span id="_Toc185597990"></span><span id="_Toc228268019"></span><h2 id="vyber-pojmu">Výběr pojmů</h2>

<p>Podíváme-li se do zákona o silničním provozu, nalezneme §2, Vymezení základních pojmů. Podobný paragraf se vyskytuje v několika zákonech a představuje dobrý začátek pro vybrání těch nejdůležitějších pojmů. Například máme v tomto paragrafu písmeno d):</p>

<blockquote>řidič je účastník provozu na pozemních komunikacích, který řídí motorové nebo nemotorové vozidlo anebo tramvaj; řidičem je i jezdec na zvířeti,</blockquote>

<p>z čehož můžeme založit první pojem. Váš výběr si můžete zkontrolovat několika hrubými pravidly:</p>

<ul>
<li><strong>Sbírá</strong><strong>t</strong><strong>e v rámci </strong><strong>v</strong><strong>aší oblasti o daném pojmu data?</strong> Pokud se pojem objevuje v informačním systému, formuláři, výpisu, či jiných záznamech, je odpověď jednoznačně ano.</li>
<li><strong>Je pojem součástí nějaké hierarchie pojmů</strong><strong>? </strong>Jinými slovy, pomohlo by klasifikaci pojmů do jednotlivých kategorií, kdybychom pojem do slovníku zahrnuli? Více informací o hierarchickém řazení pojmů naleznete v podkapitole 5.11 <a href="#_Nadřazené_pojmy">Nadřazené pojmy</a>.</li>
<li><strong>Je pojem ve vztahu s nějakým jiným pojmem?</strong><strong> </strong>Tento požadavek slouží především jako kontrola správného rozsahu slovníku.<strong> </strong>V kapitole 4 <a href="základy-popisu-dat#_Proces_popisu_dat_1">Základy popisu dat</a> uvádíme, že pojmy vstupují s ostatními pojmy do věcných vztahů (žadatel <em>vlastní</em> silniční vozidlo, silniční vozidlo <em>je pojištěno</em> pojištěním). I když není nutné tyto vztahy formalizovat do minimálního slovníku, měli byste být schopni nějaký (alespoň základní) vztah určit (resp. říct, <em>proč</em> daný pojem patří do dané oblasti).</li>
</ul>

<aside class="methodology-callout methodology-callout--note">V této metodice se zaměřujeme na tvorbu slovníků určených pro evidenci dat v ISVS z určité oblasti (<em>datové slovníky</em><em> </em>dle Strategie). Existují však i další použití slovníků, např. jako výkladový slovník (neboli tezaurus), kde jsou kritéria pro zahrnutí pojmu do slovníku mnohem volnější. Slovníky popsané touto metodikou jsou vhodné pro oba případy.</aside>

<span id="_Subjekty_a_objekty_2"></span><span id="_Toc180400090"></span><span id="_Ref181112332"></span><span id="_Ref181112340"></span><span id="_Ref181112342"></span><span id="_Ref181112364"></span><span id="_Toc185597991"></span><span id="_Toc228268020"></span><h2 id="subjekty-a-objekty-prava">Subjekty a objekty práva</h2>

<p>Ve výkonu veřejné správy se běžně pracuje s daty nějakého subjektu práva a s ním souvisejícími objekty práva. Subjekty a objekty práva jako typy pojmů jsou hlavním předmětem popisu – další typy (vlastnosti a vztahy) je poté upřesňují a dodávají jim bližší kontext.</p>

<p><strong>Subjekt práva</strong> je osoba, která se účastní právních vztahů. Subjekt práva můžeme také definovat jako nositele práv a povinností. Tyto osoby působí na ostatní subjekty nebo objekty práva (viz níže) – činí, vykonávají svoji vůli. Příkladem jsou:</p>

<ul>
<li>lidé – žadatelé, studenti, děti, řidiči, cizinci,</li>
<li>organizace a soukromé subjekty – firmy, orgány veřejné moci, odbory,</li>
<li>role – provozovatelé, správci, dodavatelé.</li>
</ul>

<p><strong>Objekt práva</strong> je příčinou vstupu subjektu do právního vztahu. Každá „věc“, která je předmětem nějakého právního vztahu, je objektem práva. Působí na ni subjekty práva – objekty z hlediska veřejné správy nemají svoji vůli a nemohou ji tedy vykonávat. Příkladem jsou:</p>

<ul>
<li>aktiva a hmotné předměty – vozidla, nemovitosti, zvířata, informační systémy, duševní vlastnictví, energie, voda, suroviny, průkazy,</li>
<li>právní koncepty – agendy, osvědčení, práva, povinnosti, přestupky,</li>
<li>další abstraktní koncepty – služby, audity, pracoviště, databáze, informace.</li>
</ul>

<aside class="methodology-callout methodology-callout--good">Ve výše uvedeném příkladu řidiče z §2, písmena d) zákona o silničním provozu se jedná o subjekt práva (řidič je fyzická <em>osoba</em>, která se <em>účastn</em><em>í</em> provozu).</aside>

<span id="_Charakteristiky_pojmu_1"></span><span id="_Toc180400091"></span><span id="_Ref181112383"></span><span id="_Ref181112386"></span><span id="_Toc185597992"></span><span id="_Toc228268021"></span><h2 id="charakteristiky-pojmu">Charakteristiky pojmu</h2>

<p>Každý pojem, jak je naznačeno v kapitole 4 <a href="základy-popisu-dat#_Proces_popisu_dat_1">Základy popisu dat</a>, musí být zasazen do správného kontextu a řádně vysvětlen – jinak jde o pouhé pojmenování bez jasného významu. Pro toto upřesnění slouží vyplnění následujících charakteristik k danému pojmu:</p>

<ul>
<li><strong>Název: </strong>Jedná se o jednoznačný název pojmu, je spisovný, bez použití zkratek a v prvním pádu jednotného čísla: „<em>Řidič</em>“.</li>
<li><strong>Zdroj: </strong>Dokument a jeho část, v níž je pojem definován. Odstavec zákona, strana metodiky apod. Uvedení zdroje je důležité nejen pro dohledání významu, ale i pro zdůvodnění některých skutečností (např.: Z jakého důvodu data popsaná pojmem evidujete?) Pokud možno se uvádí jako odkaz URL na konkrétní dokument, nejlépe přímo na sekci dokumentu/stránky: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-04-01/dokument/norma/cast_1/hlava_1/par_2/pism_d"><em>§ 2 písm. d) zákona č. 361/2000 Sb. o silničním provozu</em></a><em> </em>(odkaz na e-Sbírku).</li>
<li><strong>Definice: </strong>Text přímo vyňatý ze zdroje, který stanovuje přesný význam pojmu – „<em>účastník provozu na pozemních komunikacích, který řídí motorové nebo nemotorové vozidlo anebo tramvaj; řidičem je i jezdec na zvířeti</em>“.</li>
<li><strong>Popis: </strong>„Zjednodušený“ (relativně k definici) výklad nebo doplňující poznámky, který je vytvořený přímo pro pojem (tj. píše ho tvůrce pojmu a nemusí tedy pocházet z nějakého zdroje): <em>Řidič je tedy i</em><em> </em><em>cyklista, nejen řidič motorových vozidel – neváže se na něj nutně řidičské oprávnění.</em></li>
</ul>

<aside class="methodology-callout methodology-callout--good">Výsledný pojem „Řidič“ by tedy vypadal následovně:</aside>

<aside class="methodology-callout methodology-callout--good"><strong>Řidič</strong><em><br></em><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-04-01/dokument/norma/cast_1/hlava_1/par_2/pism_d">§ 2 písm. d) zákona č. 361/2000 Sb. o silničním provozu</a> <em><br></em><em>definice: </em>účastník provozu na pozemních komunikacích, který řídí motorové nebo nemotorové vozidlo anebo tramvaj; řidičem je i jezdec na zvířeti<br><em>popis: </em>Řidič je tedy i cyklista, nejen řidič motorových vozidel – neváže se na něj nutně řidičské oprávnění.<br><em>typ:</em> Subjekt práva</aside>

<aside class="methodology-callout methodology-callout--note">Vždy rozvádějte název pojmu a nedávejte do názvu zkratky. Pište „Fyzická osoba“, ne FO, „Identifikační číslo osoby“, ne IČO. Pamatujte, že vaše pojmy mají být dohledatelné a použitelné napříč oblastmi, agendami, informačními systémy atd. I v na první pohled jednoznačných pojmech může totiž vzniknout nejasnost a nepořádek, obzvlášť když se stejným/podobným názvem označuje větší množství pojmů z různých oblastí.</aside>

<p>Dále si vybereme ve stejném paragrafu písmeno f):</p>

<blockquote>vozidlo je motorové vozidlo, nemotorové vozidlo nebo tramvaj,</blockquote>

<p>Protože vozidlo samo o sobě z právního hlediska nevykonává svou vůli (nepůsobí, nýbrž je na něj působeno), jde o objekt práva. Pojem do slovníku zavedeme stejně, jako „Řidič“:</p>

<aside class="methodology-callout methodology-callout--good"><strong>Vozidlo</strong><strong><br></strong><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-07-01/dokument/norma/cast_1/hlava_1/par_2/pism_f">§ 2 písm. f) zákona č. 361/2000 Sb.</a> <em><br>definice: </em>motorové vozidlo, nemotorové vozidlo nebo tramvaj<strong><br></strong><em>typ:</em> Objekt práva</aside>

<aside class="methodology-callout methodology-callout--note">Příklad pojmů, které nebudeme uvádět do našeho příkladového slovníku, jsou konkrétní práva a povinnosti, situace, nebo příliš obecné pojmy (snížená viditelnost, pokyn zastavit, boční sezení na motocyklu, krajnice apod.). Jejich uvedení není chybou, ale v našem příkladě to není něco, o čem bychom měli nebo chtěli mít data (např. nevedeme evidenci všech jednotlivých zastavení jednotlivých vozidel).</aside>

<p>Pro účely příkladu popisu zavedeme ještě pojem „Řidičský průkaz“ z paragrafu 103:</p>

<aside class="methodology-callout methodology-callout--good"><strong>Řidičský průkaz</strong><strong><br></strong><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-07-01/dokument/norma/cast_1/hlava_3/dil_2/par_103/odst_1">§ 103 odst. 1 zákona č. 361/2000 Sb.</a> <em><br></em><em>definice: </em>Řidičský průkaz je veřejná listina, která osvědčuje řidičské oprávnění držitele a jeho rozsah a kterou držitel prokazuje své jméno, příjmení a podobu, jakož i další údaje v ní zapsané podle tohoto zákona.<strong> </strong><strong><br></strong><em>typ:</em> Objekt práva</aside>

<span id="_Nadřazené_pojmy"></span><span id="_Toc180400093"></span><span id="_Ref181112396"></span><span id="_Ref181112477"></span><span id="_Ref181112479"></span><span id="_Toc185597993"></span><span id="_Toc228268022"></span><h2 id="nadrazene-pojmy">Nadřazené pojmy</h2>

<p>V zákoně si můžete všimnout, že se některé pojmy používají v definici dalších pojmů, například:</p>

<blockquote>řidič je <strong>účastník provozu na pozemních komunikacích</strong>, […]<br>Řidičský průkaz je <strong>veřejná listina</strong>, […]</blockquote>

<p>Je vidět, že se pojmy řadí do určité hierarchie. Podle zákona existuje několik druhů účastníků provozu na pozemních komunikacích – jedním příkladem je řidič (každý řidič je účastník provozu, ale každý účastník provozu není řidič). Pro takovéto situace existuje pojmová charakteristika <em>nadřazenosti</em>. Pojem A je nadřazený pojmu B, pokud každý příklad spadající pod pojem A zároveň spadá pod pojem B, ale pojem B dále upřesňuje pojem A nebo jej rozděluje na jednotlivé podtypy.</p>

<aside class="methodology-callout methodology-callout--good">Pro pojem „Řidič“ je nadřazený pojem „Účastník provozu na pozemních komunikacích“ z paragrafu 2, písmena a): Každý řidič je zároveň účastníkem provozu, ale opačně to neplatí – každý účastník provozu není vždy řidič.</aside>

<p>V definici pojmu „Vozidlo“ z předchozí podkapitoly si však můžete všimnout, že se tu hovoří o možných „variantách“: motorové vozidlo, nemotorové vozidlo, nebo tramvaj. Oproti řidiči a účastníku provozu se tu uvádí obrácená vazba, tj. že tyto tři pojmy jsou podřazené pojmu „Vozidlo“ (každé motorové vozidlo, nemotorové vozidlo a tramvaj je vozidlo).</p>

<span id="_Toc180400094"></span><span id="_Toc185597994"></span><span id="_Toc228268023"></span><h2 id="nejednoznacne-definovane-pojmy">Nejednoznačně definované pojmy</h2>

<p>Občas se zdroje potýkají s pojmy, které nejsou přímo definovány. V zákoně o silničním provozu je to například řidič evidovaný v registru řidičů, zmíněný v §119 odst. 2:</p>

<blockquote>Registr řidičů obsahuje a) osobní údaje o řidiči motorového vozidla uvedené v řidičském průkazu a v mezinárodním řidičském průkazu, včetně digitalizované fotografie a digitalizovaného podpisu řidiče,</blockquote>

<p>Kromě registru řidičů se v tomto odstavci hovoří o řidičích motorového vozidla – přesněji těch, kteří mají (mezinárodní) řidičský průkaz a jsou v evidenci registru řidičů. To je však dostatečně identifikovatelná skupina, pro kterou již lze založit pojem. Charakteristika pojmu <em>p</em><em>opis</em> v této situaci hraje důležitou roli – v každém případě by mělo být jasné, co pod pojem „Řidič evidovaný v registru řidičů“ spadá:</p>

<aside class="methodology-callout methodology-callout--good"><strong>Řidič evidovaný v registru řidičů</strong><strong><br></strong><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-07-01/dokument/norma/cast_1/hlava_4/par_119/odst_2/pism_a">§ 119 odst. 2 písm. a) zákona č. 361/2000 Sb.<br></a><em>popis</em>: Registr řidičů obsahuje osobní údaje o řidičích motorových vozidel uvedené v řidičských průkazech.<br><em>nadřazený pojem</em>: Řidič<br><em>typ</em>: Subjekt práva</aside>

<span id="_Vlastnosti_1"></span><span id="_Toc180400098"></span><span id="_Toc180400095"></span><aside class="methodology-callout methodology-callout--note">Pokud existuje stejné označení (název „Řidič“) pro různé definice („Řidič“ jako řidič motorových vozidel a „Řidič“ jako řidič podle definice zákona), tak se jedná o více pojmů! Více pojmů se stejným názvem nemůže být v jednom slovníku – podobně jako nedává smysl ve stejné oblasti mít stejný název pro více typů „věcí“.</aside>

<p>Podobně se například v § 105 odst. 1 písmeno i) mluví o úřadě vydávajícím řidičské průkazy:</p>

<blockquote>i) název a sídlo úřadu, který řidičský průkaz vydal,</blockquote>

<p>Pokud zákon budeme pročítat dále, uvidíme, že se jedná o obecní úřad obce s rozšířenou působností. Ten v zákoně není přesně definován, ale v paragrafech je dostatek informací pro vytvoření pojmu:</p>

<aside class="methodology-callout methodology-callout--good"><strong>O</strong><strong>becní úřad obce s rozšířenou působností</strong><br><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-10-01/dokument/norma/cast_1/hlava_3/dil_2/par_109/odst_3">§ 109 odst. 3 zákona č. 361/2000 Sb.</a><br><em>popis</em>: Úřad vydávající řidičský průkaz je vždy obecním úřadem obce s rozšířenou působností.<br><em>typ</em>: Subjekt práva</aside>

<span id="_Ekvivalentní_pojmy_1"></span><span id="_Vlastnosti"></span><span id="_Ref181112689"></span><span id="_Ref181112698"></span><span id="_Toc185597995"></span><span id="_Toc228268024"></span><h2 id="vlastnosti">Vlastnosti</h2>

<p><strong>Vlastnosti</strong> (neboli <em>údaje</em>) jsou, stejně jako jednotlivá políčka ve formuláři, zachycením typů informací o daném subjektu nebo objektu práva. Vlastnosti určují, co všechno o daném subjektu nebo objektu práva vedeme (resp. co za políčka máme) a jak (jak se má políčko vyplňovat). I u vlastností chceme název a ideálně i zdroj, definici a popis. U vlastností je popis obzvlášť důležitý, protože také potřebujeme uvést, jak se „políčko“ má vyplňovat.</p>

<p>Každá vlastnost se musí vázat na jeden konkrétní subjekt nebo objekt práva. To znamená, že pokud máte vlastnosti, které evidujete/potřebujete evidovat a nemáte pro ně subjekt nebo objekt práva, měli byste založit nový a k němu vlastnost přiřadit.</p>

<aside class="methodology-callout methodology-callout--bad">Dávejte si pozor, abyste vlastností nepopisovali samostatný subjekt/objekt práva. Například „Provozovatel vozidla“ není vlastností „Vozidla“ – „Provozovatel“ je samostatný subjekt práva.</aside>

<p>Vlastností by se měla popisovat základní jednotka dat (individuální datumy, názvy, příznaky apod.). Důležitá forma sebekontroly evidence vlastností je představit si konkrétní hodnotu takové vlastnosti (kdyby byla vlastnost vyjádřená jako políčko ve formuláři, jak by vypadal vyplněný vzor?).</p>

<aside class="methodology-callout methodology-callout--note">Rodné číslo je vlastnost pro subjekt práva „Fyzická osoba“, což je (jedno) desetimístné číslo. 7808243949 je konkrétní rodné číslo pro konkrétní subjekt práva Jan Novák.</aside>

<p>Pokud jste uvedli k subjektu nebo objektu práva nadřazený pojem, tak se vlastnosti z tohoto nadřazeného pojmu automaticky přebírají z nadřazeného pojmu. Je to jeden z primárních nástrojů pro zajištění, abyste se ve slovnících opakovali co nejméně.</p>

<p>Z rozpracovaného zákona o silničním provozu můžeme vybrat dvě vlastnosti pro „Řidičský průkaz“:</p>

<aside class="methodology-callout methodology-callout--good"><strong>Jméno držitele řidičského průkazu</strong><br><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-07-01/dokument/norma/cast_1/hlava_3/dil_2/par_105/odst_1/pism_a">§ 105 odst. 1 písm. a) zákona č. 361/2000 Sb.</a> <br><em>popis</em>: Řidičský průkaz obsahuje mj. jméno držitele.<br><em>typ</em>: Vlastnost pojmu Řidičský průkaz</aside>

<aside class="methodology-callout methodology-callout--good"><strong>Příjmení držitele řidičského průkazu</strong><br><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-07-01/dokument/norma/cast_1/hlava_3/dil_2/par_105/odst_1/pism_a">§ 105 odst. 1 písm. a) zákona č. 361/2000 Sb.</a> <br><em>popis</em>: Řidičský průkaz obsahuje mj. příjmení držitele.<br><em>typ</em>: Vlastnost pojmu Řidičský průkaz</aside>

<aside class="methodology-callout methodology-callout--bad">Vlastnost nesmí kombinovat více jednotek informací najednou, tj. nelze vytvořit vlastnost „Jméno a příjmení žadatele o řidičské oprávnění“.</aside>

<p>V názvu vlastnosti je i pojem, ke kterému se vlastnost vztahuje. Zajišťujeme tak splnění požadavku na neopakující se názvy pojmů ve slovníku a jednoznačněji určujeme, k čemu vlastnost patří.</p>

<aside class="methodology-callout methodology-callout--bad">Vlastnostmi nejsou provozní data informačních systémů – provozní identifikátory, databázové klíče apod.</aside>

<p>Paragraf 105 odst. 1 písmeno i) uvádí, že mezi informacemi na řidičském průkazu je také:</p>

<blockquote>i) název a sídlo úřadu, který řidičský průkaz vydal,</blockquote>

<p>z čehož nám zdánlivě vznikají dvě vlastnosti. První je název úřadu. Protože z předchozích pojmů víme, že se zde mluví přesně o obecním úřadu obce s rozšířenou působností, můžeme přiřadit název přímo k danému pojmu:</p>

<aside class="methodology-callout methodology-callout--good"><strong>Název </strong><strong>obecního úřadu obce s rozšířenou působností</strong><br><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-10-01/dokument/norma/cast_1/hlava_3/dil_2/par_105/odst_1/pism_i">§ 105 odst. 1 písm. i) zákona č. 361/2000 Sb.</a><br><em>popis</em>: Řidičský průkaz obsahuje název úřadu, který řidičský průkaz vydal (což je vždy obecní úřad obce s rozšířenou působností).<br><em>typ</em>: Vlastnost pojmu Obecní úřad obce s rozšířenou působností</aside>

<p>Dále, adresa sídla se skládá z více prvků – pokud se podíváme na formulář žádosti o řidičský průkaz, adresa má hned několik dílčích vlastností: ulice, číslo orientační, číslo popisné, poštovní směrovací číslo atd. Jak bylo zmíněno výše, <strong>v</strong><strong>lastnosti nemohou mít </strong><strong>své </strong><strong>dílčí</strong><strong> </strong><strong>vlastnosti</strong> – měly by zachycovat co nejmenší možné „políčko“ formuláře. Proto „Adresa“ není vlastnost, ale objekt práva, pod který spadají výše zmíněné „části“ adresy jako vlastnosti.</p>

<aside class="methodology-callout methodology-callout--note">Díky evidenci adresy jako objektu práva navíc dovolíme, aby ostatní pojmy, které nějakým způsobem využívají adresu, se na ní navázaly také. Díky tomu se nemusí duplicitně uvádět všechny položky adresy u každého subjektu/objektu práva.</aside>

<p>Navázání této adresy na jiné subjekty nebo objekty práva zprostředkovávají vztahy.</p>

<span id="_Vztahy"></span><span id="_Toc180400096"></span><span id="_Ref181112665"></span><span id="_Ref181112670"></span><span id="_Toc185597996"></span><span id="_Toc228268025"></span><h2 id="vztahy">Vztahy</h2>

<p><strong>Vztah</strong> věcně propojuje jeden subjekt nebo objekt práva s jiným subjektem nebo objektem práva.</p>

<aside class="methodology-callout methodology-callout--note">Pojem „řídí vozidlo“ je vztah mezi subjektem práva „Řidič“ a objektem práva „Vozidlo“. Řízení vozidla Škoda 120L Janem Novákem je konkrétní příklad vztahu mezi Janem Novákem (příklad subjektu práva „Řidič“) a Škoda 120L (příklad objektu práva „Vozidlo“).</aside>

<aside class="methodology-callout methodology-callout--bad">Vyhýbejte se vztahům typu „má vlastnost“ – vlastnosti se k subjektům a objektům práva v podporovaných nástrojích připisují jinými způsoby.</aside>

<p>I u vztahů chceme název a ideálně i zdroj, definici a popis. Tyto charakteristiky vztahů jsou nezbytné, neboť dva pojmy mohou být souběžně ve vztazích různých typů (je manželem, partnerem, rodičem apod.).</p>

<p>Vhodná pomůcka pro tvoření vztahů je, že si představíte větu ve formátu [pojem] [vztah] [pojem], například „Řidič“ <em>řídí vozidlo</em> „Vozidlo“. V názvu vztahu je i pojem, na který se vztah váže. Zajišťujeme tak, že se názvy pojmů ve slovníku neopakují a jednoznačně určujeme, k čemu vztah patří. Doporučujeme názvy psát v rodu činném, nebo přinejmenším rod činný a trpný v rámci slovníku nemíchat.</p>

<p>V rámci našeho příkladu jsme evidovali několik subjektů a objektů práva, které už podle vyňatých definic jsou v nějakém věcném vztahu:</p>

<aside class="methodology-callout methodology-callout--good"><strong>ř</strong><strong>ídí vozidlo</strong><strong><br></strong><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-04-01/dokument/norma/cast_1/hlava_1/par_2/pism_d">§ 2 písm. d) zákona č. 361/2000 Sb. o silničním provozu</a> <br><em>definice: </em>řidič je<em> </em>účastník provozu na pozemních komunikacích, který řídí motorové nebo nemotorové vozidlo anebo tramvaj; řidičem je i jezdec na zvířeti<strong><br></strong><em>typ:</em> Vztah mezi Řidič a Vozidlo</aside>

<aside class="methodology-callout methodology-callout--good"><strong>d</strong><strong>rží řidičský průkaz</strong><strong><br></strong><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-07-01/dokument/norma/cast_1/hlava_4/par_119/odst_2/pism_a">§ 119 odst. 2 písm. a) zákona  č. 361/2000 Sb.</a> <br><em>definice: </em>Registr řidičů obsahuje a) osobní údaje o řidiči motorového vozidla uvedené v řidičském průkazu a v mezinárodním řidičském průkazu, včetně digitalizované fotografie a digitalizovaného podpisu řidiče,<br><em>popis: </em>Z definice vyplývá, že řidiči, kteří jsou evidováni v registru řidičů, jsou držiteli řidičského průkazu.<strong><br></strong><em>typ:</em> Vztah mezi Řidič evidovaný v registru řidičů a Řidičský průkaz</aside>

<p>Daný vztah nemusí platit pro všechna konkrétní data. Kdybychom udělali stejný vztah <em>drží řidičský průkaz</em> mezi obecným „Řidičem“ jako účastníkem provozu a „Řidičským průkazem“, tak tím říkáme, že každý řidič může (ale nemusí) mít řidičský průkaz. Podle toho vytvářejte názvy vztahů – není potřeba uvádět „<em>může</em><em>“</em> <em>vlastnit řidičský průkaz</em> – <em>může</em> se implikuje. Jelikož je ale tento vztah mezi „Řidič evidovaný v registru řidičů“ a „Řidičský průkaz“ jasnější, uvádíme ho v podobě výše.</p>

<p>Pomocí vztahů si můžete ověřit naplnění požadovaného rozsahu popisu dat. Pokud považujete slovník za hotový (resp. jste přesvědčeni, že zachycuje celou zvolenou oblast/část oblasti) a máte v něm pojem, který není s žádným jiným provázaný (vztahem ani nadřazeností), je tento pojem s velkou pravděpodobností přebytečný, nebo jsou vztahy ve slovníku chybně vyjádřeny. S tím bychom si mohli uvědomit, že jsme zapomněli zavést vztah mezi „Obecní úřad obce s rozšířenou působností“ a „Řidičský průkaz“:</p>

<aside class="methodology-callout methodology-callout--good"><strong>vydává řidičský průkaz </strong><strong><br></strong><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-10-01/dokument/norma/cast_1/hlava_3/dil_2/par_109/odst_3">§ 109 odst. 3 zákona č. 361/2000 Sb.</a><strong><br></strong><em>definice</em>: Řidičský průkaz vydá příslušný obecní úřad obce s rozšířenou působností na žádost držitele řidičského oprávnění.<br><em>popis</em>: Z definice vyplývá, že řidiči, kteří jsou evidovaní v registru řidičů, mohou být držiteli řidičského průkazu.<br><em>typ</em>: Vztah mezi Obecní úřad obce s rozšířenou působností a Řidičský průkaz</aside>

<p>Při pojmenovávání vztahů dbejte na to, abyste nechali co nejmenší prostor pro různé interpretace významu vztahu.</p>

<aside class="methodology-callout methodology-callout--bad">Nevytvářejte nespecificky pojmenované vztahy („je součástí“, „je“, „se skládá z“, „tvoří“, „řeší“ apod.) – je to relativně nejasné vyjádření významu („je součástí“ proč? V jakém slova smyslu?). Místo toho používejte specifické názvy – například „provozuje“, „podává zprávu“, „vydává“, „schvaluje“ apod.</aside>

<p>V podkapitole 5.13 <a href="#_Vlastnosti">Vlastnosti</a> jsme diskutovali potenciální vztah mezi adresou a „Úřadem vydávajícím řidičské průkazy“. Pojem „Adresa“ je již definovaný v <a href="https://www.e-sbirka.cz/eli/cz/sb/2009/111/2024-07-01/dokument/norma/cast_1/hlava_4/par_29/odst_1/pism_h">§ 29 odst. 1 písm. h) zákona č. 111/2009 Sb., o základních registrech</a>, který je vzhledem k jeho navázání na základní registry (jejichž data jsou velkou skupinou informačních systémů využívány) nanejvýše relevantní. Pokud je tento zákon popsaný jiným slovníkem, je nejjednodušší použít již definovaný pojem.</p>

<span id="_Využití_pojmů_z"></span><span id="_Toc180400097"></span><span id="_Toc185597997"></span><span id="_Toc228268026"></span><h2 id="vyuziti-pojmu-z-jinych-slovniku">Využití pojmů z jiných slovníků</h2>

<p>Používání pojmů z jiných slovníků je jedna z nejdůležitějších možností, které slovníky přinášejí. Valná většina oblastí veřejné správy je propojena s jinou oblastí. Dále celá veřejná správa pracuje s několika základními pojmy (například „Fyzická osoba“, „Adresa“, „Dokument“ apod.). Proto se můžete při tvorbě slovníků odkazovat na pojmy mimo váš slovník – ať už se nacházejí na jednom konci vztahu nebo jsou součástí nadřazenosti.</p>

<p>Každý <strong>publikovaný</strong> pojem (více viz <a href="#_Ref181374123">5.18</a> <a href="#_Publikace_slovníků">Publikace slovníku</a>) má svůj vlastní jednoznačný identifikátor – IRI (podobné webové adrese s diakritikou). Díky IRI se může pojem využívat v ostatních slovnících, aniž by se musel kopírovat do cílového slovníku a také nedojde ke ztrátě kontextu a informací o daném pojmu.</p>

<p>Příkladů z oblasti řidičů je několik. Zmínili jsme „Adresu“, která <a href="https://xn--slovnk-7va.gov.cz/prohl%C3%AD%C5%BE%C3%ADme/pojem?iri=https://slovn%C3%ADk.gov.cz/legislativn%C3%AD/sb%C3%ADrka/111/2009/pojem/adresa">je definována ve slovníku zákona o základních registrech</a>, kde je i napojena na adresní místo RÚIAN.</p>

<aside class="methodology-callout methodology-callout--good">Výsledný vztah mezi „Obecním úřadem obce s rozšířenou působností“ a „Adresou“ by tedy vypadal následovně:</aside>

<aside class="methodology-callout methodology-callout--good"><strong>sídlí</strong><strong> na adrese</strong><strong><br></strong><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-10-01/dokument/norma/cast_1/hlava_3/dil_2/par_105/odst_1/pism_i">§ 105 odst. 1 písm. i) zákona č. 361/2000 Sb.</a><br><em>popis</em><em>: </em>Sídlo úřadu vydávajícího průkaz (obecním úřadem ORP) se nachází na nějaké adrese. Adresa je obecně definována v zákoně o základních registrech.<strong><br></strong><em>typ:</em> Vztah mezi Obecní úřad obce s rozšířenou působností a <a href="https://xn--slovnk-7va.gov.cz/prohl%C3%AD%C5%BE%C3%ADme/pojem?iri=https://slovn%C3%ADk.gov.cz/legislativn%C3%AD/sb%C3%ADrka/111/2009/pojem/adresa">Adresa ze slovníku zákona č. 111/2009 Sb., o základních registrech</a></aside>

<aside class="methodology-callout methodology-callout--note">DIA spravuje a publikuje slovník obecných pojmů veřejného sektoru, ve kterém jsou obecné pojmy, které jsou často používány napříč agendami veřejné správy (například Osoba, Dokument, Subjekt práva). Tento slovník se vyskytuje ve všech šablonách pro nástroje pro tvorbu popisu dat a je určen právě k použití v rámci jiných slovníků. Pojmy ze slovníku obecných pojmů veřejného sektoru slouží jako pojmy <em>nadřazené</em><em> </em>vámi vytvořeným pojmům.</aside>

<span id="_Ekvivalentní_pojmy"></span><span id="_Toc180400099"></span><span id="_Toc185597998"></span><span id="_Toc228268027"></span><h2 id="kompletni-priklad-slovniku">Kompletní příklad slovníku</h2>

<p>Zde jsou uvedeny pojmy celé iterace slovníku, který byl vytvářen v předchozích sekcích.<em> </em>U všech zdrojů je uveden i odkaz ve formátu <a href="https://eur-lex.europa.eu/content/help/eurlex-content/eli.html?locale=cs">ELI</a> na příslušnou část zákona v <a href="https://www.e-sbirka.cz/">e-Sbírce</a>. Příklady vytvoření tohoto slovníku v podporovaných nástrojích jsou uvedeny v návodech pro popis dat v těchto nástrojích.</p>

<p><strong>Řidič</strong><em><br></em><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-04-01/dokument/norma/cast_1/hlava_1/par_2/pism_d">§ 2 písm. d) zákona č. 361/2000 Sb. o silničním provozu</a> <em><br></em><em>definice: </em>účastník provozu na pozemních komunikacích, který řídí motorové nebo nemotorové vozidlo anebo tramvaj; řidičem je i jezdec na zvířeti<br><em>popis: </em>Řidič je tedy i cyklista, nejen řidič motorových vozidel – neváže se na něj nutně řidičské oprávnění.<em><br></em><em>nadřazený pojem</em>: Účastník provozu na pozemních komunikacích<br><em>typ:</em> Subjekt práva</p>

<p><strong>Vozidlo</strong><strong><br></strong><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-07-01/dokument/norma/cast_1/hlava_1/par_2/pism_f">§ 2 písm. f) zákona č. 361/2000 Sb.</a> <em><br>definice: </em>motorové vozidlo, nemotorové vozidlo nebo tramvaj<strong><br></strong><em>typ:</em> Objekt práva</p>

<p><strong>Účastník provozu na pozemních komunikacích</strong><em><br></em><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-07-01/dokument/norma/cast_1/hlava_1/par_2/pism_a">§ 2 písm. a) zákona č. 361/2000 Sb. o silničním provozu</a><em><br></em><em>definice: </em>každý, kdo se přímým způsobem účastní provozu na pozemních komunikacích<br><em>typ:</em> Subjekt práva</p>

<p><strong>Řidič</strong><strong> evidovaný v registru řidičů</strong><em><br></em><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-07-01/dokument/norma/cast_1/hlava_4/par_119/odst_2/pism_a">§ 119 odst. 2 písm. a) zákona č. 361/2000 Sb.</a><em><br></em><em>definice: </em>Registr řidičů obsahuje a) osobní údaje o řidiči motorového vozidla uvedené v řidičském průkazu a v mezinárodním řidičském průkazu, včetně digitalizované fotografie a digitalizovaného podpisu řidiče,<em><br></em><em>nadřazený pojem</em>: Řidič<br><em>typ:</em> Subjekt práva</p>

<p><strong>Řidičský průkaz</strong><strong><br></strong><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-07-01/dokument/norma/cast_1/hlava_3/dil_2/par_103/odst_1">§ 103 odst. 1 zákona č. 361/2000 Sb.</a> <em><br></em><em>definice: </em>Řidičský průkaz je veřejná listina, která osvědčuje řidičské oprávnění držitele a jeho rozsah a kterou držitel prokazuje své jméno, příjmení a podobu, jakož i další údaje v ní zapsané podle tohoto zákona.<strong> </strong><strong><br></strong><em>typ:</em> Objekt práva</p>

<p><strong>Obecní úřad obce s rozšířenou působností</strong> <br>zdroj: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-10-01/dokument/norma/cast_1/hlava_3/dil_2/par_109/odst_3">§ 109 odst. 3 zákona č. 361/2000 Sb.</a><br>popis: Úřad vydávající řidičský průkaz je vždy obecním úřadem obce s rozšířenou působností.<br>typ: Subjekt práva</p>

<p><strong>Jméno </strong><strong>držitele</strong><strong> řidičského</strong><strong> průkazu</strong><strong><br></strong><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-07-01/dokument/norma/cast_1/hlava_3/dil_2/par_105/odst_1/pism_a">§ 105 odst. 1 písm. a) zákona č. 361/2000 Sb.</a> <br><em>popis</em>: Řidičský průkaz obsahuje mj. jméno a příjmení držitele.<strong><br></strong><em>typ:</em> Vlastnost pojmu Řidičský průkaz</p>

<p><strong>Příjmení držitele</strong><strong> řidičského</strong><strong> průkazu</strong><strong><br></strong><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-07-01/dokument/norma/cast_1/hlava_3/dil_2/par_105/odst_1/pism_a">§ 105 odst. 1 písm. a) zákona č. 361/2000 Sb.</a> <br><em>popis</em>: Řidičský průkaz obsahuje mj. jméno a příjmení držitele.<strong><br></strong><em>typ:</em> Vlastnost pojmu Řidičský průkaz</p>

<p><strong>Název </strong><strong>o</strong><strong>becní</strong><strong>ho</strong><strong> úřad</strong><strong>u</strong><strong> obce s rozšířenou působností</strong><br><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-10-01/dokument/norma/cast_1/hlava_3/dil_2/par_105/odst_1/pism_i">§ 105 odst. 1 písm. i) zákona č. 361/2000 Sb.</a><br><em>popis</em>: Řidičský průkaz obsahuje název úřadu, který řidičský průkaz vydal (což je vždy obecní úřad obce s rozšířenou působností).<br><em>typ</em>: Vlastnost pojmu Obecní úřad obce s rozšířenou působností</p>

<p><strong>d</strong><strong>rží řidičský průkaz </strong><strong><br></strong><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-07-01/dokument/norma/cast_1/hlava_4/par_119/odst_2/pism_a">§ 119 odst. 2 písm. a) zákona  č. 361/2000 Sb.</a> <br><em>definice: </em>Registr řidičů obsahuje a) osobní údaje o řidiči motorového vozidla uvedené v řidičském průkazu a v mezinárodním řidičském průkazu, včetně digitalizované fotografie a digitalizovaného podpisu řidiče,<br><em>popis:</em><em> </em>Z definice vyplývá, že řidiči, kteří jsou evidováni v registru řidičů, mohou být držiteli řidičského průkazu.<strong><br></strong><em>typ:</em> Vztah mezi Řidič evidovaný v registru řidičů a Řidičský průkaz</p>

<p><strong>ř</strong><strong>ídí vozidlo</strong><strong><br></strong><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-04-01/dokument/norma/cast_1/hlava_1/par_2/pism_d">§ 2 písm. d) zákona č. 361/2000 Sb. o silničním provozu</a> <br><em>definice: </em>řidič je<em> </em>účastník provozu na pozemních komunikacích, který řídí motorové nebo nemotorové vozidlo anebo tramvaj; řidičem je i jezdec na zvířeti<strong><br></strong><em>typ:</em> Vztah mezi Řidič a Vozidlo</p>

<p><strong>vydává řidičský průkaz </strong><strong><br></strong>zdroj: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-10-01/dokument/norma/cast_1/hlava_3/dil_2/par_109/odst_3">§ 109 odst. 3 zákona č. 361/2000 Sb.</a><strong><br></strong>definice: Řidičský průkaz vydá příslušný obecní úřad obce s rozšířenou působností na žádost držitele řidičského oprávnění.<br>popis: Z definice vyplývá, že řidiči, kteří jsou evidováni v registru řidičů, mohou být držiteli řidičského průkazu.<br>typ: Vztah mezi Řidič evidovaný v registru řidičů a Řidičský průkaz</p>

<span id="_Toc180400100"></span><p><strong>sídlí</strong><strong> na adrese</strong><strong><br></strong><em>zdroj</em>: <a href="https://www.e-sbirka.cz/eli/cz/sb/2000/361/2024-10-01/dokument/norma/cast_1/hlava_3/dil_2/par_105/odst_1/pism_i">§ 105 odst. 1 písm. i) zákona č. 361/2000 Sb.</a><br><em>popis</em><em>: </em>Sídlo úřadu vydávajícího průkaz (obecním úřadem ORP) se nachází na nějaké adrese. Adresa je obecně definována v zákoně o základních registrech.<strong><br></strong><em>typ:</em> Vztah mezi Obecní úřad obce s rozšířenou působností a <a href="https://xn--slovnk-7va.gov.cz/prohl%C3%AD%C5%BE%C3%ADme/pojem?iri=https://slovn%C3%ADk.gov.cz/legislativn%C3%AD/sb%C3%ADrka/111/2009/pojem/adresa">Adresa ze slovníku zákona č. 111/2009 Sb., o základních registrech</a></p>

<span id="_Toc185597999"></span><span id="_Toc228268028"></span><h2 id="pokrocily-popis-dat">Pokročilý popis dat</h2>

<span id="_Využití_popisu_dat"></span><p>Při popisování dat můžete narazit na specifické problémy nebo potřeby vyjádřit specifické skutečnosti. Tyto scénáře a jejich řešení jsou blíže popsány na <a href="https://data.gov.cz/popis-dat">https://data.gov.cz/popis-dat</a>.<s> </s><s> </s><s> </s></p>

<span id="_Publikace_slovníků"></span><span id="_Publikace_slovníku"></span><span id="_Toc180400105"></span><span id="_Ref181112708"></span><span id="_Ref181112718"></span><span id="_Ref181374123"></span><span id="_Toc185598000"></span><span id="_Toc228268029"></span><h2 id="publikace-slovniku">Publikace slovníku</h2>

<p>Před jakýmkoliv využitím popisu dat je potřeba jej publikovat tak, aby byl katalogizován v Národním katalogu dat. Slovníky jsou otevřenými daty, a bez tohoto kroku nemohou podle být zákona č. 106/1999 Sb. považována za otevřená data. Není to však jen o povinnostech, publikace vám poskytne několik výhod:</p>

<ul>
<li>Slovníky budou snadno dostupné přes internet vám i ostatním. Publikací získává každý pojem a slovník jednoznačný identifikátor (IRI), pomocí kterého se na něj dá odkazovat.</li>
<li>Díky katalogizaci bude hledání slovníků a pojmů mnohem jednodušší.</li>
<li>Během přípravy slovníku se potvrzuje kompatibilita s otevřenou formální normou pro slovníky – aby bylo zajištěno, že s vašim slovníkem mohou pracovat všichni.</li>
</ul>

<p>V prvé řadě je nutné určit název slovníku, který jste vytvořili. Název se odvíjí od oblasti, kterou slovníkem popisujete (nebo zdroje, pokud pro slovník používáte právě jeden).</p>

<aside class="methodology-callout methodology-callout--good">Dobré příklady názvu slovníku jsou: Slovník zákona č. 361/2000 Sb., Slovník agendy A998, Slovník veřejných zakázek, Slovník badatelského řádu apod. Slovník z našeho příkladu jsme nazvali Slovník z<em>ákona č. 361/2000 Sb.</em> a přidáme popis: Příkladový slovník, který sbírá pojmy ze zákona o silničním provozu.</aside>

<p>Poté vezměte svůj slovník (resp. výstup z nástrojů), a pokud již není ve formátu OFN pro slovníky, převeďte jej do tohoto formátu. Postup pro získání výstupů z jednotlivých nástrojů jsou obsaženy v návodech pro jednotlivé nástroje. Proces získání souboru se slovníkem dle OFN z těchto výstupů je popsán na <a href="https://data.gov.cz/popis-dat">stránkách popisu dat</a>. Následně můžete soubor se slovníkem dle OFN nahrát na veřejně dostupnou adresu a založit katalogizační záznam do svého lokálního katalogu dat.</p>

<aside class="methodology-callout methodology-callout--note">Slovník je datová sada, jako jakákoliv jiná v Národním katalogu dat. Aby však byla tato datová sada rozpoznána jako slovník, je nutné pro ni uvést <a href="https://ofn.gov.cz/slovníky">OFN slovníky</a> jako <a href="https://ofn.gov.cz/dcat-ap-cz-rozhran%C3%AD-katalog%C5%AF-otev%C5%99en%C3%BDch-dat/2024-05-28/#polo%C5%BEky-datov%C3%A1-sada-specifikace">specifikaci této sady</a>.</aside>

<p>Pokud se slovník poté katalogizuje v Národním katalogu dat jako slovník, máte publikaci a tím i celou iteraci hotovou. Pokud postupujete podle opatření Strategie, iterace v rámci vašich možností opakujte, dokud nemáte popsaná všechna data vašich informačních systémů veřejné správy.</p>

</div>
