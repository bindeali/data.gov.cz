---
layout: contained
title: Návod pro popis dat v tabulce
ref: DataModelling-Guide-Spreadsheet
lang: cs
---

<div class="methodology-document">
<span id="_Toc181623512"></span><span id="_Toc186707623"></span><h2 id="uvod">Úvod</h2>

<p>Tento dokument navazuje na Metodiku popisu dat – její přečtení a porozumění je pro následující text nezbytné. Aktuální verze metodiky je společně s aktuálními informacemi a podpůrnými materiály k popisu dat umístěna na Portálu o datech:</p>

<blockquote><a href="https://data.gov.cz/popis-dat">https://data.gov.cz/popis-dat</a></blockquote>

<p>Tento návod nemá za cíl naučit čtenáře používat nástroj jako takový – nýbrž ukázat, jakým způsobem v daném nástroji popisovat data podle metodiky s pomocí připravené šablony.</p>

<p>Tabulkové řešení jsme připravili hlavně pro ty, kdo s popisem dat začínají a v úřadě nemají zkušenosti s nástroji na tvorbu popisu dat v grafické podobě (neboli s diagramy/pohledy). Tabulka je nejjednodušší řešení pro základní popis dat. Nevyžaduje vynaložení speciálních kapacit kromě znalce oblastí, které jste si zvolili pro tvorbu slovníků. Berte však na vědomí, že s růstem počtu pojmů, vlastností a vztahů ale roste komplikovanost a klesá srozumitelnost tabulky.</p>

<span id="_Toc181075329"></span><span id="_Toc181623513"></span><span id="_Toc186707624"></span><h3 id="o-sablone">O šabloně</h3>

<p>Šablony jsou připraveny jednak ve formátu XLSX (pro Microsoft Excel). V šabloně je zabudovaná nápověda a výběr z vyplněných hodnot (kde je to vhodné). Sešit se šablonou je rozdělen do čtyř listů:</p>

<ul>
<li><strong>Subjekty a objekty práva</strong></li>
<li><strong>Vlastnosti</strong></li>
<li><strong>Vztahy</strong></li>
<li><strong>Slovník</strong></li>
</ul>

<p>Šablonu pro zahájení práce stačí otevřít ve Vámi preferovaném nástroji pro tabulky jako jakýkoliv jiný sešit.</p>

<span id="_Toc186707625"></span><h3 id="doprovodne-slovniky">Doprovodné slovníky</h3>

<p>Doprovodné slovníky (obsažené také v šablonách pro ostatní podporované nástroje pro popis dat) jsou v samostatné tabulce. Jedná se o příkladový slovník z metodiky a Slovník obecných pojmů veřejného sektoru. Těmito slovníky se můžete podle své libosti inspirovat, využít jejich pojmy, nebo je smazat. Jedná se o lokální kopie těchto slovníků, jejich úpravou se publikované verze nijak nemění.</p>

<span id="_Toc181623515"></span><span id="_Toc186707626"></span>

<h2 id="popis-dat-v-nastroji">Popis dat v nástroji</h2>

<p>Pro převod tabulky do slovníku podle OFN je velmi důležité, abyste neupravovali názvy listů ani názvy jednotlivých sloupců (tj. první řádek) v tabulkách.</p>

<span id="_Toc186707627"></span><p>Pomocí jednoho sešitu se popisuje jeden slovník. Jednotlivé charakteristiky slovníků a pojmů jsou doplněny níže. <em>Doplňující charakteristiky </em>dále upřesňují význam pojmu nad rámec potřebné úrovně z metodiky popisu dat a doporučujeme je vyplňovat až tehdy, kdy je uznáte za potřebné.</p>

<h3 id="charakteristiky-slovniku">Charakteristiky slovníku</h3>

<p>Obecné informace o slovníku se popisují v listu Slovník.</p>

<span id="_Hlk185592667"></span><div class="methodology-table-wrapper"><table><tbody><tr><th>Charakteristika</th><th>Popis</th><th>Přípustné hodnoty</th></tr><tr><td>Název slovníku</td><td>Název slovníku (musí být unikátní vzhledem ke všem publikovaným slovníkům)</td><td>Volný text</td></tr><tr><td>Popis slovníku</td><td>Doplňující informace o slovníku</td><td>Volný text</td></tr><tr><td>Adresa lokálního katalogu dat, ve kterém bude slovník registrován</td><td>Podle této adresy se budou vytvářet identifikátory slovníku a jednotlivých pojmů.</td><td>Odkaz (URL)</td></tr></tbody></table></div>

