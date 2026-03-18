# 🚀 NexaStream (Kodi Addon & CMS)
> Ultimátní, bleskově rychlý a exkluzivní streamovací ekosystém pro Kodi, postavený na privátní databázi a špičkovém administračním rozhraní.

NexaStream není jen další doplněk. Je to kompletně přepsaná architektura, která spojuje **stabilitu oficiálního TMDB API**, **oblíbená hodnocení z ČSFD** a **vlastní zabezpečenou databázi** prověřených streamů v té nejvyšší kvalitě.

---

## 🎬 Výhody pro diváky (Kodi Addon)
NexaStream v Kodi nabízí čistý, rychlý a ničím nerušený zážitek ze sledování.
* 🌟 **Smart VIP Radar:** Systém okamžitě pozná, že je film v naší exkluzivní databázi. Tyto prémiové linky vystřelí na absolutně první místo ve vyhledávání a označí je zlatou hvězdou.
* 💯 **Nativní ČSFD Procenta:** U každého našeho filmu rovnou vidíte přesné procentuální hodnocení z ČSFD (barevně odlišené), aniž by Kodi muselo cokoliv zdlouhavě stahovat.
* ⚡ **Ultra-Rychlé hledání (Unicode Safe):** Kompletně přepsané vyhledávací jádro napojené přímo na TMDB REST API. Bez pádů, bez chyb a s plnou podporou české diakritiky (háčky a čárky už nejsou problém).
* 🧹 **Čistý design:** Žádný balast v názvech. Naše linky zobrazují pouze čistý název, rozlišení (např. 4K, 1080p), audio, dabing a velikost souboru. 
* 📚 **Integrace do knihovny:** Přímý export do knihovny Kodi (STRM) a dokonalá synchronizace historie zhlédnutí ("Pokračovat ve sledování").

---

## ⚙️ NexaStream CMS (Nástroj snů pro Uploadery)
Pro chod projektu jsme vyvinuli vlastní "Master CMS". Tvorba databáze nikdy nebyla tak pohodlná, rychlá a "blbuvzdorná".
* 🤖 **Auto-ČSFD Scraper:** Uploader pouze vybere film z TMDB. Náš chytrý cURL robot na pozadí prorazí ochrany a sám vytěží procenta z ČSFD (s chytrou zálohou z TMDB v případě výpadku). 
* 🎛️ **Live Editor s Náhledem:** Po vložení zdrojového linku se okamžitě vygeneruje náhledový obrázek, vypíše se datový tok (bitrate) a systém pomocí regex map automaticky předvyplní kvalitu, audio a dabing. Uploader má před uložením plnou kontrolu nad finálním štítkem.
* 🚨 **Skener Mrtvých Linků (Karanténa):** CMS obsahuje zabudovaný radar, který na jedno kliknutí obvolá servery. Pokud najde smazaný soubor, vybublá ho na první místo v tabulce, označí ho jako DEAD a před Kodi ho dočasně skryje. Uploader jej může jediným kliknutím "Opravit".
* 🏆 **Uploader Leaderboard (Připravujeme):** Systém osobních účtů pro uploadery, kde každý vidí, kolik přispěl do společného Trezoru.

---

## 🆕 Poslední velké aktualizace (Changelog)
* **[REFACTOR]** Odstraněn zastaralý HTML ČSFD scraper z Kodi (zrychlení doplňku, ochrana proti IP banům).
* **[NEW]** Implementováno bezpečné API zabezpečené tokenem mezi Kodi a databází.
* **[FIX]** Chytrá výhybka pro epizody seriálů – přiřazování záložních hodnot audia a dabingu při selhání detekce zdrojového souboru.

---

## 🤝 HLEDÁME TESTERY A UPLOADERY!
NexaStream je aktuálně v **uzavřené beta verzi**. Hledáme nadšence, kteří nám pomohou projekt otestovat, a spolehlivé uploadery, kteří s námi budou plnit náš Trezor tím nejlepším obsahem.
Vize je taková, že s příspěvků bude hrazen provoz doplňku (žádné velké náklady) a přispívat aktivním uploaderům.

### Jak se zapojit do projektu?
Jelikož jde o privátní projekt, přístup (Kodi doplněk + klíč) rozdáváme přes pozvánkový systém.

1. **Ukažte zájem (Hlasování):** Dejte tomuto repozitáři ⭐️ **STAR** (hvězdičku) nahoře vpravo. Čím více hvězdiček, tím rychleji projekt otevřeme pro další vlnu!
2. **Zažádejte o pozvánku:** Vyplňte náš krátký dotazník a dejte nám vědět, zda chcete pouze testovat, nebo se zapojit i jako Uploader s přístupem do našeho VIP CMS systému.
   👉 **[KLIKNĚTE ZDE PRO ŽÁDOST O POZVÁNKU - https://forms.gle/cxMgdkbjeMpvyjun8]**
3. **Zapojte se do diskuze:** Máte nápad? Narazili jste na problém? Přejděte do záložky **[Discussions](https://github.com/nexastream-pro/nexastream-pro/discussions)** zde na GitHubu a řekněte nám svůj názor!

---
*NexaStream - Tvoříme komunitu společně.*
