# Povolení k práci – Knauf Insulation, závod Krupka

Webová aplikace pro digitální vedení povolení k práci (jeden soubor `index.html`, bez instalace a bez serveru).

**Spuštění:** https://holyvatz-cyber.github.io/povoleni-k-praci/
**Board na TV:** https://holyvatz-cyber.github.io/povoleni-k-praci/#board

## Propojené formuláře
| Formulář | Obsah v aplikaci |
|---|---|
| **KI_F_057** Povolení k práci | sekce 1–10: dodavatel a kontakty, rizika, systém bezpečné práce, prohlášení, dodatečná povolení, odpojení/LOTO, OOPP, vydání a schválení, pracovníci, prodloužení, ukončení a předání |
| **KK_053** Příkaz ke svařování / povolení k práci s otevřeným ohněm | svářeči, opatření, požární dohled, průběh svařování a dohled po svařování (min. 8 h, kontroly v intervalech) |
| **KK_047** Testování atmosféry v uzavřených prostorech | prostor, měření plynů s vyhodnocením limitů, body A/B/C, vstupující osoby, předání/převzetí |

## Originál a kopie
- **Originál** – záznam v aplikaci, držitel = odpovědná osoba KI.
- **Kopie – digitální board** – režim pro TV, automatická obnova, odpočty platnosti, požární dohled, uzavřené prostory.
- **Kopie – mobil příjemce** – QR kód, kopie pouze pro čtení bez přihlášení; data jsou zakódována přímo v odkazu. Aplikace hlídá, zda kopie neodpovídá aktuálnímu stavu.
- **Tisk** – ORIGINÁL / KOPIE board / KOPIE příjemce / KOPIE IMS, zapisuje se do registru kopií.

## Důležité
- Data se ukládají **v prohlížeči daného zařízení** (localStorage). Pravidelně exportujte zálohu JSON (Nastavení → Data). Pro sdílení mezi více zařízeními je potřeba sdílené úložiště (další etapa).
- Limity plynů (KK_047) jsou výchozí orientační hodnoty – před použitím je ověřte a schvalte s HSE / technikem PO.
- V Nastavení vyplňte **Veřejnou adresu aplikace** (`https://holyvatz-cyber.github.io/povoleni-k-praci/`), aby QR kódy mobilních kopií fungovaly.

Licence knihovny QR: qrcode-generator © Kazuhiko Arase, MIT. „QR Code“ je registrovaná ochranná známka DENSO WAVE INCORPORATED.
