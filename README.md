# 🎬 NexaStream - Kodi Addon (VIP Gold Edition)

NexaStream je prémiový Kodi doplněk navržený pro maximální pohodlí, rychlost a vizuální zážitek ze sledování filmů a seriálů. Spojuje obrovskou databázi obsahu s inteligentními funkcemi, které znáte z moderních streamovacích platforem.

## 🚀 Hlavní funkce (Co umíme)

* **Smart Autoplay (Netflix Styl):** Nepřerušované sledování! Stačí kliknout na epizodu a doplněk automaticky vybere nejvyšší kvalitu a plynule přehraje zbytek série. Plná podpora pro oblíbený doplněk **Up Next**!
* **VIP Trezor & Český Dabing:** Exkluzivní sekce s ručně tříděným obsahem v té nejvyšší kvalitě (4K, UHD) s primárním zaměřením na CZ dabing.
* **Dětský svět (Kids Mode):** Bezpečná a oddělená sekce plná pohádek, oblíbených večerníčků a animáků. 100% ochrana před obsahem pro dospělé.
* **Auto-Healing Metadata:** Bleskové načítání i složek se 100+ díly díky vnitřní paměti (Cache). Doplněk si sám na pozadí doplňuje chybějící české názvy, popisy a plakáty z TMDB.
* **Barevné hodnocení ČSFD a TMDB:** Ihned vidíte, na co má smysl koukat. Originální barevné škály ČSFD (🔴🔵⚪) přímo v názvech titulů.
* **Chytré vyhledávání a Wishlist:** Pokročilé hledání podle herců, žánrů nebo roků. Pokud něco nenajdete, doplněk to tiše odešle jako "Poptávku" na náš server a brzy to přidáme do Trezoru!
* **Plná personalizace (Možnosti nastavení):**
  * Volba mezi Autoplayem a manuálním výběrem kvality.
  * Možnost skrýt celé sekce (např. Dětský svět) z hlavního menu pro čistší vzhled.
  * Omezovač dat (nastavení maximálního rozlišení pro pomalejší internet).
  * Vlastní nastavení procent (70–95 %) pro automatické označení filmu za "Zhlédnutý".
* **Lokální stahování:** Možnost stáhnout si jakýkoliv film nebo epizodu na lokální disk pro sledování offline.

---

## 🆕 Poslední velké aktualizace (Changelog doplňku)

**v3.8.0 (Velký Autoplay & Settings Update)**
* `[NOVÉ]` Smart Autoplay - automatické přehrávání dalších dílů seriálů (Netflix styl).
* `[NOVÉ]` Plná integrace a podpora pro doplňek Up Next.
* `[NOVÉ]` Pokročilé Menu Nastavení (Vypínání sekcí v menu, volba zhlédnutých %, omezovač kvality).
* `[NOVÉ]` Auto-Healing cache systém - bleskové načítání složek se 100+ epizodami bez timeoutů.
* `[NOVÉ]` Tlačítka pro kompletní smazání historie zhlédnutých a hledání přímo z nastavení.
* `[OPRAVA]` Opraveno padání (Timeout) Kodi při otevírání seriálů s velkým počtem epizod.
* `[OPRAVA]` Barevné ČSFD hodnocení opraveno a optimalizováno (vynecháno pro epizody pro maximální rychlost).
* `[OPRAVA]` SQL optimalizace Trezoru (api.php) - opraveno zahlcení seznamu nejnovějších seriálů jedním titulem.
* `[ÚPRAVA]` Vyčištění GUI od nepodporovaných Unicode (emoji) znaků pro čistší vzhled na všech zařízeních.
* `[ÚPRAVA]` Sjednocení API volání na HTTP protokol pro maximální stabilitu a rychlost spojení.

---

## 🎛️ Chytrý Admin Panel

Aby byl obsah v Kodi vždy stoprocentní, disponuje projekt vlastním administrátorským rozhraním pro správu databáze, které proces nahrávání maximálně automatizuje:

* **Hloubkový rentgen odkazů (AJAX):** Konec hádání metadat z názvu souboru! Panel se na pozadí přímo dotazuje API Websharu a stahuje **reálnou kvalitu obrazu (např. 1080p, 4K)** a **skutečnou zvukovou stopu** dříve, než se cokoliv uloží.
* **Ochrana proti chybám TMDB:** Při nahrávání seriálů panel automaticky křížově kontroluje čísla dílů s databází TMDB. Pokud zadáte S01E111 a TMDB tento díl nezná, panel vás okamžitě vizuálně varuje.
* **Asynchronní hromadné zpracování:** Možnost vložit desítky linků najednou. Díky modernímu asynchronnímu JavaScriptu se prohlížeč během skenování nesekne a vy ihned vidíte krásný vizuální náhled všech dat.
* **Auto-párování metadat:** Systém sám z názvů souborů vyextrahuje číslo série a epizody a bleskově je napáruje na oficiální české názvy epizod z TMDB.

### 🆕 Poslední velké aktualizace (Changelog Admin Panelu)
* `[NOVÉ]` Chytrý Admin Panel (index.php) - Kompletní přepis logiky pro hromadné přidávání linků.
* `[NOVÉ]` AJAX skenování Webshare API pro získání reálné kvality a jazyka (namísto parsování z názvu).
* `[NOVÉ]` Asynchronní chod a ochrana proti zamrznutí prohlížeče při vkládání velkého množství epizod.
* `[OPRAVA]` Zavedena vizuální křížová kontrola epizod s TMDB přímo v náhledu (prevence "prázdných složek" v Kodi).

---

## 🤝 HLEDÁME TESTERY A UPLOADERY!

NexaStream je aktuálně v **uzavřené beta verzi**. Hledáme nadšence, kteří nám pomohou projekt otestovat, a spolehlivé uploadery, kteří s námi budou plnit náš Trezor tím nejlepším obsahem. 
Vize je taková, že z příspěvků bude hrazen provoz doplňku (žádné velké náklady) a přispívat aktivním uploaderům.

### Jak se zapojit do projektu?
Jelikož jde o privátní projekt, přístup (Kodi doplněk + klíč) rozdáváme přes pozvánkový systém.

1. **Ukažte zájem (Hlasování):** Dejte tomuto repozitáři ⭐️ **STAR** (hvězdičku) nahoře vpravo. Čím více hvězdiček, tím rychleji projekt otevřeme pro další vlnu!
2. **Zažádejte o pozvánku:** Vyplňte náš krátký dotazník a dejte nám vědět, zda chcete pouze testovat, nebo se zapojit i jako Uploader s přístupem do našeho VIP CMS systému.  
   👉 **[KLIKNĚTE ZDE PRO ŽÁDOST O POZVÁNKU](https://forms.gle/cxMgdkbjeMpvyjun8)**
3. **Zapojte se do diskuze:** Máte nápad? Narazili jste na problém? Přejděte do záložky **[Discussions](https://github.com/nexastream-pro/nexastream-pro/discussions)** zde na GitHubu a řekněte nám svůj názor!

---
*NexaStream - Tvoříme komunitu společně.*
