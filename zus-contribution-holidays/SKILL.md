---
name: zus-contribution-holidays
description: Use when a Polish entrepreneur (JDG, mikroprzedsiębiorca) asks about "wakacje składkowe", "wakacje od ZUS", the RWS application (wniosek o zwolnienie z obowiązku opłacania składek za wskazany miesiąc), eligibility for a one-month ZUS contribution exemption, de minimis questions in that form, or how to file it in eZUS / PUE ZUS — in any language (Polish, Russian, Ukrainian, English).
---

# Wakacje składkowe (RWS application in eZUS)

**English** | [Polski](#wersja-polska)

> The same instructions are given twice: first in English, then in Polish. Both versions say the same thing — follow either one.

## Overview

You help an entrepreneur check eligibility, prepare the data, and walk through the RWS wizard in eZUS. **You cannot file the application for them**: login (Profil Zaufany / mObywatel / username and password) and signing are done by the user only. Reply in the user's language; keep Polish field and button names exactly as they appear in the UI.

At the start, tell the user they can watch the official ZUS video with a full example of filling in the application (Polish, ~3 min): https://www.youtube.com/watch?v=AfuqKwYIvNI — and mention that the screens in the video may look slightly different from the current eZUS.

Sources: ZUS video tutorial (`source-transcript.txt`) and real eZUS screens (`ezus-screens.md` — question texts and how to answer them). If the user sends a screenshot, explain based on it; if the screen differs from this skill, trust the screen.

## Workflow

1. **Check eligibility** — don't ask a list of questions. Show the disqualifiers from «Eligibility» and ask one yes/no question: «Does any of this apply to you?». «No» → eligible, move on. «Yes» → find out which one and say plainly what it means. Skip items the user has already answered.
2. **Compute the exemption month** — the month following the month of filing.
3. **Prepare data**: main PKD code (where to find it — `ezus-screens.md`); de minimis aid from the last 3 years, including previous wakacje od ZUS (date, amount, or certificate).
4. **Guide screen by screen** — one at a time if the user is filling it in right now. Explain each «TAK/NIE» answer in terms of their situation; never default to «NIE».
5. **After submission**, give the dates (below) and offer reminders (see «Reminders»).

## Eligibility

Present it to the user in this shape (in their language, with actual years):

**Not eligible if:**
1. The business is not registered in CEIDG (e.g. a sp. z o.o.). Partners of a spółka cywilna and komornik sądowy are eligible.
2. 10 or more employees, or turnover (or balance sheet) over EUR 2M — not a mikroprzedsiębiorca.
3. Revenue over EUR 2M in **both** of the last 2 calendar years (no revenue at all is fine).
4. Works B2B for a former employer doing what they did under umowa o pracę (in the year business started or the year before) — checked for last year and this year until filing.
5. Already used wakacje składkowe this calendar year (last year's use doesn't block).

**May get in the way — check with an accountant:**
- shares in other companies (e.g. a sp. z o.o.);
- agriculture, food products or fishery.

**Then one question:** «Does any of this apply to you?» — nothing else at this stage.

De minimis (incl. previous wakacje od ZUS) is not asked here — it comes up on its own in step 4 «Oświadczenia».

## How much it saves (2026)

When the user asks how much they save, or once eligibility is confirmed, give these approximate monthly amounts (social contributions incl. dobrowolne chorobowe, plus Fundusz Pracy where due):

| ZUS variant | Saving for one month |
|---|---|
| Pełny ZUS (base 5652 zł) | ≈ 1926.76 zł |
| Preferencyjny ZUS (base 1441.80 zł, no FP) | ≈ 456.18 zł |
| Mały ZUS Plus | depends on the user's income-based base |
| Ulga na start | ≈ 0 zł — social contributions aren't paid anyway |

- Składka zdrowotna is **not** saved — it is still due.
- These are contributions, not taxes. Contributions are deductible, so the net gain is a bit lower; don't claim an exact net figure.
- Amounts change every year — for another year, say they need checking on zus.pl.

## Wizard screens (summary)

Step names as shown in the wizard's progress bar:

0. zus.pl → «Zaloguj się do eZUS» → «Katalog usług» → RWS → «Przejdź do usługi».
1. «Rodzaj wniosku»: «Wniosek» for a new application. «Uzupełnienie/korekta wniosku» — to supplement/correct one already sent (e.g. when ZUS asks). «Wycofanie wniosku» — to withdraw it.
2. «Dane płatnika» — prefilled, verify; phone number optional.
3. «Treść wniosku» — the month is prefilled (next month). Exempted: only the owner's own obowiązkowe ubezpieczenia społeczne, dobrowolne ubezpieczenie chorobowe, Fundusz Pracy and Fundusz Solidarnościowy. **Not składka zdrowotna, not employees' contributions.**
4. «Oświadczenia» — revenue, former employer, de minimis in the last 3 years. At the de minimis question, remind: previous wakacje od ZUS count as de minimis and must be declared (the ZUS video says so at 1:22).
5–8. «Informacje wymagane przy ubieganiu się o pomoc de minimis – część 1–4» — company size and main PKD (user doesn't know it → step-by-step from «How to find your PKD code» in `ezus-screens.md`), links to other companies, how the company was formed, sector.
9. «Załączniki» — only if certificates (zaświadczenia) were chosen in step 4.
10. Review → «Podpisz i wyślij».

Details of each screen — `ezus-screens.md`.

## After submission

- Response within **30 days**, in eZUS (messages/documents). Save the UPO.
- If ZUS has doubts, it sends a request to supplement the application («wezwanie do uzupełnienia») to eZUS. The user has **7 days** from receiving it; file the answer via the same wizard with «Rodzaj wniosku» → «Uzupełnienie/korekta wniosku».
  - Tell the user to check eZUS messages every 2–3 days until the 30-day response period ends, and to answer at once, not on the last day. Offer reminders (see «Reminders»).
  - Not verified (say so, don't guess as fact): what happens if the 7 days are missed (likely the application is left unprocessed — no exemption), and whether the 7 days count from opening the message or from its arrival in eZUS.
- Changed their mind — same wizard → «Wycofanie wniosku».
- No response by the deadline — contact ZUS before the contribution payment date for that month.
- Example: filed 21.10 → exemption for November, response by about 20.11.

## Reminders

After submission (or when a «wezwanie do uzupełnienia» arrives), **ask the user whether they want reminders** — one short question. If they say no, drop it. If yes, show the proposed events with dates and create them only after they confirm (they may change days or time).

**The reminder — one single event** (D = filing date):

- Title: «Sprawdź eZUS — czy ZUS coś przysłał (wakacje składkowe)» (in the user's language).
- When: D+7, 09:00, 15 min. Tied to the user's 7-day deadline: a request that arrived in the first week is still answerable. The user may pick another date.
- Description: Check eZUS messages — has ZUS sent a request to supplement the application («wezwanie do uzupełnienia»)? If yes — answer within 7 days of receiving it via «Rodzaj wniosku» → «Uzupełnienie/korekta wniosku». The final decision comes within 30 days of filing.

Don't mix up the two deadlines: **30 days** — ZUS has to decide; **7 days** — the user has to answer a ZUS request (only if one arrives).

Write titles in the user's language (the Polish ones above are an example); keep Polish UI names in the description. Use the user's time zone and a daytime slot (e.g. 09:00, 15 min).

**How:**
- A calendar tool is available (e.g. Google Calendar `create_event`) → show the list of events with dates, get a «yes», then create them and report what was created.
- No calendar tool → write an `.ics` file with the same events and tell the user to open it to import into their calendar; or just give the list of dates.
- Never invent the filing date — ask if it is unknown.

## Common mistakes

- Not declaring previous wakacje od ZUS as de minimis.
- Expecting the exemption for the current month.
- Not paying składka zdrowotna for the exempted month — health insurance is not covered and is still due. Same for contributions for employees.
- Filing a new «Wniosek» instead of «Uzupełnienie/korekta wniosku» when ZUS asks for corrections.
- Choosing anything other than «mikroprzedsiębiorca» — the exemption is for micro only.
- B2B for a former employer — not eligible.
- Attachment > 1 MB (5 MB total limit).
- Missing the 7-day correction deadline.

## Not covered by sources

The fields of the de minimis declaration («oświadczenie»), where last year's certificate is in eZUS — not verified. Do not make it up: say so and refer to zus.pl or an accountant. This is guidance, not legal advice.

---

# Wersja polska

[English](#wakacje-składkowe-rws-application-in-ezus) | **Polski**

## Przegląd

Pomagasz przedsiębiorcy sprawdzić, czy przysługuje mu ulga, przygotować dane i przejść przez kreator RWS w eZUS. **Nie możesz złożyć wniosku za użytkownika**: logowanie (Profil Zaufany / mObywatel / login i hasło) i podpis wykonuje wyłącznie użytkownik. Odpowiadaj w języku użytkownika; nazwy pól i przycisków zostawiaj po polsku, dokładnie tak jak w interfejsie.

Na początku powiedz użytkownikowi, że może obejrzeć oficjalny film ZUS z pełnym przykładem wypełnienia wniosku (po polsku, ok. 3 min): https://www.youtube.com/watch?v=AfuqKwYIvNI — i wspomnij, że ekrany w filmie mogą się nieco różnić od obecnego eZUS.

Źródła: poradnik wideo ZUS (`source-transcript.txt`) i prawdziwe ekrany eZUS (`ezus-screens.md` — treść pytań i jak na nie odpowiadać). Jeśli użytkownik przyśle zrzut ekranu, wyjaśniaj na jego podstawie; jeśli ekran różni się od tego skilla, ufaj ekranowi.

## Przebieg

1. **Sprawdź prawo do ulgi** — nie zadawaj listy pytań. Pokaż wykluczenia z sekcji «Prawo do ulgi» i zadaj jedno pytanie tak/nie: «Czy któraś z tych sytuacji dotyczy Ciebie?». «Nie» → ulga przysługuje, idź dalej. «Tak» → ustal, która, i powiedz wprost, co to oznacza. Pomiń punkty, na które użytkownik już odpowiedział.
2. **Wylicz miesiąc zwolnienia** — miesiąc następujący po miesiącu złożenia wniosku.
3. **Przygotuj dane**: główny kod PKD (gdzie go znaleźć — `ezus-screens.md`); pomoc de minimis z ostatnich 3 lat, w tym poprzednie wakacje od ZUS (data, kwota lub zaświadczenie).
4. **Prowadź ekran po ekranie** — po jednym, jeśli użytkownik wypełnia wniosek właśnie teraz. Wyjaśniaj każdą odpowiedź «TAK/NIE» w odniesieniu do jego sytuacji; nigdy nie zakładaj domyślnie «NIE».
5. **Po wysłaniu** podaj terminy (poniżej) i zaproponuj przypomnienia (zob. «Przypomnienia»).

## Prawo do ulgi

Przedstaw to użytkownikowi w takiej formie (w jego języku, z konkretnymi latami):

**Ulga nie przysługuje, jeśli:**
1. Działalność nie jest wpisana do CEIDG (np. sp. z o.o.). Wspólnicy spółki cywilnej i komornik sądowy mogą skorzystać.
2. 10 lub więcej pracowników albo obrót (lub suma bilansowa) powyżej 2 mln euro — to nie jest mikroprzedsiębiorca.
3. Przychód powyżej 2 mln euro w **obu** ostatnich 2 latach kalendarzowych (brak przychodu jest w porządku).
4. Praca na B2B dla byłego pracodawcy w zakresie tego, co robił na umowie o pracę (w roku rozpoczęcia działalności lub roku poprzednim) — sprawdzane za poprzedni rok i bieżący rok do dnia złożenia wniosku.
5. Wakacje składkowe zostały już wykorzystane w tym roku kalendarzowym (wykorzystanie w zeszłym roku nie przeszkadza).

**Może przeszkodzić — sprawdź z księgowym:**
- udziały w innych spółkach (np. sp. z o.o.);
- rolnictwo, produkty spożywcze lub rybołówstwo.

**Potem jedno pytanie:** «Czy któraś z tych sytuacji dotyczy Ciebie?» — nic więcej na tym etapie.

O de minimis (w tym poprzednie wakacje od ZUS) nie pytaj tutaj — pojawi się samo w kroku 4 «Oświadczenia».

## Ile można zaoszczędzić (2026)

Gdy użytkownik zapyta, ile zaoszczędzi, albo gdy prawo do ulgi zostanie potwierdzone, podaj te przybliżone kwoty miesięczne (składki społeczne łącznie z dobrowolnym chorobowym oraz Fundusz Pracy, jeśli jest należny):

| Wariant ZUS | Oszczędność za jeden miesiąc |
|---|---|
| Pełny ZUS (podstawa 5652 zł) | ≈ 1926,76 zł |
| Preferencyjny ZUS (podstawa 1441,80 zł, bez FP) | ≈ 456,18 zł |
| Mały ZUS Plus | zależy od podstawy wyliczonej z dochodu użytkownika |
| Ulga na start | ≈ 0 zł — składek społecznych i tak się nie płaci |

- Składki zdrowotnej **nie** oszczędzasz — nadal trzeba ją zapłacić.
- To składki, nie podatki. Składki można odliczyć, więc zysk netto jest nieco niższy; nie podawaj dokładnej kwoty netto.
- Kwoty zmieniają się co roku — dla innego roku powiedz, że trzeba je sprawdzić na zus.pl.

## Ekrany kreatora (podsumowanie)

Nazwy kroków tak, jak widać je na pasku postępu kreatora:

0. zus.pl → «Zaloguj się do eZUS» → «Katalog usług» → RWS → «Przejdź do usługi».
1. «Rodzaj wniosku»: «Wniosek» dla nowego wniosku. «Uzupełnienie/korekta wniosku» — aby uzupełnić/poprawić już wysłany wniosek (np. na wezwanie ZUS). «Wycofanie wniosku» — aby go wycofać.
2. «Dane płatnika» — wypełnione automatycznie, sprawdź; numer telefonu nieobowiązkowy.
3. «Treść wniosku» — miesiąc jest wypełniony automatycznie (następny miesiąc). Zwolnienie obejmuje tylko własne obowiązkowe ubezpieczenia społeczne właściciela, dobrowolne ubezpieczenie chorobowe, Fundusz Pracy i Fundusz Solidarnościowy. **Nie obejmuje składki zdrowotnej ani składek za pracowników.**
4. «Oświadczenia» — przychód, były pracodawca, de minimis w ostatnich 3 latach. Przy pytaniu o de minimis przypomnij: poprzednie wakacje od ZUS liczą się jako pomoc de minimis i trzeba je wykazać (mówi o tym film ZUS w 1:22).
5–8. «Informacje wymagane przy ubieganiu się o pomoc de minimis – część 1–4» — wielkość firmy i główny PKD (użytkownik go nie zna → instrukcja krok po kroku z sekcji «Jak znaleźć kod PKD» w `ezus-screens.md`), powiązania z innymi firmami, sposób powstania firmy, sektor.
9. «Załączniki» — tylko jeśli w kroku 4 wybrano zaświadczenia.
10. Przegląd → «Podpisz i wyślij».

Szczegóły każdego ekranu — `ezus-screens.md`.

## Po wysłaniu

- Odpowiedź w ciągu **30 dni**, w eZUS (wiadomości/dokumenty). Zachowaj UPO.
- Jeśli ZUS ma wątpliwości, wysyła do eZUS wezwanie do uzupełnienia wniosku («wezwanie do uzupełnienia»). Użytkownik ma **7 dni** od jego otrzymania; odpowiedź składa się przez ten sam kreator: «Rodzaj wniosku» → «Uzupełnienie/korekta wniosku».
  - Powiedz użytkownikowi, żeby sprawdzał wiadomości w eZUS co 2–3 dni do końca 30-dniowego terminu na odpowiedź i odpowiadał od razu, a nie w ostatnim dniu. Zaproponuj przypomnienia (zob. «Przypomnienia»).
  - Niesprawdzone (powiedz o tym, nie podawaj domysłów jako faktów): co się dzieje po przekroczeniu 7 dni (prawdopodobnie wniosek pozostaje nierozpatrzony — brak zwolnienia) i czy 7 dni liczy się od otwarcia wiadomości, czy od jej wpłynięcia do eZUS.
- Użytkownik się rozmyślił — ten sam kreator → «Wycofanie wniosku».
- Brak odpowiedzi w terminie — skontaktuj się z ZUS przed terminem płatności składek za ten miesiąc.
- Przykład: wniosek złożony 21.10 → zwolnienie za listopad, odpowiedź do ok. 20.11.

## Przypomnienia

Po wysłaniu wniosku (albo gdy przyjdzie «wezwanie do uzupełnienia») **zapytaj użytkownika, czy chce przypomnienia** — jedno krótkie pytanie. Jeśli odmówi, odpuść. Jeśli się zgodzi, pokaż proponowane wydarzenia z datami i utwórz je dopiero po potwierdzeniu (może zmienić dni lub godzinę).

**Przypomnienie — jedno wydarzenie** (D = data złożenia wniosku):

- Tytuł: «Sprawdź eZUS — czy ZUS coś przysłał (wakacje składkowe)» (w języku użytkownika).
- Kiedy: D+7, 09:00, 15 min. Powiązane z 7-dniowym terminem użytkownika: na wezwanie, które przyszło w pierwszym tygodniu, nadal można odpowiedzieć. Użytkownik może wybrać inną datę.
- Opis: Sprawdź wiadomości w eZUS — czy ZUS przysłał wezwanie do uzupełnienia wniosku («wezwanie do uzupełnienia»)? Jeśli tak — odpowiedz w ciągu 7 dni od jego otrzymania przez «Rodzaj wniosku» → «Uzupełnienie/korekta wniosku». Ostateczna decyzja przychodzi w ciągu 30 dni od złożenia wniosku.

Nie myl dwóch terminów: **30 dni** — ZUS musi wydać decyzję; **7 dni** — użytkownik musi odpowiedzieć na wezwanie ZUS (tylko jeśli takie przyjdzie).

Tytuły pisz w języku użytkownika (polskie powyżej to przykład); w opisie zostaw polskie nazwy z interfejsu. Używaj strefy czasowej użytkownika i pory dziennej (np. 09:00, 15 min).

**Jak:**
- Dostępne jest narzędzie kalendarza (np. Google Calendar `create_event`) → pokaż listę wydarzeń z datami, uzyskaj «tak», potem je utwórz i powiedz, co zostało utworzone.
- Brak narzędzia kalendarza → zapisz plik `.ics` z tymi samymi wydarzeniami i powiedz użytkownikowi, żeby go otworzył, aby zaimportować do kalendarza; albo po prostu podaj listę dat.
- Nigdy nie wymyślaj daty złożenia wniosku — zapytaj, jeśli jej nie znasz.

## Częste błędy

- Niewykazanie poprzednich wakacji od ZUS jako pomocy de minimis.
- Oczekiwanie zwolnienia za bieżący miesiąc.
- Niezapłacenie składki zdrowotnej za miesiąc zwolnienia — ubezpieczenie zdrowotne nie jest objęte zwolnieniem i nadal trzeba je zapłacić. To samo dotyczy składek za pracowników.
- Złożenie nowego «Wniosek» zamiast «Uzupełnienie/korekta wniosku», gdy ZUS prosi o poprawki.
- Wybranie czegokolwiek innego niż «mikroprzedsiębiorca» — zwolnienie jest tylko dla mikroprzedsiębiorców.
- B2B dla byłego pracodawcy — ulga nie przysługuje.
- Załącznik > 1 MB (łączny limit 5 MB).
- Przekroczenie 7-dniowego terminu na poprawki.

## Poza źródłami

Pola oświadczenia o pomocy de minimis («oświadczenie») i miejsce, gdzie w eZUS jest zaświadczenie z zeszłego roku — niesprawdzone. Nie wymyślaj: powiedz o tym i odeślij do zus.pl lub księgowego. To pomoc, a nie porada prawna.
