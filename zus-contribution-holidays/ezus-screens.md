# RWS wizard screens in eZUS — texts and how to answer

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
