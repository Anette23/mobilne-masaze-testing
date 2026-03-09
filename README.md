# Portfolio Project: QA Manual Testing – mobilnemasaze.eu

Tento projekt slúži ako ukážka mojich zručností v oblasti manuálneho testovania webových aplikácií. Zameriava sa na overenie funkčnosti, použiteľnosti a používateľskej skúsenosti (UX) webovej stránky pre služby mobilného maséra.

**Testovaný web:** https://www.mobilnemasaze.eu

---

## 🛠 Rozsah projektu (Project Scope)
Cieľom projektu bolo vykonať manuálne testovanie objednávkového formulára ako kľúčového biznis procesu webovej stránky. Testovanie zahŕňalo prípravu test planu, tvorbu testovacích prípadov, ich následné vykonávanie (test execution) a reportovanie chýb.

Zameranie testovania:
- **Objednávkový proces:** Odoslanie objednávky, validačné scenáre, chybové stavy.
- **Validácia dát:** Email, telefón, dátum, povinné polia, extrémne vstupy.
- **Bezpečnosť:** Základné testy SQL Injection a XSS v input poliach.
- **UX & navigácia:** Scrollovanie k formuláru z rôznych častí webu, správanie success popupu.
- **Responzivita:** Funkčnosť formulára na mobile a tablete.
- **Kompatibilita:** Testovanie v rôznych prehliadačoch (Chrome, Firefox, Edge).
- **Výkon:** Odozva formulára pri odoslaní objednávky.

---

## 📂 Štruktúra repozitára
- **`01_TestPlan/`** – Testovací plán: rozsah, stratégia, prostredie, vstupné a výstupné kritériá.
- **`02_TestCases/` – Testovacie prípady rozdelené do troch súborov:
    * `TC_OrderForm.md` – Objednávkový formulár (TC-001 – TC-020)
    * `TC_Reviews.md` – Sekcia Recenzie (TC-R01 – TC-R13)
    * `TC_Website.md` – Navigácia, Hero, O mne, Výhody, Služby, Darčekové poukážky, Animácie, Responzívnosť, Výkon (TC-N01 – TC-P03)
    - **`03_BugReports/`** – Reporty chýb (Summary, Steps to Reproduce, Expected vs. Actual Result, Severity, Priority).
- **`04_TestExecution/`** – Záznamy z vykonávania testov (PASS / FAIL / BLOCKED, odkazy na bugy).
- **`05_ExploratoryTesting/`** – Záznamy z prieskumného testovania a UX poznámky.

---

## 🚀 Použité technológie a nástroje
- **Typ testovania:** Manuálne testovanie (Black Box)
- **Dokumentácia:** Markdown (GitHub)
- **Nástroje:** Browser DevTools, Lighthouse (základná kontrola výkonu)
- **Prehliadače / zariadenia:** Chrome, Firefox, Edge, Mobile (DevTools)

---

## 💡 Čo som sa naučila
Počas tohto projektu som si precvičila:
- návrh a štruktúrovanie testovacích prípadov pre kritický formulár,
- vykonávanie manuálneho testovania a evidenciu výsledkov,
- reportovanie funkčných, validačných a UX chýb,
- identifikáciu bezpečnostných rizík v input poliach,
- pohľad na web z perspektívy koncového používateľa.
