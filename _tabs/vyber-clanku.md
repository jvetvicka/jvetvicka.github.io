---
# the default layout is 'page'
title: Výběr článků
icon: fas fa-eye
order: 6
---

Výběr zahraničních článků, které se dotýkají dezinformací. Vychází z českého monitoringu, ale jsou zde zobrazeny pouze články, které prošly ručním výběrem. Zároveň je k nim poskytnut i krátký překlad.

<!-- Odkazy na klíčová slova -->
<button onclick="filterByKeyword('vsechna')" class="post-tag btn btn-outline-primary">vše</button>
<button onclick="filterByKeyword('fact-checking')" class="post-tag btn btn-outline-primary">fact-checking</button>
<button onclick="filterByKeyword('dezinformace')" class="post-tag btn btn-outline-primary">dezinformace</button>
<button onclick="filterByKeyword('kyberbezpecnost')" class="post-tag btn btn-outline-primary">kyberbezpečnost</button>
<button onclick="filterByKeyword('AI')" class="post-tag btn btn-outline-primary">AI</button>
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
          novinka.style.display = 'block';
        } else {
          novinka.style.display = 'none';
        }
      });
    }
</script>

<div class="novinka" data-keywords="dezinformace, AI"><div class="monitoring-title"><a href="https://www.polygraph.info/a/7677588.html" target="_blank">Během rwandské prezidentské kampaně byly odhaleny dezinformace generované umělou inteligencí</a></div>
<small><i class="fa-regular fa-calendar"></i> 29.06.</small> <code class="highlighter-rouge">AI</code> <code class="highlighter-rouge">dezinformace</code>
<p>Současný prezident Paul Kagame po 24 letech vládnutí opět usiluje o znovuzvolení. Jeho vládnutí však kritizuje nejen opozice, ale i lidskoprávní organizace. Aby se vypořádal s kritikou a ospravedlnil své další funkční období, spustila jeho vláda koordinovanou online kampaň, která využívá AI ke generování a šíření politické propagandy. Podle zjištění Media Forensics Hub od ledna 2024 sdílelo 464 X účtů 650 000 příspěvků vytvořených pomocí AI. Šlo jak o texty, tak obrázky. <small>(polygraph.info)</small></p></div>

