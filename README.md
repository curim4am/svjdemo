# Hlasování SVJ — DEMO (ukázka)

Ukázková verze aplikace pro vedení schůze shromáždění SVJ (prezence → usnášeníschopnost → hlasování → protokol). Slouží k tomu, aby si ji sousedé mohli **prohlédnout a vyzkoušet**, jak funguje.

**Všechna data jsou smyšlená** — jména, vlastnické podíly i schůze jsou vymyšlené a neodpovídají skutečnosti. Nejde o žádné reálné hlasování.

## Co v demu najdete

- **24 jednotek** s ukázkovými jmény a podíly (součet 100 %).
- **2 uzavřené schůze** (řádná a mimořádná) s hotovými protokoly.
- **1 probíhající schůzi** (řádná), kde už proběhlo pár hlasování.
- V každé schůzi 2–3 usnesení — přijatá i nepřijatá, ať je vidět, jak se počítá výsledek podle podílů a podle potřebné většiny.

## Jak si to prohlédnout

1. Otevři **index.html** v prohlížeči (Chrome, Edge, Firefox). Demo data se načtou sama.
2. Klikni na některou schůzi v „Historii schůzí" → projdi **Prezenci**, **Hlasování** a **Přehled a protokol**.
3. V „Přehled a protokol" dej **🖨 Tisk protokolu** a vyzkoušej přepínač **Kompletní / Zjednodušený protokol**.

Cokoli v demu naklikáš zůstane jen v tvém prohlížeči (v „localStorage") a nikoho se to netýká. Když chceš demo vrátit do původního stavu, smaž data webu pro tuto stránku v prohlížeči.

## Nahrání na web (GitHub Pages)

1. Založ repozitář na GitHubu a nahraj do něj **index.html** (název `index.html` je nutný).
2. Settings → Pages → Source „Deploy from a branch", branch `main`, složka `/root` → Save.
3. Za chvíli demo poběží na `https://tvojejmeno.github.io/nazev-repa/` a můžeš odkaz poslat sousedům.

Pro demo je nahrání na web bezpečné — neobsahuje žádné skutečné osobní údaje. (U ostré verze aplikace naopak nikdy nenahrávej zálohu `.json` se skutečnými jmény a podíly.)

---
© 2026 curim4am
