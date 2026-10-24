# RWS wizard screens in eZUS — texts and how to answer

**English** | [Polski](#wersja-polska)

> The same content is given twice: first in English, then in Polish. Both versions say the same thing.

Texts taken from real eZUS screens (October 2026). Step numbers as the user sees them in the wizard.

Wizard title: «Kreator wniosku o zwolnienie z obowiązku opłacenia składek za wskazany miesiąc – RWS (wakacje składkowe)».

Progress bar: 1 «Rodzaj wniosku» (name inferred) → 2 «Dane płatnika» → 3 «Treść wniosku» → 4 «Oświadczenia» → 5–8 «Informacje wymagane przy ubieganiu się o pomoc de minimis – część 1–4» → … («Załączniki», review).

## Step 1. Rodzaj wniosku

Info box at the top of the screen:

> «Zwolnienie z obowiązku opłacenia składek możesz otrzymać raz w roku za wybrany miesiąc. Wniosek zawsze składasz w miesiącu poprzedzającym miesiąc, o który wnioskujesz. Ulga dotyczy wyłącznie Twoich składek na:
> • obowiązkowe ubezpieczenia społeczne,
> • dobrowolne ubezpieczenie chorobowe,
> • Fundusz Pracy i Fundusz Solidarnościowy.»
>
> «Ze zwolnienia z opłacania składek możesz skorzystać, jeśli prowadzisz pozarolniczą działalność gospodarczą wpisaną do CEiDG, w tym jeśli jesteś wspólnikiem spółki cywilnej albo komornikiem sądowym.»
>
> «Z ulgi możesz skorzystać, jeśli spełnisz warunki wskazane w ustawie. Szczegóły znajdziesz w artykule "Zwolnienie z opłacania składek ZUS - wakacje składkowe" na stronie ZUS.»
>
> «We wniosku musisz też wypełnić blok dotyczący pomocy publicznej de minimis. Dlatego przygotuj: 1. dane o uzyskanej pomocy publicznej de minimis w okresie 3 minionych lat albo 2. zaświadczenia o uzyskanej pomocy.»

What it means:
- Once a year, for one month; always filed in the month **before** the exempted month.
- Only the owner's **own** contributions: mandatory social insurance, voluntary sickness insurance, FP and FS. Not składka zdrowotna, not employees' contributions.
- Who can apply: business registered in CEIDG, incl. partners of a spółka cywilna and court bailiffs (komornik sądowy).
- Have de minimis data (last 3 years) or certificates ready before starting.

«Rodzaj wniosku» options:

| Option | When |
|---|---|
| «Wniosek» | New application — the usual choice |
| «Uzupełnienie/korekta wniosku» | Supplementing or correcting an application already sent, e.g. when ZUS asks (7-day deadline) |
| «Wycofanie wniosku» | Withdrawing an application already sent |

## Step 3. Treść wniosku

> «Wnoszę o zwolnienie z obowiązku opłacenia składek na ubezpieczenia społeczne oraz Fundusz Pracy i Fundusz Solidarnościowy za miesiąc:»
> «Miesiąc: 04 Rok: 2026» (example — prefilled with the month after filing; nothing to choose)
> «Jeżeli nie masz obowiązku opłacenia składek na Fundusz Pracy i Fundusz Solidarnościowy za miesiąc, który wskazujesz we wniosku, rozpatrzymy Twój wniosek wyłącznie w zakresie zwolnienia z obowiązku opłacenia składek na ubezpieczenia społeczne.»

What it means:
- **Exempted:** the owner's own social insurance contributions (składki na ubezpieczenia społeczne — emerytalne, rentowe, wypadkowe, plus dobrowolne chorobowe if paid) plus Fundusz Pracy and Fundusz Solidarnościowy.
- If the user has no FP/FS obligation that month (e.g. low income or preferential contributions), only social insurance is exempted — that is normal, not an error.
- **Not exempted: składka zdrowotna** (health insurance) — it is not listed, so it must still be paid for that month.
- Just verify the month and click «dalej».

## Step 4. Oświadczenia

The user declares («Oświadczam, że»):

1. **Revenue.** «w ostatnich dwóch latach kalendarzowych poprzedzających rok złożenia wniosku nie osiągnąłem przychodu (...) lub w co najmniej jednym roku z dwóch ostatnich lat (...) osiągnąłem roczny przychód (...), który nie przekracza równowartości w złotych 2 milionów euro»
   - Satisfied if there was no revenue (new business) **or** revenue ≤ EUR 2M in at least one of the 2 years.
2. **Former employer.** «jako ubezpieczony w roku kalendarzowym poprzedzającym rok złożenia wniosku oraz od początku roku (...) nie wykonywałem pozarolniczej działalności gospodarczej na rzecz byłego pracodawcy, na rzecz którego w roku kalendarzowym rozpoczęcia działalności lub w poprzednim roku kalendarzowym wykonywałem w ramach stosunku pracy (...) czynności wchodzących w zakres wykonywanej działalności»
   - Not eligible example: worked as a programmer on umowa o pracę → opened a JDG → works for the same company on B2B.
3. **«W okresie minionych 3 lat:»** — whether de minimis aid was received. If yes, choose:
   - «oświadczenie»: add the entities that granted the aid (for "wakacje" — ZUS); no attachments needed;
   - certificates (zaświadczenia): upload them on the «Załączniki» screen.
   - Previous wakacje od ZUS are de minimis and must be declared. Look for their certificate among last year's documents in eZUS (exact location not verified).

## De minimis — część 1: company size and PKD

«Wielkość podmiotu, zgodnie z załącznikiem I do rozporządzenia Komisji (UE) nr 651/2014»: mikroprzedsiębiorca / mały / średni / inny.

- Choose **mikroprzedsiębiorca**: < 10 employees (in annual work units; the JDG owner usually does not count) and turnover or balance sheet ≤ EUR 2M. Other options — not eligible.
- Linked/partner enterprises may be aggregated under EU rules — if the user holds shares in other companies, check with an accountant.
- **Main PKD code** (likely on the same screen) — see «How to find your PKD code» below.

### How to find your PKD code

When the wizard asks for the main PKD code and the user doesn't know it, give these steps (one source is enough):

**A. CEIDG public search (fastest, no login)**
1. Open biznes.gov.pl → «Wyszukiwarka firm» (CEIDG company search).
2. Enter your **NIP** (or REGON, or name and surname) → search.
3. Open your company's entry.
4. Find the PKD section: the main code is marked «przeważający» (predominant) or listed first; the rest are additional codes.
5. Copy the main code into the wizard exactly as shown, e.g. `62.01.Z`.

**B. biznes.gov.pl account** — log in (Profil Zaufany / mObywatel) → your company's details → PKD codes.

**C. REGON registry** — wyszukiwarkaregon.stat.gov.pl → search by NIP → main PKD in the entry.

**D. Documents / accountant** — CEIDG entry printout (wydruk / zaświadczenie o wpisie), REGON certificate, or ask the accountant.

Notes:
- Enter **only the main** (przeważający) code, not the additional ones.
- Format is digits with a letter at the end, e.g. `62.01.Z`; keep the dots if the field accepts them.
- Both PKD 2007 and PKD 2025 classifications exist — enter the code currently shown in CEIDG. If the wizard rejects it, ask the user for the exact error and suggest checking with the accountant or ZUS.
- Site labels may change; if the user sends a screenshot, guide from it.

## De minimis — część 2: Powiązania z innymi przedsiębiorcami

«Czy pomiędzy podmiotem a innymi przedsiębiorcami istnieją powiązania polegające na tym, że:»

| | Meaning | «TAK» if |
|---|---|---|
| a | większość praw głosu akcjonariuszy lub wspólników | > 50% of votes in another company (or someone holds that in yours) |
| b | prawo wyznaczyć lub odwołać większość członków organu zarządzającego lub nadzorczego | control over the management/supervisory board |
| c | dominujący wpływ zgodnie z umową lub dokumentami założycielskimi | control via a contract or articles of association |
| d | samodzielna kontrola większości praw głosu na podstawie porozumienia | < 50%, but majority of votes by agreement with other shareholders |
| e | powyższe przez innego przedsiębiorcę lub kilku | any of the above through an intermediary |

Regular JDG with no shares in other companies → «NIE» everywhere. Co-owner of a sp. z o.o. (especially > 50% or on the board) → check with an accountant: may count as «jedno przedsiębiorstwo».

## De minimis — część 3: Informacje o powstaniu podmiotu

| | Question | «TAK» if |
|---|---|---|
| a | powstał wskutek połączenia się innych przedsiębiorców | company formed by a merger |
| b | przejął innego przedsiębiorcę | took over another company or part of it as a whole |
| c | powstał w wyniku podziału innego przedsiębiorcy | spun off from another company |
| d | powstał w wyniku przekształcenia przedsiębiorcy | converted from another legal form |

Simply registered a JDG in CEIDG → «NIE» everywhere. If «TAK» (usually b), the previous company's de minimis aid may count — refer to an accountant.

## De minimis — część 4: Działalność gospodarcza

«Czy podmiot prowadzi działalność gospodarczą:»

| | Sector | «TAK» if |
|---|---|---|
| a | produkcja podstawowa produktów rybołówstwa i akwakultury | catches/farms fish, shellfish |
| b | produkcja podstawowa produktów rolnych (załącznik I TFUE) | grows crops, raises livestock, beekeeping |
| c | przetwarzanie i wprowadzanie do obrotu produktów rolnych (załącznik I TFUE) | processes or sells agricultural products |
| d | przetwarzanie i wprowadzanie do obrotu produktów rybołówstwa i akwakultury | processes or sells fish products |

IT, services, consulting, construction, non-food trade → «NIE» everywhere. Food-related business → check with an accountant (the załącznik I list is broad).

## Załączniki

- Needed only if certificates de minimis were chosen in step 4. Otherwise leave empty → «dalej».
- Formats: .doc, .docx, .gif, .jpg, .jpeg, .ods, .odt, .pades, .pdf, .png, .rar, .rtf, .svg, .tif, .tiff, .txt, .xades, .xls, .xlsx, .xml, .zip. PDF preferred.
- Limits: **1 MB per file, 5 MB total**. Compress heavy scans.

## Next

Review the whole application → «Podpisz i wyślij» → submission confirmation (UPO) in eZUS.

---

# Wersja polska

[English](#rws-wizard-screens-in-ezus--texts-and-how-to-answer) | **Polski**

# Ekrany kreatora RWS w eZUS — teksty i jak odpowiadać

Teksty pochodzą z prawdziwych ekranów eZUS (październik 2026). Numery kroków tak, jak widzi je użytkownik w kreatorze.

Tytuł kreatora: «Kreator wniosku o zwolnienie z obowiązku opłacenia składek za wskazany miesiąc – RWS (wakacje składkowe)».

Pasek postępu: 1 «Rodzaj wniosku» (nazwa przypuszczalna) → 2 «Dane płatnika» → 3 «Treść wniosku» → 4 «Oświadczenia» → 5–8 «Informacje wymagane przy ubieganiu się o pomoc de minimis – część 1–4» → … («Załączniki», przegląd).

## Krok 1. Rodzaj wniosku

Ramka informacyjna u góry ekranu:

> «Zwolnienie z obowiązku opłacenia składek możesz otrzymać raz w roku za wybrany miesiąc. Wniosek zawsze składasz w miesiącu poprzedzającym miesiąc, o który wnioskujesz. Ulga dotyczy wyłącznie Twoich składek na:
> • obowiązkowe ubezpieczenia społeczne,
> • dobrowolne ubezpieczenie chorobowe,
> • Fundusz Pracy i Fundusz Solidarnościowy.»
>
> «Ze zwolnienia z opłacania składek możesz skorzystać, jeśli prowadzisz pozarolniczą działalność gospodarczą wpisaną do CEiDG, w tym jeśli jesteś wspólnikiem spółki cywilnej albo komornikiem sądowym.»
>
> «Z ulgi możesz skorzystać, jeśli spełnisz warunki wskazane w ustawie. Szczegóły znajdziesz w artykule "Zwolnienie z opłacania składek ZUS - wakacje składkowe" na stronie ZUS.»
>
> «We wniosku musisz też wypełnić blok dotyczący pomocy publicznej de minimis. Dlatego przygotuj: 1. dane o uzyskanej pomocy publicznej de minimis w okresie 3 minionych lat albo 2. zaświadczenia o uzyskanej pomocy.»

Co to oznacza:
- Raz w roku, za jeden miesiąc; wniosek zawsze składa się w miesiącu **poprzedzającym** miesiąc zwolnienia.
- Tylko **własne** składki właściciela: obowiązkowe ubezpieczenia społeczne, dobrowolne ubezpieczenie chorobowe, FP i FS. Nie składka zdrowotna, nie składki za pracowników.
- Kto może złożyć wniosek: działalność wpisana do CEIDG, w tym wspólnicy spółki cywilnej i komornicy sądowi.
- Przed rozpoczęciem przygotuj dane o pomocy de minimis (ostatnie 3 lata) albo zaświadczenia.

Opcje «Rodzaj wniosku»:

| Opcja | Kiedy |
|---|---|
| «Wniosek» | Nowy wniosek — zwykły wybór |
| «Uzupełnienie/korekta wniosku» | Uzupełnienie lub poprawienie już wysłanego wniosku, np. na wezwanie ZUS (termin 7 dni) |
| «Wycofanie wniosku» | Wycofanie już wysłanego wniosku |

## Krok 3. Treść wniosku

> «Wnoszę o zwolnienie z obowiązku opłacenia składek na ubezpieczenia społeczne oraz Fundusz Pracy i Fundusz Solidarnościowy za miesiąc:»
> «Miesiąc: 04 Rok: 2026» (przykład — wypełnione automatycznie miesiącem po złożeniu wniosku; nie ma nic do wyboru)
> «Jeżeli nie masz obowiązku opłacenia składek na Fundusz Pracy i Fundusz Solidarnościowy za miesiąc, który wskazujesz we wniosku, rozpatrzymy Twój wniosek wyłącznie w zakresie zwolnienia z obowiązku opłacenia składek na ubezpieczenia społeczne.»

Co to oznacza:
- **Zwolnione:** własne składki właściciela na ubezpieczenia społeczne (emerytalne, rentowe, wypadkowe oraz dobrowolne chorobowe, jeśli jest opłacane) plus Fundusz Pracy i Fundusz Solidarnościowy.
- Jeśli w danym miesiącu użytkownik nie ma obowiązku opłacania FP/FS (np. niski dochód lub składki preferencyjne), zwolnione są tylko ubezpieczenia społeczne — to normalne, a nie błąd.
- **Niezwolniona: składka zdrowotna** — nie ma jej na liście, więc za ten miesiąc nadal trzeba ją zapłacić.
- Wystarczy sprawdzić miesiąc i kliknąć «dalej».

## Krok 4. Oświadczenia

Użytkownik oświadcza («Oświadczam, że»):

1. **Przychód.** «w ostatnich dwóch latach kalendarzowych poprzedzających rok złożenia wniosku nie osiągnąłem przychodu (...) lub w co najmniej jednym roku z dwóch ostatnich lat (...) osiągnąłem roczny przychód (...), który nie przekracza równowartości w złotych 2 milionów euro»
   - Warunek spełniony, jeśli nie było przychodu (nowa działalność) **albo** przychód ≤ 2 mln euro w co najmniej jednym z 2 lat.
2. **Były pracodawca.** «jako ubezpieczony w roku kalendarzowym poprzedzającym rok złożenia wniosku oraz od początku roku (...) nie wykonywałem pozarolniczej działalności gospodarczej na rzecz byłego pracodawcy, na rzecz którego w roku kalendarzowym rozpoczęcia działalności lub w poprzednim roku kalendarzowym wykonywałem w ramach stosunku pracy (...) czynności wchodzących w zakres wykonywanej działalności»
   - Przykład braku prawa do ulgi: praca jako programista na umowie o pracę → założenie JDG → praca dla tej samej firmy na B2B.
3. **«W okresie minionych 3 lat:»** — czy uzyskano pomoc de minimis. Jeśli tak, wybierz:
   - «oświadczenie»: dodaj podmioty, które udzieliły pomocy (dla „wakacji” — ZUS); załączniki nie są potrzebne;
   - zaświadczenia: dołącz je na ekranie «Załączniki».
   - Poprzednie wakacje od ZUS to pomoc de minimis i trzeba je wykazać. Zaświadczenia szukaj wśród zeszłorocznych dokumentów w eZUS (dokładne miejsce niesprawdzone).

## De minimis — część 1: wielkość firmy i PKD

«Wielkość podmiotu, zgodnie z załącznikiem I do rozporządzenia Komisji (UE) nr 651/2014»: mikroprzedsiębiorca / mały / średni / inny.

- Wybierz **mikroprzedsiębiorca**: < 10 pracowników (w rocznych jednostkach pracy; właściciel JDG zwykle się nie wlicza) i obrót lub suma bilansowa ≤ 2 mln euro. Pozostałe opcje — brak prawa do ulgi.
- Przedsiębiorstwa powiązane/partnerskie mogą być sumowane według przepisów UE — jeśli użytkownik ma udziały w innych spółkach, niech sprawdzi to z księgowym.
- **Główny kod PKD** (prawdopodobnie na tym samym ekranie) — zob. «Jak znaleźć kod PKD» poniżej.

### Jak znaleźć kod PKD

Gdy kreator pyta o główny kod PKD, a użytkownik go nie zna, podaj te kroki (wystarczy jedno źródło):

**A. Publiczna wyszukiwarka CEIDG (najszybciej, bez logowania)**
1. Otwórz biznes.gov.pl → «Wyszukiwarka firm» (wyszukiwarka CEIDG).
2. Wpisz swój **NIP** (albo REGON, albo imię i nazwisko) → szukaj.
3. Otwórz wpis swojej firmy.
4. Znajdź sekcję PKD: główny kod jest oznaczony jako «przeważający» albo podany jako pierwszy; pozostałe to kody dodatkowe.
5. Przepisz główny kod do kreatora dokładnie tak, jak jest pokazany, np. `62.01.Z`.

**B. Konto na biznes.gov.pl** — zaloguj się (Profil Zaufany / mObywatel) → dane Twojej firmy → kody PKD.

**C. Rejestr REGON** — wyszukiwarkaregon.stat.gov.pl → szukaj po NIP → główny PKD we wpisie.

**D. Dokumenty / księgowy** — wydruk wpisu z CEIDG (wydruk / zaświadczenie o wpisie), zaświadczenie o numerze REGON albo zapytaj księgowego.

Uwagi:
- Wpisz **tylko główny** (przeważający) kod, bez dodatkowych.
- Format to cyfry z literą na końcu, np. `62.01.Z`; zostaw kropki, jeśli pole je przyjmuje.
- Istnieją dwie klasyfikacje: PKD 2007 i PKD 2025 — wpisz kod, który jest obecnie widoczny w CEIDG. Jeśli kreator go odrzuci, poproś użytkownika o dokładną treść błędu i zaproponuj kontakt z księgowym lub ZUS.
- Nazwy na stronach mogą się zmieniać; jeśli użytkownik przyśle zrzut ekranu, prowadź na jego podstawie.

## De minimis — część 2: Powiązania z innymi przedsiębiorcami

«Czy pomiędzy podmiotem a innymi przedsiębiorcami istnieją powiązania polegające na tym, że:»

| | Znaczenie | «TAK», jeśli |
|---|---|---|
| a | większość praw głosu akcjonariuszy lub wspólników | > 50% głosów w innej spółce (lub ktoś ma tyle w Twojej) |
| b | prawo wyznaczyć lub odwołać większość członków organu zarządzającego lub nadzorczego | kontrola nad zarządem/radą nadzorczą |
| c | dominujący wpływ zgodnie z umową lub dokumentami założycielskimi | kontrola na podstawie umowy lub umowy spółki/statutu |
| d | samodzielna kontrola większości praw głosu na podstawie porozumienia | < 50%, ale większość głosów dzięki porozumieniu z innymi wspólnikami |
| e | powyższe przez innego przedsiębiorcę lub kilku | którakolwiek z powyższych sytuacji przez pośrednika |

Zwykła JDG bez udziałów w innych spółkach → wszędzie «NIE». Współwłaściciel sp. z o.o. (zwłaszcza > 50% lub w zarządzie) → sprawdź z księgowym: może to być traktowane jako «jedno przedsiębiorstwo».

## De minimis — część 3: Informacje o powstaniu podmiotu

| | Pytanie | «TAK», jeśli |
|---|---|---|
| a | powstał wskutek połączenia się innych przedsiębiorców | firma powstała z połączenia |
| b | przejął innego przedsiębiorcę | przejęła inną firmę lub jej część w całości |
| c | powstał w wyniku podziału innego przedsiębiorcy | wydzieliła się z innej firmy |
| d | powstał w wyniku przekształcenia przedsiębiorcy | przekształciła się z innej formy prawnej |

Po prostu zarejestrowana JDG w CEIDG → wszędzie «NIE». Jeśli «TAK» (zwykle b), pomoc de minimis poprzedniej firmy może się wliczać — odeślij do księgowego.

## De minimis — część 4: Działalność gospodarcza

«Czy podmiot prowadzi działalność gospodarczą:»

| | Sektor | «TAK», jeśli |
|---|---|---|
| a | produkcja podstawowa produktów rybołówstwa i akwakultury | łowi/hoduje ryby, skorupiaki |
| b | produkcja podstawowa produktów rolnych (załącznik I TFUE) | uprawia rośliny, hoduje zwierzęta, prowadzi pasiekę |
| c | przetwarzanie i wprowadzanie do obrotu produktów rolnych (załącznik I TFUE) | przetwarza lub sprzedaje produkty rolne |
| d | przetwarzanie i wprowadzanie do obrotu produktów rybołówstwa i akwakultury | przetwarza lub sprzedaje produkty rybne |

IT, usługi, doradztwo, budownictwo, handel niespożywczy → wszędzie «NIE». Działalność związana z żywnością → sprawdź z księgowym (lista z załącznika I jest szeroka).

## Załączniki

- Potrzebne tylko wtedy, gdy w kroku 4 wybrano zaświadczenia de minimis. W przeciwnym razie zostaw puste → «dalej».
- Formaty: .doc, .docx, .gif, .jpg, .jpeg, .ods, .odt, .pades, .pdf, .png, .rar, .rtf, .svg, .tif, .tiff, .txt, .xades, .xls, .xlsx, .xml, .zip. Najlepiej PDF.
- Limity: **1 MB na plik, 5 MB łącznie**. Ciężkie skany skompresuj.

## Dalej

Przejrzyj cały wniosek → «Podpisz i wyślij» → potwierdzenie wysłania (UPO) w eZUS.
