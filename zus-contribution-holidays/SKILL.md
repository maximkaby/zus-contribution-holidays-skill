---
name: zus-contribution-holidays
description: Use when a Polish entrepreneur (JDG, mikroprzedsiębiorca) asks about "wakacje składkowe", "wakacje od ZUS", the RWS application (wniosek o zwolnienie z obowiązku opłacania składek za wskazany miesiąc), eligibility for a one-month ZUS contribution exemption, de minimis questions in that form, or how to file it in eZUS / PUE ZUS — in any language (Polish, Russian, Ukrainian, English).
---

# Wakacje składkowe (RWS application in eZUS)

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
