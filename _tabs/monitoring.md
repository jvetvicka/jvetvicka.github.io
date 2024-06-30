---
# the default layout is 'page'
title: Monitoring CZ/SK
icon: fas fa-eye
order: 6
---

V rámci monitoringu českých a slovenských médií jsem pomocí ChatGPT vytvořil jednoduchý [python skript](https://github.com/jvetvicka/scripts/blob/449af380bd3e56b4e2ad9336031cfeefa58f8898/mediacheck.py), který prohledává RSS zpravodajských webů a na základě klíčových slov vypisuje relevantní články pro mou práci. Průběžně zde budu zveřejňovat odkazy pro jednotlivé dny.

<!-- Odkazy na klíčová slova -->
<button onclick="filterByKeyword('vsechna')" class="post-tag btn btn-outline-primary">vše</button>
<button onclick="filterByKeyword('fact-checking')" class="post-tag btn btn-outline-primary">fact-checking</button>
<button onclick="filterByKeyword('dezinformace')" class="post-tag btn btn-outline-primary">dezinformace</button>
<button onclick="filterByKeyword('kyberbezpecnost')" class="post-tag btn btn-outline-primary">kyberbezpečnost</button>
<button onclick="filterByKeyword('umela-inteligence')" class="post-tag btn btn-outline-primary">AI</button>
<button onclick="filterByKeyword('cenzura')" class="post-tag btn btn-outline-primary">cenzura</button>
<button onclick="filterByKeyword('podvod')" class="post-tag btn btn-outline-primary">podvod</button>
<button onclick="filterByKeyword('musk')" class="post-tag btn btn-outline-primary">elon musk</button>
<button onclick="filterByKeyword('propaganda')" class="post-tag btn btn-outline-primary">propaganda</button>
<button onclick="filterByKeyword('krajni-pravice')" class="post-tag btn btn-outline-primary">krajní pravice</button>
<button onclick="filterByKeyword('konspirace')" class="post-tag btn btn-outline-primary">konspirace</button>

<script>
    function filterByKeyword(keyword) {
      var novinky = document.querySelectorAll('.novinka');
      novinky.forEach(function(novinka) {
        var keywords = novinka.getAttribute('data-keywords').split(', ');
        if (keywords.includes(keyword) || keyword === 'vsechna') {
          novinka.style.display = 'list-item';
        } else {
          novinka.style.display = 'none';
        }
      });
    }
</script>

## 30.6. (neděle) 🟢
<ul>
<li class="novinka" data-keywords="fact-checking"><a href="https://www.irozhlas.cz/zpravy-domov/overovna-pavel-chce-zakazat-volit-starym-lidem-lze-e-mail-vyrok-je-ale-upraveny_2406300500_edr" target="_blank">OVĚŘOVNA: Pavel chce zakázat volit starým lidem, lže e-mail. Výrok je ale upravený a vytržený z kontextu</a> <small>(irozhlas.cz, 30.06)</small> <code class="highlighter-rouge">fact-checking</code></li>
<li class="novinka" data-keywords="fact-checking"><a href="https://cedmohub.eu/cs/seznam-cz-novinky-a-stream-cz-zustavaji-ivo-lukacovicovi-napojeni-na-sorose-je-smyslene/?utm_source=rss&utm_medium=rss&utm_campaign=seznam-cz-novinky-a-stream-cz-zustavaji-ivo-lukacovicovi-napojeni-na-sorose-je-smyslene" target="_blank">Seznam.cz, Novinky a Stream.cz zůstávají Ivo Lukačovičovi, napojení na Sorose je smyšlené</a> <small>(cedmohub.eu, 30.06)</small> <code class="highlighter-rouge">fact-checking</code></li>
<li class="novinka" data-keywords="propaganda"><a href="https://www.aktuality.sk/clanok/wMZYS2t/ako-propaganda-meni-pravidla-komunikacnych-hier/" target="_blank">Ako propaganda mení pravidlá komunikačných hier</a> <small>(aktuality.sk, 30.06)</small> <code class="highlighter-rouge">propaganda</code></li>
<li class="novinka" data-keywords="krajni-pravice"><a href="https://zpravy.aktualne.cz/zahranici/macronuv-gamble-nevychazi-strana-le-penove-ma-na-dosah-voleb/r~0f9118a8351e11ef95ee0cc47ab5f122/?utm_source=mediafed&utm_medium=rss&utm_campaign=mediafed" target="_blank">Macron se přepočítal. Krajní pravice míří k triumfu, Francii hrozí dvojvládí a chaos</a> <small>(zpravy.aktualne.cz, 30.06)</small> <code class="highlighter-rouge">krajní pravice</code></li>
<li class="novinka" data-keywords="krajni-pravice"><a href="https://www.seznamzpravy.cz/clanek/volby-francie-2024-kdo-je-jordan-bardella-254835" target="_blank">Lepenovská hvězda TikToku chce řídit Francii. Zatím dostává nabídky k sňatku</a> <small>(seznamzpravy.cz, 30.06)</small> <code class="highlighter-rouge">krajní pravice</code></li>
<li class="novinka" data-keywords="propaganda"><a href="https://www.teraz.sk/zahranicie/riziko-ruskeho-zasahovania-do-volieb-vo/805604-clanok.html" target="_blank">Riziko ruského zasahovania do volieb vo V. Británii je znepokojujúce</a> <small>(teraz.sk, 30.06)</small> <code class="highlighter-rouge">propaganda</code></li>
<li class="novinka" data-keywords="propaganda"><a href="https://dennikn.sk/minuta/4074177/" target="_blank">Cirkevnými dejinami vanie propagandisticky organizovaná mizogýnna atmosféra zameraná na udržanie...</a> <small>(dennikn.sk, 30.06)</small> <code class="highlighter-rouge">propaganda</code></li>

</ul>

## 29.6. (sobota) 🟢
<ul>
<li class="novinka" data-keywords="krajni-pravice"><a href="https://www.seznamzpravy.cz/clanek/volby-eurovolby-laka-mlade-krajni-pravice-ne-jen-je-v-kurzu-volit-rebely-rika-sociolog-254824" target="_blank">Láká mladé krajní pravice? Ne, jen je v kurzu volit rebely, říká sociolog</a>) <small>(seznamzpravy.cz)</small> <code class="highlighter-rouge">krajní pravice</code></li>
<li class="novinka" data-keywords="krajni-pravice"><a href="https://www.denik.cz/ze_sveta/izrael-demonstrace-benjamin-netanjahu.html" target="_blank">Desetitisíce lidí v Izraeli znovu vyšly do ulic. Protestují proti Netanjahuovi</a><small>(denik.cz)</small> <code class="highlighter-rouge">krajní pravice</code></li>
<li class="novinka" data-keywords="podvod"><a href="https://www.novinky.cz/clanek/krimi-desitky-podvodniku-ze-zlinska-si-diky-fiktivnim-dokladum-prisly-na-145-milionu-40478343" target="_blank">Desítky podvodníků ze Zlínska si díky fiktivním dokladům přišly na 145 milionů</a> <small>(novinky.cz)</small> <code class="highlighter-rouge">podvod</code></li>
<li class="novinka" data-keywords="kyberbezpecnost"><a href="https://hnonline.sk/svet/96156974-polska-prokuratura-vysetruje-kyberneticky-utok-na-pap-a-sirenie-dezinfomacie" target="_blank">Poľská prokuratúra vyšetruje kybernetický útok na PAP a šírenie dezinfomácie</a> <small>(hnonline.sk)</small> <code class="highlighter-rouge">kyberbezpečnost</code></li>
<li class="novinka" data-keywords="konspirace"><a href="https://www.seznamzpravy.cz/clanek/audio-podcast-cemu-vsemu-jsou-lide-ochotni-verit-znate-nejvetsi-skryte-pravdy-sveta-254783" target="_blank">Čemu všemu jsou lidé ochotni věřit. Znáte největší „skryté pravdy“ světa?</a> <small>(seznamzpravy.cz)</small> <code class="highlighter-rouge">konspirace</code></li>
<li class="novinka" data-keywords="konspirace"><a href="https://refresher.cz/161978-Invaze-do-Iraku-nebo-vymyvani-mozku-podle-CIA-Tohle-jsou-pravdive-konspiracni-teorie-kterym-nejdriv-nikdo-neveril" target="_blank">Invaze do Iráku nebo vymývání mozků podle CIA. Tohle jsou pravdivé konspirační teorie, kterým nejdřív nikdo nevěřil </a> <small>(refresher.cz)</small> <code class="highlighter-rouge">konspirace</code></li>
</ul>