<span id="_Toc181075330"></span><span id="_Toc181623516"></span><span id="_Toc186707628"></span><h3 id="charakteristiky-spolecne-pro-vsechny-pojmy">Charakteristiky společné pro všechny pojmy</h3>

<div class="methodology-table-wrapper"><table><tbody><tr><th>Charakteristika</th><th>Popis</th><th>Přípustné hodnoty</th></tr><tr><td>Název</td><td>Název pojmu</td><td>Volný text</td></tr><tr><td>Popis</td><td>Popis pojmu</td><td>Volný text</td></tr><tr><td>Definice</td><td>Definice pojmu</td><td>Volný text</td></tr><tr><td>Zdroj</td><td>Zdroj pojmu</td><td>Odkaz URL (ELI), případně volný text</td></tr><tr><td>Nadřazený pojem</td><td>Nadřazený pojem vyplňovaného pojmu</td><td>Název pojmu z tabulky nebo identifikátor IRI</td></tr><tr><td>Identifikátor</td><td>IRI pojmu – nevyplňovat, pokud se jedná o ještě nepublikovaný pojem!</td><td>Identifikátor IRI</td></tr><tr><td>Alternativní název</td><td>Doplňující charakteristika. Další, neoficiální název pojmu (<a href="https://data.gov.cz/popis-dat/znalostní-báze/doplňující-informace/alternativní-název">více informací</a>)</td><td>Volný text</td></tr><tr><td>Ekvivalentní pojem</td><td>Doplňující charakteristika. Ekvivalentní pojem vyplňovaného pojmu (<a href="https://data.gov.cz/popis-dat/znalostní-báze/doplňující-informace/ekvivalentní-pojem">více informací</a>)</td><td>Identifikátor pojmu IRI z publikovaného slovníku</td></tr><tr><td>Související zdroj</td><td>Doplňující charakteristika. Zdroj, který nedefinuje, nýbrž upřesňuje význam pojmu (<a href="https://data.gov.cz/popis-dat/znalostní-báze/doplňující-informace/související-zdroj">více informací</a>)</td><td>Odkaz URL (ELI), případně volný text</td></tr></tbody></table></div>

<span id="_Toc181075331"></span><span id="_Toc181623517"></span><span id="_Toc186707629"></span><h3 id="subjekty-a-objekty-prava">Subjekty a objekty práva</h3>

<div class="methodology-table-wrapper"><table><tbody><tr><th>Charakteristika</th><th>Popis</th><th>Přípustné hodnoty</th></tr><tr><td>Typ</td><td>Zdali se jedná o subjekt nebo objekt práva</td><td>“Subjekt práva” nebo “Objekt práva”</td></tr></tbody></table></div>

<span id="_Toc181075332"></span><span id="_Toc181623518"></span><span id="_Toc186707630"></span><h3 id="vlastnosti">Vlastnosti</h3>

<div class="methodology-table-wrapper"><table><tbody><tr><th>Charakteristika</th><th>Popis</th><th>Přípustné hodnoty</th></tr><tr><td>Subjekt nebo objekt práva</td><td>Subjekt nebo objekt práva, ke kterému je vlastnost přiřazena</td><td>Název pojmu z tabulky nebo identifikátor IRI</td></tr><tr><td>Datový typ</td><td>Doplňující charakteristika. Typ očekávaných hodnot vlastností (<a href="https://data.gov.cz/popis-dat/znalostní-báze/doplňující-informace/datové-typy">další informace</a>)</td><td>Výběr ze seznamu (Excel) nebo XSD identifikátor datového typu</td></tr></tbody></table></div>

<span id="_Toc181075333"></span><span id="_Toc181623519"></span><span id="_Toc186707631"></span><h3 id="vztahy">Vztahy</h3>

<span id="_Toc181075334"></span><div class="methodology-table-wrapper"><table><tbody><tr><th>Popis</th><th>Popis</th><th>Přípustné hodnoty</th></tr><tr><td>Subjekt nebo objekt práva (první sloupec)</td><td>Subjekt nebo objekt práva, ke kterému je vztah přiřazen</td><td>Název pojmu z tabulky nebo identifikátor IRI</td></tr><tr><td>Subjekt nebo objekt práva (třetí sloupec)</td><td>Subjekt nebo objekt práva, ke kterému je vztah přiřazen</td><td>Název pojmu z tabulky nebo identifikátor IRI</td></tr></tbody></table></div>

