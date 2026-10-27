# Methodology

**Status: proposed procedure; data collection has not begun.**

## 1. Define the sample

The workbook contains 20 suggested searches and three planned result slots per query. Confirm or change the queries before collection. The positions 1, 2 and 3 refer to the ordinary organic webpage results selected under the rule below; they are not observations until the search is performed.

For the first session, use only Q01: `how to take a screenshot on a Mac`.

## 2. Collect results consistently

1. Use the same search engine, desktop browser and language throughout. A signed-out private window reduces some personalisation but does not remove location effects.
2. Use Raleigh, North Carolina as the intended location for local queries. Record the engine, browser, signed-in/private status, intended location and any different location displayed by the engine in **Search context**. Do not record a home address.
3. Record the actual observation date as YYYY-MM-DD. If revisiting later changes the evidence, record that date in your notes.
4. Before opening results, write the likely **User intent** in one sentence. Mention meaningful ambiguity rather than assuming one interpretation is certain.
5. Select the first three ordinary non-sponsored webpage links in displayed order. Exclude ads, AI-generated answer panels, map packs, shopping carousels, video carousels and expandable question boxes. Do not count sitelinks beneath one result as separate results. This project assesses webpages, not the whole results-page experience.
6. Open each selected page. Record its URL and title. Do not rate from its search snippet alone.
7. If fewer than three eligible links are available, record that limitation. If a selected page is blocked, paywalled or unavailable, retain its position and URL, mark it **Blocked**, explain the issue and leave the scores blank. Do not silently replace it with a better result.

## 3. Apply the custom rubric

Use whole numbers. The total is the sum of four dimensions and remains blank until all four are entered. A numerical total does not mean an evaluation is complete: the URL, date, intent, rationale and evidence must also be present.

| Criterion | Score definitions |
| --- | --- |
| Intent match, 0–3 | **0:** Does not address the need. **1:** Related but misses the main need. **2:** Addresses most of the need with a meaningful gap. **3:** Directly addresses the intended task or question. |
| Credibility and evidence, 0–3 | **0:** No usable basis for trusting the relevant claims, or material deception. **1:** Weak authorship, sourcing or supporting evidence. **2:** Relevant expertise or evidence with a material limitation. **3:** Clear relevant expertise and strong, traceable support appropriate to the query. |
| Accuracy and freshness, 0–2 | **0:** Materially incorrect or outdated in a way that undermines the answer. **1:** Partially supported or mixed, with unresolved uncertainty explicitly recorded. **2:** Key relevant claims checked and supported; currency is appropriate to the query. |
| Usefulness and clarity, 0–2 | **0:** Content cannot usefully answer the need despite access. **1:** Usable with significant omissions, clutter or unclear steps. **2:** Clear, sufficiently complete and practical for the intended user. |

Credibility is topic-specific: a shop is a primary source for its own opening hours, but its claim to sell the best product needs separate scrutiny. An official domain alone is not proof of relevance or correctness. Old content is not automatically stale if the information remains valid.

## 4. Document evidence

For every accessible result:

- Enter all four scores and a two- or three-sentence **Rating justification** that explains the main strengths and deductions using the rubric.
- In **Verification evidence / limits**, give the supporting source URL, the particular claim checked, and any uncertainty. For technical guidance, use relevant manufacturer documentation where available. For dates, hours and admission, check the responsible organisation. For shopping claims, distinguish specifications from opinions and promotional claims.
- If accuracy remains uncertain, describe the uncertainty; do not present it as a verified falsehood. If the page cannot be assessed at all, mark it Blocked and leave scores empty.
- Set **Status** to Complete only when the required fields are filled and the justification supports the scores. The status is manually selected, not an automatic quality check.

Write your own concise notes. Link to webpages rather than copying whole articles. Do not include personal customer information or confidential employer assessment materials.

## 5. Pilot and consistency review

Complete Q01 first. Review whether the rubric explains your decisions clearly. If you change its definitions, record the change and revisit earlier ratings under the revised version.

After collection, select the first five accessible assessed results in dataset order. On a later pass, re-rate them without looking at your earlier scores. In the findings report record the query ID, position, original and revised scores, and why they differ. This is a self-consistency check, not independent reviewer agreement.

## 6. Finish and report honestly

Report the actual number of queries searched, accessible pages assessed, blocked pages and uncompleted slots. Base findings on identified rows such as Q01 / position 2. Avoid broad claims about all search results or an employer's grading standards.

Use **ratings.xlsx** as the working copy. The pale input cells are editable; the Total column is calculated. In Excel or Numbers, save/export an updated Excel copy if needed, then export the Ratings sheet as **ratings.csv**. CSV is a values-only snapshot; do not use it as a substitute for the working workbook. Replace both files on GitHub after a session.