## 28.6. (pátek)
<ul>
<li class="novinka" data-keywords="fact-checking"><a href="https://cedmohub.eu/cs/japonska-vlada-stale-doporucuje-ockovani-proti-covidu-19-neockovanym-se-neomlouvala/?utm_source=rss&utm_medium=rss&utm_campaign=japonska-vlada-stale-doporucuje-ockovani-proti-covidu-19-neockovanym-se-neomlouvala" target="_blank">Japonská vláda stále doporučuje očkování proti covidu-19. Neočkovaným se neomlouvala</a> <small>(cedmohub.eu)</small> <code class="highlighter-rouge">fact-checking</code></li>
<li class="novinka" data-keywords="dezinformace"><a href="https://www.aktuality.sk/clanok/uPgO8DK/spekuloval-o-tom-orban-rusi-aj-dezinfoscena-robert-kalinak-vysvetloval-famy-o-zakladni-nato-na-slovensku/" target="_blank">Špekuloval o tom Orbán, Rusi aj dezinfoscéna. Robert Kaliňák vysvetľoval fámy o základni NATO na Slovensku</a> <small>(aktuality.sk)</small> <code class="highlighter-rouge">dezinformace</code></li>
<li class="novinka" data-keywords="podvod"><a href="https://www.aktuality.sk/clanok/uEkbyDC/pozor-na-podvody-pri-hladani-dovolenky-ubytovacia-online-sluzba-varuje-pred-utokmi-hackerov/" target="_blank">Pozor na podvody pri hľadaní dovolenky. Ubytovacia online služba varuje pred útokmi hackerov</a> <small>(aktuality.sk)</small> <code class="highlighter-rouge">podvod</code></li>
<li class="novinka" data-keywords="cenzura"><a href="https://www.seznamzpravy.cz/clanek/zahranicni-stredni-evropa-markiza-propustila-moderatora-kovacice-ktery-ji-ve-vysilani-obvinil-z-cenzury-254831" target="_blank">Markíza propustila moderátora Kovačiče, který ji ve vysílání obvinil z cenzury</a> <small>(seznamzpravy.cz)</small> <code class="highlighter-rouge">cenzura</code></li>
<li class="novinka" data-keywords="krajni-pravice"><a href="https://www.irozhlas.cz/zpravy-svet/jordan-bardella-narodni-sdruzeni-marine-le-pen-francie-krajni-pravice_2406281324_ula" target="_blank">Politik jako hvězda sociálních sítí. Krajně pravicový Bardella skrze ně cílí hlavně na mladé Francouze</a> <small>(irozhlas.cz)</small> <code class="highlighter-rouge">krajní pravice</code></li>
<li class="novinka" data-keywords="cenzura"><a href="https://www.lupa.cz/aktuality/moderator-michal-kovacic-dostal-vypoved-v-tv-markiza/?utm_source=rss&utm_medium=text&utm_campaign=rss" target="_blank">Moderátor Michal Kovačič dostal výpověď v TV Markíza</a> <small>(lupa.cz)</small> <code class="highlighter-rouge">cenzura</code></li>
<li class="novinka" data-keywords="kyberbezpecnost"><a href="https://www.novinky.cz/clanek/internet-a-pc-bezpecnost-10-nejobavanejsich-viru-pro-android-40478196" target="_blank">10 nejobávanějších virů pro Android</a> <small>(novinky.cz)</small> <code class="highlighter-rouge">kyberbezpečnost</code></li>
<li class="novinka" data-keywords="kyberbezpecnost"><a href="https://www.novinky.cz/clanek/internet-a-pc-bezpecnost-pozor-na-bankovni-ucty-cerberus-utoci-stale-casteji-40478195" target="_blank">Pozor na bankovní účty, Cerberus útočí stále častěji</a> <small>(novinky.cz)</small> <code class="highlighter-rouge">kyberbezpečnost</code></li>
<li class="novinka" data-keywords="podvod"><a href="https://www.novinky.cz/clanek/krimi-zena-se-zamilovala-do-fiktivniho-lekare-z-jemenu-prisla-o-dva-miliony-40478072" target="_blank">Žena se zamilovala do fiktivního lékaře z Jemenu. Přišla o dva miliony</a> <small>(novinky.cz)</small> <code class="highlighter-rouge">podvod</code></li>
<li class="novinka" data-keywords="musk"><a href="https://vtm.zive.cz/clanky/spacex-znici-mezinarodni-vesmirnou-stanici-deorbitalni-raketa-kupodivu-nebude-variantou-starship/sc-870-a-228903/default.aspx" target="_blank">SpaceX zničí Mezinárodní vesmírnou stanici. Deorbitální raketu pro NASA postaví Musk</a> <small>(vtm.zive.cz)</small> <code class="highlighter-rouge">Elon Musk</code></li>
<li class="novinka" data-keywords="podvod"><a href="https://news.refresher.sk/162698-Slovaci-si-musia-davat-pozor-na-kyberneticke-utoky-Podvodnici-zacali-vo-velkom-vyuzivat-umelu-inteligenciu" target="_blank">Slováci si musia dávať pozor na kybernetické útoky. Podvodníci začali vo veľkom využívať umelú inteligenciu</a> <small>(news.refresher.sk)</small> <code class="highlighter-rouge">podvod</code></li>
<li class="novinka" data-keywords="umela-inteligence"><a href="https://www.seznamzpravy.cz/clanek/porady-inside-talks-nenapadne-jako-covid-smrtici-jako-ebola-expert-varuje-pred-ai-bez-limitu-254723" target="_blank">Nenápadné jako covid, smrtící jako ebola. Expert varuje před AI bez limitů</a> <small>(seznamzpravy.cz)</small> <code class="highlighter-rouge">AI</code></li>
</ul>