<span id="_Toc181623520"></span><span id="_Toc186707632"></span><span id="_Toc181623521"></span><h3 id="vyuzivani-pojmu-z-jinych-slovniku-pomoci-iri">Využívání pojmů z jiných slovníků pomocí IRI</h3>

<p>Tam, kde je mezi přípustnými hodnotami „Identifikátor IRI“, je umožněno pracovat s pojmy z jiných (publikovaných) slovníků. Pro používání těchto pojmů v rozpracovaném slovníku je nutné znát jejich IRI – jen tak poznáme, že jde o pojem z jiného slovníku. To také znamená, že tyto pojmy musí být před využitím katalogizované do Národního katalogu dat, ve kterém slovníky/pojmy vyhledáte a společně s jejich IRI. Slovník obecných pojmů veřejného sektoru má identifikátory IRI zanesené také do šablony.</p>

<span id="_Toc186707633"></span><h3 id="rozsireni-pro-evidenci-udaju-agendy-do-registru-prav-a-povinnosti">Rozšíření pro evidenci údajů agendy do Registru práv a povinností</h3>

<p>Pokud popisujete subjekty a objekty práva pro jejich následnou reprezentaci v RPP, můžete je popsat detailněji zvláštními charakteristikami definovanými v OFN pro slovníky, uvedeny níže.</p>

<span id="_Toc181623522"></span><span id="_Toc186707634"></span><h4 id="subjekty-a-objekty-prava-2">Subjekty a objekty práva</h4>

<div class="methodology-table-wrapper"><table><tbody><tr><th>Charakteristika</th><th>Popis</th><th>Přípustné hodnoty</th></tr><tr><td>Agenda</td><td>Agenda, do které subjekt/objekt (resp. jeho údaje) patří (je „agendový vlastní“, tj. nepřebíraný)</td><td>Kód agendy z RPP</td></tr><tr><td>Agendový informační systém</td><td>Agendový informační systém (AIS), pro který jsou údaje subjektu/objektu práva „agendově vlastní&quot;, tj. nepřebírané</td><td>Kód ISVS z RPP</td></tr></tbody></table></div>

<span id="_Toc181623523"></span><span id="_Toc186707635"></span><h4 id="vlastnosti-a-vztahy">Vlastnosti a vztahy</h4>

<div class="methodology-table-wrapper"><table><tbody><tr><th>Charakteristika</th><th>Popis</th><th>Přípustné hodnoty</th></tr><tr><td>Je pojem sdílen v PPDF?</td><td>Sdílení údaje (plánované nebo již uskutečněné) v <a href="https://pruvodcepripojenim.gov.cz/">propojeném datovém fondu</a>. „Ne“ znamená „není a nebude sdílen“ nebo „je sdílen, ale ne v PPDF“.</td><td>„Ano“ nebo „Ne“</td></tr><tr><td>Je pojem veřejný?</td><td>Určení, zdali je údaj (ne)veřejný, tj. (ne)přístupný veřejnosti</td><td>„Ano“ nebo „Ne“</td></tr><tr><td>Ustanovení dokládající neveřejnost pojmu</td><td>Ustanovení, ze kterého neveřejnost údaje vyplývá; vyplňuje se právě tehdy, když charakteristika pojmu „Je pojem veřejný?“ je „Ne“</td><td>Odkaz (URL), případně volný text</td></tr></tbody></table></div>

<span id="_Toc181623524"></span><span id="_Toc186707636"></span><h2 id="publikace-slovniku">Publikace slovníku</h2>

<p>Pro publikaci je potřeba tabulku převést do formátu slovníku podle OFN. Tabulku pošlete na účet <a href="mailto:data@dia.gov.cz">data@dia.gov.cz</a>. Nezapomeňte zmínit, jaké je zamýšlené využití slovníku (např. evidence údajů agendy do RPP, výkladový slovník apod.).</p>

<p>Jakmile slovník schválíme, obdržíte slovník ve formátu dle OFN, který můžete nahrát a poté pro něj vytvořit katalogizační záznam do vašeho Lokálního katalogu dat.</p>

</div>
