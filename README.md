# WDIO trenink
[https://webdriver.io/](https://webdriver.io/) 

## Zaměření tréninku
- Navazující trénink na [TEST AUTOMATION BASECAMP](https://www.testautomation-basecamp.cz/)
- Doménový specialista na funkcionální a nefunkcionální testy v browseru. 
- Praxe s nasazením a údržbou automatizovaného test stacku 
> Cílem tréninku je prakticky provést testera (nováček / zkušený) od běžných požadavků na funkcionální test automatizaci po reálné nasazení až po early adopters požadavky jako jsou interakce automatizovaného testu s prohlížečem a měření NFR.


## Pro koho je trénink určen
- Nováčky v test automatizaci
- Zkušené testery, kteří chtějí switchnout technologii a dále se rozvíjet

## Trénink pokrývá témata

**Automatizované testy frontendu**
- Automatizované testy v browseru 
- Jak funguje browser
- Mobilní browser
- Jak fungují webové aplikace
- HTML (DOM), CSS Object Model (CSSOM), React (Mutace)
- Javascript v prohlížeči

**Architektura test stacku**
- TestCase jako konfigurace
- Systém pro správu revizí
- Test exekuce
- Environment test stacku (servery a browser)
- Komponenty pro logování a monitoring testu a testované aplikace.
- Další komponenty, např. dataservery. 

**Výběr nástroje**
- Historie testování frontendu
- Konvenční frameworky

**WebdriverIO**
- about
- DigitalOcean
- Instalace WDIO

**Psaní testů**
- Psaní frontendových testů
- Běžně používané selektory, eventy a selektory trigrované eventy
- Architektura testů
- Vlastní příkazy
- Využití dataprovideru a znovupoužití packages

**Spouštění testů**
- Bash scripty
- Docker kontejnery
- CI/CD tooly
- Řízení na úrovní infrastruktury.

**Integrační úroveň**
- Automatizace rest-api
- Získání uživatelských dat pro automatizovaný test

**Visual testing**
- Testování na základě porovnávání snímků

**Git bez GUI - verzování testů**

**Linux**

**Docker**
- Seznámení s dockerem
- Používání WDIO v dockeru
- Spuštění připraveného WDIO stacku v dockeru

**Jak funguje browser**
- Infrastruktura, prostředí a komunikace
- Fáze a eventy

**Javascript v browseru**
- Integrace s dalšími javascriptovými knihovnami a využití v testech
- Využití javascriptových knihoven v browseru
- Injektáž javascriptu do browseru

**API v browseru**
- Využití Web API v automatizovaných testech
- Mutace DOMu
- Event handling
- Testování responses 

**Web Performance Testing**
- Web Performance Testing (Dan slidy)
- Rychlost načítání Webu
- RUM, AMP, CrUX, Metriky
- Syntetické měření a NFR
- https://httparchive.org/
- CrUX https://g.co/chromeuxdash / https://crux.run/
- Nástroje
    -   Lighthouse
    -   https://speedcurve.com/
    -   https://www.webpagetest.org/
    -   https://search.google.com/test/mobile-friendly?id=W3KAzTwD4LLoglewG2Fclg
- Audit a Performance v browseru
- Psaní Web Performance testů
- Hero elements
- Javascript a priorita načítání zdrojů
- WPT Checklist

**Rozšíření testu o analýzu frontendu**
- Rychlost načítání webu
- Web Api
- Chyby a logy v browseru

**Jak logovat / ukládat data**
- Seznámení s Elasticsearch, Kibana, Beats
- Live logování testů a metrik z browseru
- Tvorba vizualizací a dashboardů
- Automatická tvorba reportů
- Canvasové reporty s firemní grafikou / kontinuální sledování stavu prostředí na televizy v open-space
- Další volitelné ukládání dat z testů

**Investigace / Reporting**
- Vyhodnocování funkcionálních a nefunkcionálních requirementů z nasbíraných dat
- Jaké metriky jsou důležité

**Kubernetes**
- Stavba prostředí pro live logování
- Seznámení s kubernetes
- Pattern 1:1:1
- Příprava WDIO stacku pro imutabilní a izolované spuštění v kubernetes
- Rotace automatizovaného testu v kubernetes

**WDIO v cloudu**

**WDIO a CI/CD**

## Další zdroje
- [Gitter Channel](https://gitter.im/webdriverio/webdriverio)
- [Twitter](https://twitter.com/webdriverio)
- [Rychlost načítání - případovky](https://wpostats.com/)
- [Lighthouse váhy](https://docs.google.com/spreadsheets/d/1up5rxd4EMCoMaxH8cppcK1x76n6HLx0e7jxb0e0FXvc/edit#gid=0)

## Jak to funguje
- Trénink je dvoudenní, vždy od 09h do 16h a probíhá pomocí Google Meets.
- Střídavě teorie s praktickým zapojením, výsledkem je funkční test stack, který můžete začít používat u vás ve firmě.
- Testuje se oproti připravené DEMO aplikaci.
- Po každé lekci bude debrief .
- Na konci tréninku získá každý účastník certifikát na základě ústní zkoušky.
- Každý z účastníků má možnost využít kdykoli později 1h konzultace.

## Buďte připraveni a projděte si (Předpoklady účastníka)
- Musí umět obsluhovat svůj počítač a mít práva pro instalaci programů.
- Musí umět používat SSH.
- Docker https://www.zdrojak.cz/clanky/proc-pouzivat-docker/
- Git https://git-scm.com/download/win (volitelné)
- Putty https://www.putty.org/ (pro windows uživatele)
- Založte si účet na githubu: https://github.com/ a projděte si:  https://www.root.cz/knihy/pro-git/
- Zaregistrujte se na https://hub.docker.com/
- Zaregistruj se na [DigitalOcean](https://m.do.co/c/d3a11bf7b094)

## Trenér
**Radim Daniel Pánek**

Dlouhá léta pracoval jako vývojář a v posledních osmi letech se plně soustředí na výzkum v oblasti test automatizace. Působí v první linii od psaní testů přes správu infrastruktury pro automatizované testy až po evangelizaci test automatizace. Školí testery a navštěvuje různé QA týmy, mentoruje a hodnotí jejich test stack.

* [Twitter](https://twitter.com/RDPanek)
* [LinkedIn](https://www.linkedin.com/in/rdpanek/) 
* Tel.: 731 011 200
* Mail: rdpanek gmail

Pokud se ti trénink **líbil**, dej **hvězdičku** a sleduj **změny**. Super bude určitě tvá recenze a nebo post na socialních síti twitter, linkedin atp. + mě označ, a využij tagů `#testAutomationBasecamp`, `#wdioCZ` díky :-) 
<br/>
<br/>
Pokračuj ve vzdělávání a sleduj [TEST STACK Live](https://www.youtube.com/c/teststack), sleduj mě při práci a ptej se [Let's tests](https://www.twitch.tv/rdpanek/videos) a nebo se otoč [na slack](http://bit.ly/test-stack).
<br/>
<br/>
<br/>
![alt text](https://www.testautomation-basecamp.cz/tabMini.png "TEST AUTOMATION BASECAMP")