## 27.6. (čtvrtek)
<ul>
<li class="novinka" data-keywords="fact-checking"><a href="https://cedmohub.eu/cs/asosbrn-video-z-mexickho-pobe-nen-dkazem-e-nedochz-ke-stoupn-hladiny-mo/?utm_source=rss&utm_medium=rss&utm_campaign=asosbrn-video-z-mexickho-pobe-nen-dkazem-e-nedochz-ke-stoupn-hladiny-mo" target="_blank">Časosběrné video z mexického pobřeží není důkazem, že nedochází ke stoupání hladiny moří</a> <small>(cedmohub.eu)</small> <code class="highlighter-rouge">fact-checking</code></li>
<li class="novinka" data-keywords="kyberbezpecnost"><a href="https://www.seznamzpravy.cz/clanek/ekonomika-ocima-byznysu-komentar-dopadlo-to-jako-vzdy-zakon-ma-pritom-jen-pripomenout-kyberbezpecnost-254422" target="_blank">Komentář: Dopadlo to jako vždy, zákon má přitom jen připomenout kyberbezpečnost</a> <small>(seznamzpravy.cz)</small> <code class="highlighter-rouge">kyberbezpečnost</code></li>
<li class="novinka" data-keywords="fact-checking"><a href="https://cedmohub.eu/cs/pocet-profesionalnich-vojaku-i-zaloh-armady-cr-roste/" target="_blank">Počet profesionálních vojáků i záloh Armády ČR roste</a> <small>(cedmohub.eu)</small> <code class="highlighter-rouge">fact-checking</code></li>
<li class="novinka" data-keywords="umela-inteligence"><a href="https://www.seznamzpravy.cz/clanek/tech-umela-inteligence-si-prisla-pro-praci-freelanceru-tim-se-to-ale-nezastavi-254663" target="_blank">Umělá inteligence si přišla pro práci živnostníků. Tím se to ale nezastaví</a> <small>(seznamzpravy.cz)</small> <code class="highlighter-rouge">AI</code></li>
<li class="novinka" data-keywords="propaganda"><a href="https://www.irozhlas.cz/zpravy-svet/online-patnactilety-chlapec-jde-v-rusku-za-podporu-ukrajiny-do-vezeni-bojoval_2406270654_kma" target="_blank">Patnáctiletý chlapec jde v Rusku za podporu Ukrajiny do vězení. Bojoval proti propagandě</a> <small>(irozhlas.cz)</small> <code class="highlighter-rouge">propaganda</code></li>
<li class="novinka" data-keywords="fact-checking"><a href="https://www.denik.cz/z_domova/denik-proti-fake-news-ukrajina-deti-autobus-uniformy-stredni-vojenska-skola.html" target="_blank">Posílá Ukrajina na frontu děti? Dezinformátoři zneužívají video se studenty</a> <small>(denik.cz)</small> <code class="highlighter-rouge">fact-checking</code></li>
<li class="novinka" data-keywords="fact-checking"><a href="https://demagog.cz/diskuze/vymysly-o-podvodech-pri-volbach-do-evropskeho-parlamentu-jak-se-podkopava-duvera-v-demokracii" target="_blank">Výmysly o podvodech při volbách do Evropského parlamentu – jak se podkopává důvěra v demokracii</a> <small>(demagog.cz)</small> <code class="highlighter-rouge">fact-checking</code></li>
<li class="novinka" data-keywords="podvod"><a href="https://www.novinky.cz/clanek/zahranicni-amerika-odmena-za-informace-o-kryptokralovne-ignatovove-se-zvysila-na-117-milionu-40478144" target="_blank">Odměna za informace o kryptokrálovně Ignatovové se zvýšila na 117 milionů</a> <small>(novinky.cz)</small> <code class="highlighter-rouge">podvod</code></li>
</ul>

