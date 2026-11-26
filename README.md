# Povolení k práci – Knauf Insulation, závod Krupka

Webová aplikace pro digitální vedení povolení k práci (jeden soubor `index.html`, bez instalace a bez serveru).

**Spuštění:** https://holyvatz-cyber.github.io/povoleni-k-praci/
**Board na TV:** https://holyvatz-cyber.github.io/povoleni-k-praci/#board

## Instalace do PC a telefonu
Aplikace je PWA – po instalaci má vlastní ikonu, okno a funguje i offline.
- **PC (Chrome / Edge):** tlačítko **Instalovat** v aplikaci nebo ikona instalace v adresním řádku. Zástupci: *Digitální board*, *Nové povolení* (pravé tlačítko na ikoně).
- **Android:** Chrome → ⋮ → *Instalovat aplikaci*.
- **iPhone:** Safari → *Sdílet* → *Přidat na plochu*.

## Asistent nastavení (PC)
Tlačítko vpravo dole. Rozumí pokynům v češtině i angličtině, např. `limit CO 30`, `kyslík 19,5–23,5`, `přidej prostor Silo 3`, `přidej přístroj Dräger X-am 2500`, `tísňové číslo 150 / 112`, `dohled po svařování 10 h`, `zobraz nastavení`, `historie změn`, `zpět`. Každá změna se potvrdí, zapíše do historie a dá se vrátit. Nebezpečné hodnoty (např. dohled < 8 h, O₂ min < 18 %) odmítne.

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
