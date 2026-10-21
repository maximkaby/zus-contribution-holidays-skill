# zus-contribution-holidays — Claude Code skill

**English** | [Polski](#wersja-polska)

## 💰 Save up to 1 926 zł — skip one month of ZUS contributions

A [Claude Code](https://claude.com/claude-code) skill that helps Polish entrepreneurs apply for **wakacje składkowe** — a one-month exemption from ZUS social contributions (the **RWS** application in eZUS).

Claude checks eligibility, helps prepare the data, walks the user through every screen of the eZUS wizard, explains each «TAK/NIE» answer, and after submission explains the deadlines and offers a reminder. It answers in the user's language (Polish, Russian, Ukrainian, English, …) and keeps Polish button and field names exactly as in eZUS.

> Claude never files or signs the application — login and signing are done by the user. This is guidance, not legal or tax advice. Rules may change: check [zus.pl](https://www.zus.pl).

## How much you save

One month without social contributions in 2026 — approximately:

- **Pełny ZUS:** ≈ **1926.76 zł**
- **Preferencyjny ZUS:** ≈ **456.18 zł**
- **Mały ZUS Plus:** depends on your income

Składka zdrowotna (health insurance) is not covered and is still due. Amounts change every year — check [zus.pl](https://www.zus.pl).

## Video example

Want to see the whole process first? Watch the official ZUS tutorial with a full example of filling in the RWS application (Polish, ~3 min):

▶️ https://www.youtube.com/watch?v=AfuqKwYIvNI

The video may look slightly different from the current eZUS — the skill follows the current wizard screens. Claude also shares the link with the user at the start.

## What it covers

- **Eligibility** — a short list of disqualifiers and one yes/no question instead of an interview:
  - not registered in CEIDG;
  - not a mikroprzedsiębiorca (10+ employees or turnover > EUR 2M);
  - revenue > EUR 2M in both of the last 2 years;
  - B2B for a former employer doing the same work;
  - already used this calendar year.
- **Exemption month** — always the month after filing (filled in automatically by eZUS).
- **What is exempted** — the owner's own social insurance, voluntary sickness insurance, Fundusz Pracy and Fundusz Solidarnościowy. **Not** składka zdrowotna, not employees' contributions.
- **Preparation** — how to find the main PKD code (CEIDG, REGON), de minimis aid from the last 3 years (previous wakacje od ZUS count too).
- **The wizard, screen by screen:**
  1. «Rodzaj wniosku»
  2. «Dane płatnika»
  3. «Treść wniosku»
  4. «Oświadczenia»
  5–8. de minimis część 1–4
  9. «Załączniki»
  10. «Podpisz i wyślij»
- **After submission:**
  - ZUS decides within **30 days**;
  - if ZUS sends a request to supplement the application, the user has **7 days** to answer via «Uzupełnienie/korekta wniosku»;
  - the application can be withdrawn via «Wycofanie wniosku».
- **Reminder** — with the user's consent, one calendar event 7 days after filing to check eZUS for a ZUS request (Google Calendar if connected, otherwise an `.ics` file or just the date).

## Files

| File | Purpose |
|---|---|
| `zus-contribution-holidays/SKILL.md` | Main instructions Claude loads |
| `zus-contribution-holidays/ezus-screens.md` | Real eZUS screen texts (Polish) with how to answer each question |
| `zus-contribution-holidays/source-transcript.txt` | Polish subtitles of the official ZUS video tutorial |

## Install

Install with the [skills](https://skills.sh) CLI. Requires [Node.js](https://nodejs.org). Run in your project folder:

```bash
# this project only (installs into .claude/skills/)
npx skills add maximkaby/zus-contribution-holidays-skill -a claude-code

# all your projects (installs into ~/.claude/skills/)
npx skills add maximkaby/zus-contribution-holidays-skill -a claude-code -g
```

### Check that it works

Start a **new** Claude Code session (skills are loaded at startup) and:

- type `/skills` — `zus-contribution-holidays` should be in the list, or
- just ask, e.g. «Jak złożyć wniosek o wakacje od ZUS?» or «Can I take ZUS contribution holidays?».

## Sources

- eZUS screens of the RWS wizard (October 2026).

## Known gaps

- Fields of the de minimis «oświadczenie» form are not documented.
- Where the previous year's de minimis certificate is located in eZUS is not verified.
- What happens if the 7-day deadline is missed, and from when it is counted, is not verified.
- Exact labels on biznes.gov.pl / REGON search are not verified.

When the skill hits a gap, Claude says so and refers the user to zus.pl or an accountant instead of guessing.

## Contributing

Found something inaccurate or outdated — a changed eZUS screen, a new rule, a wrong button name? Contributions are welcome:

- open an **Issue** describing what is wrong (a screenshot of the current eZUS screen helps a lot), or
- **fork** the repository, fix it and send a **Pull Request**.

You are also free to copy the skill and adapt it for your own use.

## License

[MIT](LICENSE) — you may use, copy, modify and distribute this skill, including commercially, as long as the license notice is kept. Provided "as is", without warranty.

---

# Wersja polska

[English](#zus-contribution-holidays--claude-code-skill) | **Polski**

## 💰 Zaoszczędź nawet 1 926 zł — miesiąc bez składek ZUS

Skill dla [Claude Code](https://claude.com/claude-code), który pomaga przedsiębiorcom w Polsce złożyć wniosek o **wakacje składkowe** — zwolnienie z opłacania składek ZUS za jeden miesiąc (wniosek **RWS** w eZUS).

Claude sprawdza, czy przysługuje Ci ulga, pomaga przygotować dane, prowadzi przez każdy ekran kreatora w eZUS, wyjaśnia każdą odpowiedź «TAK/NIE», a po wysłaniu wniosku przypomina o terminach i proponuje przypomnienie w kalendarzu. Odpowiada w języku użytkownika (polski, rosyjski, ukraiński, angielski, …), a nazwy przycisków i pól zostawia dokładnie takie jak w eZUS.

> Claude nigdy nie składa ani nie podpisuje wniosku za Ciebie — logowanie i podpis wykonujesz sam. To pomoc, a nie porada prawna ani podatkowa. Przepisy mogą się zmienić: sprawdź [zus.pl](https://www.zus.pl).

## Ile oszczędzasz

Jeden miesiąc bez składek społecznych w 2026 roku — w przybliżeniu:

- **Pełny ZUS:** ≈ **1926,76 zł**
- **Preferencyjny ZUS:** ≈ **456,18 zł**
- **Mały ZUS Plus:** zależy od Twojego dochodu

Składka zdrowotna nie jest objęta zwolnieniem i trzeba ją zapłacić. Kwoty zmieniają się co roku — sprawdź na [zus.pl](https://www.zus.pl).

## Film z przykładem

Chcesz najpierw zobaczyć cały proces? Obejrzyj oficjalny poradnik ZUS z pełnym przykładem wypełnienia wniosku RWS (ok. 3 min):

▶️ https://www.youtube.com/watch?v=AfuqKwYIvNI

Ekrany w filmie mogą się nieco różnić od obecnego eZUS — skill opiera się na aktualnych ekranach kreatora. Claude podaje ten link użytkownikowi na początku.

## Co obejmuje

- **Prawo do ulgi** — krótka lista sytuacji, które wykluczają, i jedno pytanie tak/nie zamiast długiego wywiadu:
  - działalność nie jest wpisana do CEIDG;
  - nie jesteś mikroprzedsiębiorcą (10+ pracowników lub obrót > 2 mln euro);
  - przychód > 2 mln euro w obu ostatnich latach;
  - B2B dla byłego pracodawcy w tym samym zakresie, co na umowie o pracę;
  - ulga została już wykorzystana w tym roku kalendarzowym.
- **Miesiąc zwolnienia** — zawsze miesiąc po miesiącu złożenia wniosku (eZUS uzupełnia go automatycznie).
- **Co obejmuje zwolnienie** — Twoje własne obowiązkowe ubezpieczenia społeczne, dobrowolne ubezpieczenie chorobowe, Fundusz Pracy i Fundusz Solidarnościowy. **Nie obejmuje** składki zdrowotnej ani składek za pracowników.
- **Przygotowanie** — jak znaleźć główny kod PKD (CEIDG, REGON), pomoc de minimis z ostatnich 3 lat (poprzednie wakacje od ZUS też się liczą).
- **Kreator krok po kroku:**
  1. «Rodzaj wniosku»
  2. «Dane płatnika»
  3. «Treść wniosku»
  4. «Oświadczenia»
  5–8. de minimis część 1–4
  9. «Załączniki»
  10. «Podpisz i wyślij»
- **Po wysłaniu:**
  - ZUS rozpatruje wniosek w ciągu **30 dni**;
  - jeśli ZUS wezwie do uzupełnienia wniosku, masz **7 dni** na odpowiedź przez «Uzupełnienie/korekta wniosku»;
  - wniosek można wycofać przez «Wycofanie wniosku».
- **Przypomnienie** — za Twoją zgodą jedno wydarzenie w kalendarzu 7 dni po złożeniu wniosku: sprawdź w eZUS, czy ZUS nie przysłał wezwania (Google Calendar, jeśli jest podłączony, w przeciwnym razie plik `.ics` albo po prostu data).

## Pliki

| Plik | Do czego służy |
|---|---|
| `zus-contribution-holidays/SKILL.md` | Główne instrukcje, które ładuje Claude |
| `zus-contribution-holidays/ezus-screens.md` | Teksty z ekranów eZUS i jak odpowiadać na każde pytanie |
| `zus-contribution-holidays/source-transcript.txt` | Napisy z oficjalnego poradnika wideo ZUS |

## Instalacja

Instalacja przez CLI [skills](https://skills.sh). Wymagany [Node.js](https://nodejs.org). Uruchom w folderze projektu:

```bash
# tylko ten projekt (instaluje do .claude/skills/)
npx skills add maximkaby/zus-contribution-holidays-skill -a claude-code

# wszystkie Twoje projekty (instaluje do ~/.claude/skills/)
npx skills add maximkaby/zus-contribution-holidays-skill -a claude-code -g
```

### Sprawdź, czy działa

Uruchom **nową** sesję Claude Code (skille ładują się przy starcie) i:

- wpisz `/skills` — na liście powinien być `zus-contribution-holidays`, albo
- po prostu zapytaj, np. «Jak złożyć wniosek o wakacje od ZUS?».

## Źródła

- Ekrany kreatora RWS w eZUS (październik 2026).

## Czego jeszcze brakuje

- Pola formularza «oświadczenie» o pomocy de minimis nie są opisane.
- Nie sprawdzono, gdzie w eZUS znajduje się zaświadczenie de minimis z poprzedniego roku.
- Nie sprawdzono, co się dzieje po przekroczeniu 7-dniowego terminu i od kiedy jest liczony.
- Nie sprawdzono dokładnych nazw przycisków w wyszukiwarce biznes.gov.pl / REGON.

Gdy skill natrafi na taką lukę, Claude mówi o tym wprost i odsyła do zus.pl lub księgowego, zamiast zgadywać.

## Jak pomóc

Znalazłeś nieścisłość albo coś nieaktualnego — zmieniony ekran w eZUS, nowe przepisy, błędną nazwę przycisku? Każda pomoc jest mile widziana:

- otwórz **Issue** z opisem problemu (zrzut ekranu z aktualnego eZUS bardzo pomaga), albo
- zrób **fork** repozytorium, wprowadź poprawki i wyślij **Pull Request**.

Możesz też swobodnie skopiować skill i dostosować go do własnych potrzeb.

## Licencja

[MIT](LICENSE) — możesz używać, kopiować, zmieniać i rozpowszechniać ten skill, także komercyjnie, pod warunkiem zachowania informacji o licencji. Udostępniany „tak jak jest”, bez żadnych gwarancji.