## 26.6. (středa)
- [Kasino na Kypru zůstává původním vlastníkům, informace o prodeji Zelenskému pochází z falešného webu](https://cedmohub.eu/cs/kasino-na-kypru-zustava-puvodnim-vlastnikum-informace-o-prodeji-zelenskemu-pochazi-z-falesneho-webu/?utm_source=rss&utm_medium=rss&utm_campaign=kasino-na-kypru-zustava-puvodnim-vlastnikum-informace-o-prodeji-zelenskemu-pochazi-z-falesneho-webu){:target="_blank"} (cedmohub.eu)
- [Manipulativní a nepravdivé příspěvky popírají stoupající hladinu moří](https://demagog.cz/diskuze/manipulativni-a-nepravdive-prispevky-popiraji-stoupajici-hladinu-mori){:target="_blank"} (demagog.cz)
- [Jezdil se slovenskou SPZ, skrýval ho Čech. Tak našli dezinformátora na útěku](https://www.seznamzpravy.cz/clanek/domaci-kauzy-jezdil-se-slovenskou-spz-skryval-ho-cech-tak-nasli-dezinformatora-na-uteku-254626){:target="_blank"} (www.seznamzpravy.cz)
- [Slovenský soud uvalil vazbu na dezinformátora Zítka. V Česku je trestně stíhán za šíření poplašné zprávy](https://www.irozhlas.cz/zpravy-domov/dezinformator-zitko-slovensko-vazba-cesky-zatykac_2406261106_epo){:target="_blank"} (www.irozhlas.cz)
- [Ohraná báchorka o lékaři na zahraniční misi zase zabrala](https://www.novinky.cz/clanek/krimi-ohrana-bachorka-o-lekari-na-zahranicni-misi-zase-zabrala-40477900){:target="_blank"} (www.novinky.cz)
- [Konec Pavla Zítka? Zatímco utíkal, soud mu zrušil penězovod od důvěřivců](https://www.idnes.cz/zpravy/domaci/dezinformator-pavel-zitko-utek-policie-slovensko-patrani-vybirani-penez-lide.A240625_110352_domaci_vank#utm_source=rss&utm_medium=feed&utm_campaign=zpravodaj&utm_content=main){:target="_blank"} (www.idnes.cz)
- [Český dezinformátor, ktorého zadržala slovenská polícia, ide do väzby](https://spravy.rtvs.sk/2024/06/cesky-dezinformator-ktoreho-zadrzala-slovenska-policia-ide-do-vazby/){:target="_blank"} (spravy.rtvs.sk)
- [EU se chce zbavit ruské propagandy. Operátoři musí blokovat tyto čtyři Putinovy weby](https://www.zive.cz/clanky/eu-se-chce-zbavit-ruske-propagandy-operatori-musi-blokovat-tyto-ctyri-putinovy-weby/sc-3-a-228871/default.aspx){:target="_blank"} (www.zive.cz)
- [Umělá inteligence pomůže rychle a ekonomicky odminovat Ukrajinu. Její výcvik právě začíná](https://archiv.hn.cz/c1-67337800-umela-inteligence-pomuze-rychle-a-ekonomicky-odminovat-ukrajinu-jeji-vycvik-prave-zacina){:target="_blank"} (archiv.hn.cz)


## 25.6. (úterý)
- [Média informují o všech obětech vlakové nehody, nejen o Ukrajinkách](https://cedmohub.eu/cs/media-informuji-o-vsech-obetech-vlakove-nehody-nejen-o-ukrajinkach/?utm_source=rss&utm_medium=rss&utm_campaign=media-informuji-o-vsech-obetech-vlakove-nehody-nejen-o-ukrajinkach){:target="_blank"} (cedmohub.eu)
- [Regulace podle NIS2: NÚKIB se o nejkvalitnější zaměstnance přetahuje se soukromým sektorem](https://www.lupa.cz/clanky/regulace-podle-nis2-nukib-se-o-nejkvalitnejsi-zamestnance-pretahuje-se-soukromym-sektorem/?utm_source=rss&utm_medium=text&utm_campaign=rss){:target="_blank"} (www.lupa.cz)
- [Chtěl rychle zbohatnout, ale přišel o miliony. Na internetu narazil na podvodníka](https://www.novinky.cz/clanek/internet-a-pc-bezpecnost-chtel-rychle-zbohatnout-ale-prisel-o-miliony-na-internetu-narazil-na-podvodnika-40477712){:target="_blank"} (www.novinky.cz)
- [Dnes je poslední den, kdy můžete zabránit Facebooku v trénování AI na svých datech](https://www.zive.cz/clanky/dnes-je-posledni-den-kdy-muzete-zabranit-facebooku-v-trenovani-ai-na-svych-datech/sc-3-a-228822/default.aspx){:target="_blank"} (www.zive.cz)
- [Pokus o státní převrat, agent SIS a miliardář Soros. To jsou hlavní konspirace o atentátu na Fica šířené na TikToku](https://www.investigace.cz/fico-atentat-tiktok-ohnostroj-lzi/){:target="_blank"} (www.investigace.cz)
- [Pozor na flipování. Na trhu s nemovitostmi se objevil nový způsob podvodu](https://news.refresher.cz/162453-Pozor-na-flipovani-Na-trhu-s-nemovitostmi-se-objevil-novy-zpusob-podvodu){:target="_blank"} (news.refresher.cz)
- [VAROVANIE mobilného operátora! Ak vám príde TAKÁTO správa, neotvárajte ju: Zostanú vám oči pre plač](https://www.topky.sk/cl/10/2791261/VAROVANIE-mobilneho-operatora--Ak-vam-pride-TAKATO-sprava--neotvarajte-ju--Zostanu-vam-oci-pre-plac){:target="_blank"} (www.topky.sk)
- [Máte poslednú šancu, aby ste Facebooku a Instagramu zakázali použiť vaše údaje a fotky na trénovanie AI](https://hnonline.sk/style/tech/96156203-mate-poslednu-sancu-aby-ste-facebooku-a-instagramu-zakazali-pouzit-vase-udaje-a-fotky-na-trenovanie-ai){:target="_blank"} (hnonline.sk)
- [Rusko zakázalo šírenie médií z EÚ v reakcii na podobný krok Únie](https://www.teraz.sk/zahranicie/rusko-zakazalo-sirenie-medii-z-eu/804442-clanok.html){:target="_blank"} (www.teraz.sk)
- [Čína mění taktiku své propagandy. Bude ji vůbec ještě možné rozpoznat?](https://hlidacipes.org/cina-meni-taktiku-sve-propagandy-bude-ji-vubec-jeste-mozne-rozpoznat/){:target="_blank"} (hlidacipes.org)
- 🎧 [Co je zač zadržený dezinformátor Zítko? Nebezpečná figurka parazitující na důvěřivých lidech](https://www.novinky.cz/clanek/podcasty-retezak-co-je-zac-zadrzeny-dezinformator-zitko-nebezpecna-figurka-parazitujici-na-duverivych-lidech-40477629){:target="_blank"} (Podcast Řetězák)
- 🎥 [Ohrožuje nás Cenzurní industriální komplex?](https://www.youtube.com/watch?v=b549QuPl6J0){:target="_blank"} (YT Spiknutí)

## 24.6. (pondělí)
- [Sociální sítě, informační poruchy a zdraví](https://cedmohub.eu/cs/socialni-site-informacni-poruchy-a-zdravi/?utm_source=rss&utm_medium=rss&utm_campaign=socialni-site-informacni-poruchy-a-zdravi){:target="_blank"} (cedmohub.eu)
- [EÚ zasiahla proti kyberzločincom. Pridala šesť ľudí na svoj zoznam sankcií](https://www.aktuality.sk/clanok/pOAdYSO/eu-zasiahla-proti-kyberzlocincom-pridala-sest-ludi-na-svoj-zoznam-sankcii/){:target="_blank"} (www.aktuality.sk)
- [Video: Jak policisté zadrželi dezinformátora Pavla Zítka](https://www.seznamzpravy.cz/clanek/domaci-kauzy-video-muze-to-byt-zlocinne-spolceni-hrozil-zitko-slovenskym-policistum-254528){:target="_blank"} (www.seznamzpravy.cz)
- [‚Potřebujeme vaše účty, odměna až 50 tisíc.‘ Cizinci na Telegramu najímají Čechy a dělají z nich bílé koně](https://www.irozhlas.cz/zpravy-domov/potrebujeme-vase-ucty-odmena-az-50-tisic-cizinci-na-telegramu-najimaji-cechy-a_2406240500_vtk){:target="_blank"} (www.irozhlas.cz)
- [Japonská vesmírná agentura čelí kyberútokům. Tajné informace prý neunikly](https://www.novinky.cz/clanek/internet-a-pc-bezpecnost-japonska-vesmirna-agentura-celi-kyberutokum-tajne-informace-pry-neunikly-40477595){:target="_blank"} (www.novinky.cz)
- [Expertka: Ruská ambasáda na Slovensku je najaktívnejším zastupiteľským úradom z celej Európy](https://euractiv.sk/section/digitalizacia/interview/ruska-ambasada-na-slovensku-najaktivnejsi-zastupitelsky-uradom-eu-dezinformacie-propaganda/){:target="_blank"} (euractiv.sk)
- [Umělá inteligence Applu do Evropy jen tak nedorazí. Možná by porušila místní antimonopolní pravidla](https://cc.cz/umela-inteligence-applu-do-evropy-jen-tak-nedorazi-mozna-by-porusila-mistni-antimonopolni-pravidla/){:target="_blank"} (cc.cz)
- [Chytré telefony v Česku ohrožuje malware. Maskuje se ve falešných hrách, napadá bankovní aplikace](https://mobilmania.zive.cz/clanky/prehled-hrozeb-pro-android-skodlivy-software-spyware-malware-a-dalsi-zranitelnosti/sc-3-a-1359020/default.aspx){:target="_blank"} (mobilmania.zive.cz)
- [Umělá inteligence přijímala u McDonald's objednávky. Měla problémy a nakonec dostala vyhazov](https://www.zive.cz/clanky/umela-inteligence-prijimala-u-mcdonalds-objednavky-mela-problemy-a-nakonec-dostala-vyhazov/sc-3-a-228683/default.aspx){:target="_blank"} (www.zive.cz)
- [Stát už ví, co je dezinformace. Foltýn řekl, čím chce Rusko rozbít demokracii](https://www.idnes.cz/zpravy/domaci/definice-dezinformace-foltyn-rusky-narativ-je-nicemu-neverte-snemovna-strategicka-komunikace.A240624_095013_domaci_kop#utm_source=rss&utm_medium=feed&utm_campaign=zpravodaj&utm_content=main){:target="_blank"} (www.idnes.cz)

## 23.6. (neděle)
- [OVĚŘOVNA: Důchod podle ukrajinských pravidel, ale vyplácený Českem. Šíří se další lež o uprchlících](https://www.irozhlas.cz/zpravy-domov/overovna-duchod-podle-ukrajinskych-pravidel-ale-vyplaceny-ceskem-siri-se-dalsi_2406230500_job){:target="_blank"} (www.irozhlas.cz)
- [Proti zlodějům mobilů bude bojovat umělá inteligence](https://www.novinky.cz/clanek/internet-a-pc-ai-proti-zlodejum-mobilu-bude-bojovat-umela-inteligence-40477165){:target="_blank"} (www.novinky.cz)
- [Záujem o cestovanie je veľký a podvodníci to chcú využiť: Po novom úradujú aj na sociálnych sieťach](https://spravy.rtvs.sk/2024/06/zaujem-o-cestovanie-je-velky-a-podvodnici-to-chcu-vyuzit-s-novymi-taktikami-prichadzaju-na-internete/){:target="_blank"} (spravy.rtvs.sk)


## 22.6. (sobota)
- [‚Zpravodajci to vidí jinak.‘ Ve sporu o blokaci webu AC24 vypovídali i svědci z ‚alternativních‘ médií](https://www.irozhlas.cz/zpravy-domov/zpravodajci-vidi-jinak-ve-sporu-o-blokaci-webu-ac24-vypovidali-i-svedci-z_2406220500_pik){:target="_blank"} (www.irozhlas.cz)
- [Video trasúceho sa ukrajinského dievčaťa: Nešlo o reakciu na bombardovanie, no k ruským útokom stále dochádza](https://spravy.rtvs.sk/2024/06/trasuce-sa-dieta-na-ukrajine-neslo-o-reakciu-na-bombardovanie/){:target="_blank"} (spravy.rtvs.sk)
- [Zaplatili za vilu, přijeli k lesu. Podvodníci útočí přes populární servery](https://www.seznamzpravy.cz/clanek/ekonomika-firmy-pred-dovolenou-pozor-na-rafinovany-podvod-s-falesnymi-hotely-254360){:target="_blank"} (www.seznamzpravy.cz)
- [Elektronický občanský průkaz má v mobilu přes 430 tisíc lidí. Jiní se obávají zneužití dat i zásahu státu](https://www.irozhlas.cz/zpravy-domov/elektronicky-obcansky-prukaz-ma-v-mobilu-pres-430-tisic-lidi-jini-se-obavaji_2406221322_vtk){:target="_blank"} (www.irozhlas.cz)
- [Expert: Méně nálepek. Nazývat opozici bez důkazů dezinformátory je špatné](https://www.idnes.cz/zpravy/domaci/rozstrel-tomas-kolomaznik-dezinformace-kniha-okamura.A240621_111046_domaci_vov#utm_source=rss&utm_medium=feed&utm_campaign=zpravodaj&utm_content=main){:target="_blank"} (www.idnes.cz)
- [Ak je ponuka brigády príliš dobrá, zrejme bude podvodná. Odborníci radia, ako neskončiť v pasci](https://spravy.rtvs.sk/2024/06/ak-je-ponuka-brigady-prilis-dobra-zrejme-bude-podvodna-odbornici-radia-ako-neskoncit-v-pasci/){:target="_blank"} (spravy.rtvs.sk)
- [Seniorky vložili medzi smetiaky desiatky tisíc eur, šperky aj kľúče od auta. Polícia zverejnila detaily nového typu podvodu](https://news.refresher.sk/162299-Seniorky-vlozili-medzi-smetiaky-desiatky-tisic-eur-sperky-aj-kluce-od-auta-Policia-zverejnila-detaily-noveho-typu-podvodu){:target="_blank"} (news.refresher.sk)


## 21.6. (pátek)
- [Japonská vesmírná agentura JAXA se od konce loňského roku stala terčem řady kybernetických útoků](https://denikn.cz/minuta/1458491/){:target="_blank"} (denikn.cz)
- [NÚKIB připravuje nový kyberzákon, řadě firem se ale nelíbí. ‚Tlaků bylo velké množství,‘ říká šéf úřadu](https://www.irozhlas.cz/zpravy-domov/nukib-pripravuje-novy-kyberzakon-rade-firem-se-ale-nelibi-tlaku-bylo-velke_2406210009_job){:target="_blank"} (www.irozhlas.cz)
- [Japonskou vesmírnou agenturu opakovaně napadli hackeři. Tajné informace o raketách prý ale neunikly](https://www.irozhlas.cz/zpravy-svet/japonskou-vesmirnou-agenturu-opakovane-napadli-hackeri-tajne-informace-o_2406211723_jar){:target="_blank"} (www.irozhlas.cz)
- [Podvodníci útočí na cestovatele ve velkém](https://www.novinky.cz/clanek/internet-a-pc-bezpecnost-podvodnici-utoci-na-cestovatele-ve-velkem-40477381){:target="_blank"} (www.novinky.cz)
- [Fio banka řeší rozsáhlý kybernetický útok, lidé se nemohou přihlásit do bankovnictví i několik dní](https://news.refresher.cz/162269-Fio-banka-resi-rozsahly-kyberneticky-utok-lide-se-nemohou-prihlasit-do-bankovnictvi-i-nekolik-dni){:target="_blank"} (news.refresher.cz)
- [Eštokova stránka Hoaxy a podvody blokuje kritických Slovákov](https://www.tyzden.sk/meme/111290/estokova-stranka-hoaxy-a-podvody-blokuje-kritickych-slovakov/){:target="_blank"} (www.tyzden.sk)
- [Příspěvek překrucuje dokument WHO o standardech sexuální výchovy](https://demagog.cz/diskuze/prispevek-prekrucuje-dokument-who-o-standardech-sexualni-vychovy){:target="_blank"} (demagog.cz)
- [Seznam.cz, Novinky a Stream.cz zůstávají Ivo Lukačovičovi, napojení na Sorose je smyšlené](https://demagog.cz/diskuze/seznam-cz-novinky-a-stream-cz-zustavaji-ivo-lukacovicovi-napojeni-na-sorose-je-smyslene){:target="_blank"} (demagog.cz)

## 20.6. (čtvrtek)
- [Osmdesátník slepě investoval do kryptoměn. Přišel o milion korun](https://www.novinky.cz/clanek/internet-a-pc-bezpecnost-osmdesatnik-slepe-investoval-do-kryptomen-prisel-o-milion-korun-40477142){:target="_blank"} (www.novinky.cz)
- [Policie stále hledá dezinformátora Zítka. Soud s ním se opět odkládá](https://www.novinky.cz/clanek/krimi-policie-stale-hleda-dezinformatora-zitka-soud-s-nim-se-opet-odklada-40477133){:target="_blank"} (www.novinky.cz)
- [Malé a střední firmy jsou snadným cílem pro kybernetický útok, hackeři na ně nasazují automatizované boty](https://cc.cz/male-a-stredni-firmy-jsou-snadnym-cilem-pro-kyberneticky-utok-hackeri-na-ne-nasazuji-automatizovane-boty/){:target="_blank"} (cc.cz)
- [Pandemie na Slovensku nebyla, prohlásil zástupce vlády, jenž vyšetřuje covid](https://www.idnes.cz/zpravy/zahranicni/slovensko-peter-kotlar-pandemie-na-slovensku-nebyla-sns-covid.A240619_200650_zahranicni_kha#utm_source=rss&utm_medium=feed&utm_campaign=zpravodaj&utm_content=main){:target="_blank"} (www.idnes.cz)
- [Falošné zľavy a ubytovanie v Chorvátsku: Slovenky oklamal podvodník, teraz nemajú dovolenku ani peniaze](https://spravy.rtvs.sk/2024/06/falosne-zlavy-a-ubytovanie-v-chorvatsku-slovenky-oklamal-podvodnik-teraz-nemaju-dovolenku-ani-peniaze/){:target="_blank"} (spravy.rtvs.sk)
- [Richard Kollár: Šéf vládnej komisie pre pandémiu Peter Kotlár tvrdí, že žiadna pandémia na Slovensku nebola. Čo tým sleduje?](https://www.tyzden.sk/politika/111261/richard-kollar-sef-vladnej-komisie-pre-pandemiu-peter-kotlar-tvrdi-ze-ziadna-pandemia-na-slovensku-nebola-co-tym-sleduje/){:target="_blank"} (www.tyzden.sk)

## 19.6. (středa)
- [Nemecko tvrdí, že Rusko investovalo veľké financie do náboru špiónov](https://www.teraz.sk/zahranicie/nemecko-rusko-si-po-vyhosteni-diplomat/802905-clanok.html){:target="_blank"} (www.teraz.sk, 18.06)
- [Výskumník Sloboda: Čitatelia viac dôverujú článkom, ak obsahujú informáciu o fact-checkingu (podcast)](https://www.aktuality.sk/clanok/66qHcTV/vyskumnik-sloboda-citatelia-viac-doveruju-clankom-ak-obsahuju-informaciu-o-fact-checkingu-podcast/){:target="_blank"} (www.aktuality.sk)
- [Finta z hoaxu nefunguje, ale už můžete Facebooku zakázat, aby na vás trénoval](https://www.seznamzpravy.cz/clanek/tech-ai-umela-inteligence-finta-z-hoaxu-nefunguje-ale-uz-muzete-facebooku-zakazat-aby-na-vas-trenoval-254147){:target="_blank"} (www.seznamzpravy.cz)
- [Mýty a fakta o Evropské unii: Je Unie prospěšná všem členským státům?](https://www.denik.cz/cesko-a-eu/pravda-a-lzi-o-evropske-unii-citaty-myty-a-fakta.html?utm_source=rss&utm_medium=feed&utm_campaign=www.denik.cz&utm_content=zpravy){:target="_blank"} (www.denik.cz)
- [Dezinformácie začínajú byť integrálnou súčasťou politických kampaní na Slovensku](https://euractiv.sk/section/digitalizacia/podcast/dezinformacie-hoaxy-volby-kampan-smer-sns-rusko/){:target="_blank"} (euractiv.sk)
- [Kůň výměnou za intimnosti. Nové dokumenty popisují, jak fungují vztahy Elona Muska s ženami ve SpaceX](https://cc.cz/kun-vymenou-za-intimnosti-nove-dokumenty-popisuji-jak-funguji-vztahy-elona-muska-s-zenami-ve-spacex/){:target="_blank"} (cc.cz)
- [Kino v centrálním Londýně zrušilo soukromé promítání filmu, jehož celý scénář napsala umělá inteligence](https://denikn.cz/minuta/1455884/){:target="_blank"} (denikn.cz)
- [Přes svůj účet nechal protéct milion korun. Investice se muži vymstila](https://www.novinky.cz/clanek/internet-a-pc-bezpecnost-pres-svuj-ucet-nechal-protect-milion-korun-investice-se-muzi-vymstila-40476972){:target="_blank"} (www.novinky.cz)
- [Japonská vláda stále doporučuje očkování proti covidu-19. Neočkovaným se neomlouvala](https://demagog.cz/diskuze/japonska-vlada-stale-doporucuje-ockovani-proti-covidu-19-neockovanym-se-neomlouvala){:target="_blank"} (demagog.cz)
- [Redaktoři slovenského deníku Pravda si stěžují na cenzuru a opouštějí redakci](https://www.novinky.cz/clanek/zahranicni-evropa-redaktori-slovenskeho-deniku-pravda-si-stezuji-na-cenzuru-a-opousti-redakci-40477034){:target="_blank"} (www.novinky.cz)
- [Místo politiků AI. V Anglii se o hlasy voličů uchází umělá inteligence](https://www.novinky.cz/clanek/internet-a-pc-ai-misto-politiku-ai-v-anglii-se-o-hlasy-volicu-uchazi-umela-inteligence-40477037){:target="_blank"} (www.novinky.cz)
- [Pozor, podvod. VR brýle Meta Quest 3 za poloviční cenu nekoupíte](https://www.zive.cz/clanky/nejlevnejsi-vr-bryle-meta-quest-3/sc-3-a-228729/default.aspx){:target="_blank"} (www.zive.cz)
- [Mimovládky kritizujú návrh zmien pri poskytovaní informácií, podľa rezortu vnútra sú potrebné](https://www.topky.sk/cl/10/2787539/Mimovladky-kritizuju-navrh-zmien-pri-poskytovani-informacii--podla-rezortu-vnutra-su-potrebne){:target="_blank"} (www.topky.sk)
- [Mimovládky obviňujú rezort vnútra zo snahy zaviesť cenzúru. Kvôli "limitovaným informáciám" spúšťajú petíciu](https://hnonline.sk/slovensko/96155317-mimovladky-obvinuju-rezort-vnutra-zo-snahy-zaviest-cenzuru-kvoli-limitovanym-informaciam-spustaju-peticiu){:target="_blank"} (hnonline.sk)

## 18.6. (úterý)
- [Umělá inteligence ve fast foodu? U McDonald’s v testu neuspěla](https://www.seznamzpravy.cz/clanek/zahranicni-umela-inteligence-ve-fast-foodu-u-mcdonalds-v-testu-neuspela-254181){:target="_blank"} (www.seznamzpravy.cz)
- [Hlavní hygienik USA volá po varovných nálepkách na sociální sítě](https://www.seznamzpravy.cz/clanek/zahranicni-socialni-site-skodi-americka-vlada-pozaduje-nalepky-jako-na-cigaretach-254115){:target="_blank"} (www.seznamzpravy.cz)
- [NÚKIB je pranýřován a nový zákon o kyberbezpečnosti i kvůli lobbingu vázne, uvedl šéf armády Řehka](https://www.lupa.cz/aktuality/nukib-je-pranyrovan-a-novy-zakon-o-kyberbezpecnosti-i-kvuli-lobbingu-vazne-uvedl-sef-armady-rehka/?utm_source=rss&utm_medium=text&utm_campaign=rss){:target="_blank"} (www.lupa.cz)
- [Německá kontrarozvědka: Více sledujeme krajní pravici a levici než islamisty](https://www.novinky.cz/clanek/zahranicni-evropa-nemecka-kontrarozvedka-vice-sledujeme-krajni-pravici-a-levici-nez-islamisty-40476845){:target="_blank"} (www.novinky.cz)
- [Dezinformace, reaguje AVU na kritiku. Vedení školy se zastali i studenti](https://ct24.ceskatelevize.cz/clanek/kultura/nahota-versus-stari-muzi-pokracuji-dohady-o-soucasne-akademii-vytvarneho-umeni-350373){:target="_blank"} (ct24.ceskatelevize.cz)
- [Známa banka čelí niekoľko dní kybernetickým útokom. Klientov upozorňuje, aby ignorovali podozrivé správy](https://news.refresher.sk/162063-Znama-banka-celi-niekolko-dni-kybernetickym-utokom-Klientov-upozornuje-aby-ignorovali-podozrive-spravy){:target="_blank"} (news.refresher.sk)
- [Facebook tvrdí, že príspevky s odkazom na zbierku Munícia pre Ukrajinu odstránil omylom](https://dennikn.sk/minuta/4053787/){:target="_blank"} (dennikn.sk)

## 17.6. (pondělí)
- [Deepfake videa s tančícím Zelenským pocházejí z ruského účtu na TikToku](https://cedmohub.eu/cs/deepfake-videa-s-tancm-zelenskm-pochzej-z-ruskho-tu-na-tiktoku){:target="_blank"} (cedmohub.eu)
- [Sociální síť X zaplavují falešné účty aerolinek. Vymáhají citlivé údaje](https://www.novinky.cz/clanek/internet-ai-falesne-ucty-aerolinek-vymahaji-citlive-udaje-40476733){:target="_blank"} (www.novinky.cz)
- [Ruská propaganda šíří, že naše prezidentka je lesba, líčí moldavský stand-up komik](https://zpravy.aktualne.cz/zahranici/moldavsko-komik-rozhovor/r~d18219d0231711ef801c0cc47ab5f122/?utm_source=mediafed&utm_medium=rss&utm_campaign=mediafed){:target="_blank"} (zpravy.aktualne.cz)
- [Rusku může globální oteplení pomoci, proto šíří klimatické lži, říká sociolog](https://www.idnes.cz/zpravy/domaci/klimaticke-dezinformace-vojtech-pecka-sociolog-rusko-fosilni-prumysl.A240606_111958_domaci_tty#utm_source=rss&utm_medium=feed&utm_campaign=zpravodaj&utm_content=main){:target="_blank"} (www.idnes.cz)
- [Počet profesionálních vojáků i záloh Armády ČR roste](https://demagog.cz/diskuze/pocet-profesionalnich-vojaku-i-zaloh-armady-cr-roste){:target="_blank"} (demagog.cz)
- [Firmy poslaly dopis premiérovi. Chtějí nové zadání pro NÚKIB ohledně kyberzákona](https://www.lupa.cz/aktuality/firmy-poslaly-nastvany-dopis-premierovi-chteji-nove-zadani-pro-nukib-ohledne-kyberzakona/?utm_source=rss&utm_medium=text&utm_campaign=rss){:target="_blank"} (www.lupa.cz)
- [Zlákala ji podvodná reklama s Jakubem Prachařem. Přišla o statisíce](https://www.novinky.cz/clanek/krimi-zlakala-ji-podvodna-reklama-s-jakubem-pracharem-prisla-o-statisice-40476650){:target="_blank"} (www.novinky.cz)
- [Falešní bankéři nabídli seniorovi z Olomouce pomoc, obrali jej o téměř 200 tisíc](https://www.novinky.cz/clanek/internet-a-pc-bezpecnost-falesni-bankeri-nabidli-seniorovi-z-olomouce-pomoc-obrali-jej-o-temer-200-tisic-40476637){:target="_blank"} (www.novinky.cz)
- [Průzkum: Čtenáři nedůvěřují využívání umělé inteligence ve zpravodajství](https://www.ceskenoviny.cz/zpravy/pruzkum-ctenari-neduveruji-vyuzivani-umele-inteligence-ve-zpravodajstvi/2532855?utm_source=rss&utm_medium=feed){:target="_blank"} (www.ceskenoviny.cz)
- [Facebook masívne maže príspevky o zbierkach pre Ukrajinu](https://www.sme.sk/c/23345069/facebook-odstranuje-informacie-o-zbierkach-pre-ukrajinu.html){:target="_blank"} (www.sme.sk)


## 14.6. - 16.6. (pátek, sobota, neděle)
- [Kasino na Kypru zůstává původním vlastníkům, informace o prodeji Zelenskému pochází z falešného webu](https://demagog.cz/diskuze/kasino-na-kypru-zustava-puvodnim-vlastnikum-informace-o-prodeji-zelenskemu-pochazi-z-falesneho-webu){:target="_blank"}
- [Piráti se chlubili metodikou na zadávání státní reklamy, sami ale svou politickou inzerci neuhlídali](https://www.irozhlas.cz/zpravy-domov/pirati-se-chlubili-metodikou-na-zadavani-statni-reklamy-sami-ale-svou-politickou_2406150500_pik){:target="_blank"}
- [Navzdory dezinformacím byznys šlape. Ochutnali jsme české cvrččí jerky, alternativu hovězích](https://cc.cz/navzdory-dezinformacim-byznys-slape-ochutnali-jsme-ceske-cvrcci-jerky-alternativu-hovezich/){:target="_blank"}
- [Nenechte se zmást. Pět kroků, jak odhalit dezinformační zprávu](https://www.zive.cz/clanky/nenechte-se-zmast-pet-kroku-jak-odhalit-dezinformacni-zpravu/sc-3-a-227657/default.aspx){:target="_blank"}
- [Umělá inteligence Luma dokáže z textového zadání vytvořit krátké video. Zkusit ji můžete zdarma](https://www.zive.cz/clanky/umela-inteligence-luma-dokaze-z-textoveho-zadani-vytvorit-kratke-video-zkusit-ji-muzete-zdarma/sc-3-a-228659/default.aspx){:target="_blank"}
- [Seznam Messenger bude konkurencí pro Facebook Messenger a WhatsApp. Připravuje mobilní appku i webový widget](https://mobilmania.zive.cz/clanky/seznam-messenger-bude-konkurenci-pro-facebook-messenger-a-whatsapp-pripravuje-mobilni-appku-i-webovy-widget/sc-3-a-1360299/default.aspx){:target="_blank"}
- [Konspirátor tvrdil, že se masakr, při kterém zemřelo 26 lidí, nestal. Jeho majetek půjde na odškodnění pozůstalých](https://zahranicni.hn.cz/c1-67334030-konspirator-tvrdil-ze-se-masakr-pri-kterem-zemrelo-26-lidi-nestal-jeho-majetek-pujde-na-odskodneni-pozustalych){:target="_blank"}
- [Akcionáři schválili obří odměnu pro Muska. Jaká je souvislost mezi jeho popularitou a úspěšností Tesly?](https://archiv.hn.cz/c1-67333110-proc-se-pohled-lidi-na-superhvezdu-muska-tolik-promenil-a-proc-byla-tak-zaslepujici){:target="_blank"}
- [Objavujú sa podvodné ponuky na ubytovanie v Chorvátsku: Ľudia prišli o tisíce eur](https://spravy.rtvs.sk/2024/06/objavuju-sa-podvodne-ponuky-na-ubytovanie-v-chorvatsku-ludia-prisli-o-tisice-eur/){:target="_blank"}
- [TikTok čelí útokům hackerů. Jedním kliknutím můžeš přijít o celý účet](https://news.refresher.cz/161929-TikTok-celi-utokum-hackeru-Jednim-kliknutim-muzes-prijit-o-cely-ucet){:target="_blank"}
