<!-- Toto je šablona markdown pro závěrečný projekt kurzu Building AI, 
vytvořeného společností Reaktor Innovations a Helsinskou univerzitou. 
Zkopírujte šablonu, vložte ji do svého README na GitHubu a upravte! -->

# SkinAI: Diagnostika kožních onemocnění na bázi umělé inteligence

Závěrečný projekt kurzu Building AI

## Shrnutí
SkinAI je systém poháněný umělou inteligencí, který předpovídá a klasifikuje kožní onemocnění na základě analýzy obrazu. Využitím hlubokého učení a databází lékařských snímků pomáhá dermatologům a praktickým lékařům při včasné diagnostice, která může zabránit závažným onemocněním, jako je například melanom.

## Pozadí

Kožní onemocnění postihují miliony lidí na celém světě, od mírných stavů, jako je ekzém, až po život ohrožující melanom. Včasné odhalení je nezbytné pro úspěšnou léčbu, ale přístup k dermatologům je často omezený.

* Miliony lidí trpí nediagnostikovanými nebo nesprávně diagnostikovanými kožními chorobami.
* Mnoha případům melanomu a dalších závažných onemocnění by se dalo předejít včasným odhalením.
* Dermatologů je na celém světě nedostatek, což vede k dlouhým čekacím lhůtám pro pacienty.

Jako člověk, který se zajímá o využití umělé inteligence ve zdravotnictví, vidím v tomto projektu příležitost ke zlepšení lékařské diagnostiky a dostupnosti včasného odhalení kožních onemocnění.


## Jak se používá?

Pacienti, praktičtí lékaři nebo dermatologové mohou nahrát fotografii kožní léze nebo postiženého místa. Model umělé inteligence obrázek analyzuje a poskytuje klasifikaci pravděpodobného kožního onemocnění (např. ekzém, lupénka, melanom) společně s doporučením, zda je vhodné vyhledat odbornou lékařskou pomoc.
Systém může být nasazen v různých prostředích:

*jako součást mobilní aplikace pro samodiagnostiku pacientů,

*jako nástroj pro praktické lékaře, kteří nemají specializaci v dermatologii,

*nebo přímo ve specializovaných zdravotnických zařízeních jako podpora dermatologické diagnostiky.

Je důležité zohlednit potřeby všech zúčastněných stran:

*Pacienti očekávají jednoduché a srozumitelné rozhraní, ochranu soukromí a jasné doporučení.

*Lékaři potřebují spolehlivý nástroj, který jim pomůže v rozhodovacím procesu, ale nebude nahrazovat jejich odbornost.

*Vývojáři a zdravotnické instituce musí zajistit, že systém bude bezpečný, přesný a splní všechna etická a legislativní pravidla.


### Ukázky kožního onemocnění

<img src="https://www.proalergiky.cz/CMTrade/media/static-media/9d95e4be-19b7-496b-8f8c-2294adbfda2b@w1200.webp" width="400">
<img src="https://www.dermanet.cz/files/obrazky/choroby/melanom-foto2.jpg" width="400">

## Datové zdroje a AI metody

Údaje jsou shromažďovány z:
* [ISIC Archive](https://www.isic-archive.com/).
* Veřejně dostupné dermatologické výzkumné práce.
* Generování syntetických dat pro zlepšení tréninku umělé inteligence.

Metody:
* **Hluboké učení** - konvoluční neuronové sítě (CNN) pro klasifikaci obrázků.
* **Transferové učení** - použití předtrénovaných modelů, jako jsou ResNet a EfficientNet.
* **Rozšíření dat** - zvýšení rozmanitosti datové sady pro dosažení vyšší přesnosti.

| Metoda umělé inteligence | Případ použití
| -------------- | --------------------- |
| CNN | Klasifikace kožních onemocnění |
| Učení přenosem | Zlepšení přesnosti pomocí předem vyškolených modelů |
| Rozšíření dat | Zlepšení robustnosti modelu |

## Výzvy

* Přesnost závisí na kvalitě a rozmanitosti souboru dat.
* Umělá inteligence nemůže nahradit lékařské odborníky, pouze jim pomáhat.
* Etické otázky týkající se shromažďování a používání lékařských snímků.
* Zkreslení souborů dat (omezené zastoupení různých odstínů pleti).

## Co dál?

* Integrace do mobilních aplikací pro analýzu kůže v reálném čase.
* Rozšíření souboru dat o rozmanitější typy a stavy kůže.
* Spolupráce s dermatology s cílem zlepšit výkonnost modelu.
* Regulační schválení k zajištění bezpečnosti a spolehlivosti pro lékařské použití.

## Poděkování

* Inspirace aplikacemi umělé inteligence v lékařské diagnostice.
* Data pocházejí z archivu ISIC a dalších otevřených souborů lékařských dat.
* Příklady diagnostických nástrojů řízených umělou inteligencí: [SkinVision](https://www.skinvision.com/), [Dermoscopy AI](https://www.dermoscopy.ai/).
