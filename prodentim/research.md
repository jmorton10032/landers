# Research: Oral Probiotic (ProDentim, ClickBank)

## 1. Offer check
- **Slug:** `prodentim`
- **Offer:** ProDentim, a chewable oral probiotic dietary supplement sold through ClickBank
  (hoplink `https://prodentim101.com/text.php?hop=jmodigital&hopId=...`, the vendor's text presell).
- **Vertical:** Health, dietary supplement. Health guardrails apply: no cure, treatment or before/after
  claims; no Fear angle; FDA supplement disclaimer and "not medical advice" line on every page.
- **Offer type:** direct product sale (CPS). ClickBank pays a commission on the sale.
- **What could and couldn't be checked:** this cloud session's network blocks `prodentim101.com`, so the
  vendor page itself wasn't read. Third-party listings consistently describe a chewable tablet with
  several probiotic strains (Lactobacillus paracasei and L. reuteri named most often, ~3.5 billion CFU
  claimed), one bottle around $69 with multi-bottle discounts, and a 60-day money-back guarantee through
  ClickBank, but they disagree on details. **None of those numbers are used on the pages.** The pages
  mention only that the maker lists a money-back guarantee, and send people to the official page for
  the terms. Open the hoplink yourself before spending and make sure the presell doesn't contradict
  the bridge pages.
- **EPC / gravity:** not checked. Look it up in the ClickBank marketplace before spending.
- **Affiliate link:** real hoplink on every CTA, with `&tid=<angle>` so ClickBank reports split by page.
- **Traffic:** Facebook + Native (Taboola / Outbrain), the CLAUDE.md default.
- **Test budget:** $50 split across the 3 angles (~$16.67 each), one ad set per angle.

### Policy check
- **Meta:** dietary supplements are allowed but restricted. Ads must not assert or imply a personal
  attribute or health condition ("Your bad breath...", "Struggling with gum problems?"). Target 18+.
  No before/after, no unrealistic claims. Meta's health and wellness data limits can reduce pixel
  events on health pages; optimize on clicks / landing page views if conversions are thin. The
  copy describes situations and the category, never the viewer.
- **Taboola / Outbrain:** supplements allowed; claims must stay at the symptom/benefit level, never a
  disease; health products can need manual review. Advertorial label "Advertisement · Advertorial" is
  at the top of every page.
- **ClickBank:** check the vendor's affiliate page for traffic restrictions (some vendors ban paid
  social or specific claims) before launching.

## 2. Avatar
1. **Who:** US adults, roughly 35–65, who already take care of their teeth (brush twice a day, use
   mouthwash, carry gum or mints) yet still feel self-conscious up close: in meetings, on dates, talking
   to customers. Many already take a gut probiotic or other supplements and are open to "natural" add-ons.
   Daily frustration: the clean feeling doesn't last, and they second-guess their breath in close
   conversations.
2. **Top 10 pain points:**
   1. The minty feeling fades within hours.
   2. Checking breath (hand cupped, asking a partner) before meetings or dates.
   3. Leaning back or turning away in close conversations.
   4. Smiling with the mouth closed; talking less.
   5. Spending on gum, mints and mouthwash that only mask.
   6. Feeling they do everything right and it still isn't enough.
   7. Gums that feel tender or look irritated after brushing (described as a feeling, never diagnosed).
   8. Anxiety before dental checkups and the cost of dental work.
   9. Strong mouthwash that burns and dries the mouth.
   10. Skepticism: "Supplements for teeth? Is that even a thing?" (main objection).
3. **Already tried:** whitening toothpaste, alcohol-based mouthwash, tongue scrapers, water flossers,
   gum and mints, more frequent brushing.
4. **What makes them click now:** a recent awkward moment, an upcoming event (date, interview,
   presentation), or the novelty of "probiotics for your mouth" after already buying into gut probiotics.
5. **Where they are online:** Facebook (health and wellness groups, natural living), Instagram
   wellness content, news and lifestyle sites that carry Taboola / Outbrain feeds, YouTube.

**Market context (planning only, not used as claims on the pages):**
- Halitosis is common: a 2018 systematic review of population studies estimated pooled prevalence
  around 32% (Silva et al., meta-regression).
- Evidence for oral probiotics is real but mixed: a 2020 meta-analysis of 10 RCTs on gingivitis found
  benefits in every trial but rated the overall evidence weak; L. reuteri alone was not significantly
  better than placebo on gingival or plaque index. So the pages make no efficacy claims of their own,
  say the research "is still developing", and attribute the product's purpose to its maker.
- The mouth hosts hundreds of bacterial species (the oral microbiome); this general fact is the only
  science statement on the pages.
- The ProDentim search landscape is crowded with spammy "review" pages, so an honest, low-hype
  advertorial stands out and survives network review better.

## 3. Angle scores (Facebook + Native, Health)
| Angle | Score | Why |
| --- | --- | --- |
| Pain Point | 5 | "I brush twice a day and still check my breath" is a universal, quietly felt frustration. Works as a story without naming any condition. |
| Curiosity | 5 | "Your mouth has a microbiome; mouthwash doesn't pick sides" is a true, surprising idea, and the probiotic is the natural answer. Ideal for native feeds. |
| Direct Benefit | 4 | "One chew a day after brushing" is a clear, easy end state. Kept to lifestyle and the maker's stated purpose, since health rules bar result claims. |
| Social Proof | 2 | No offer-owner numbers could be verified (vendor page blocked), and public "reviews" are mostly affiliate spam. No proof → skip. |
| Fear | 1 | Barred in Health by the guardrails (ad networks restrict health fear appeals). |

**Picked:** Pain Point (5), Curiosity (5), Direct Benefit (4).

**Skipped:**
- **Social Proof:** no verifiable proof. Revisit if the vendor's affiliate page publishes customer numbers.
- **Fear:** not allowed for Health in CLAUDE.md.

## 4. Formats
Health supplements and Native traffic both point to the Advertorial; Facebook is cold traffic that
needs the story to warm up, and the Quiz format isn't built for supplement sales (no qualifying
questions, no location). One format for all 3 pages, so the test isolates the angle.

| Page | Angle | Format | Why |
| --- | --- | --- | --- |
| `pain.html` | Pain Point | Advertorial | Pain reads best as a second-person story ("In the car, you cup a hand..."). |
| `curiosity.html` | Curiosity | Advertorial | The microbiome idea needs a few paragraphs to open and close the loop; matches native's article context. |
| `benefit.html` | Direct Benefit | Advertorial | Direct is for search intent; on Facebook / native the benefit lands better as a short story of the "after". |

## 5. Creative
- **Publisher:** "Everyday Smile Notes" (generic, `img/logo.svg`, brand color #1b6f8a).
- **Accents:** pain #9b3b5a (berry), curiosity #5b45c2 (violet), benefit #0e7a5f (green).
- **Images:** not generated. The Higgsfield connector in this session is read-only. The spots show a
  tinted block. Image rules for later: no bodies in focus, no pills or product shots, no before/after,
  no teeth close-ups that read as results.

## Sources
- Halitosis prevalence meta-regression: https://pubmed.ncbi.nlm.nih.gov/28676903/
- Probiotics for gingivitis, systematic review: https://www.scielo.br/j/bor/a/3vjhpNjmR4c4pKdbmprkLyC/?lang=en
- Probiotics for gingivitis (Mental Elf summary): https://nationalelfservice.net/dentistry/periodontal-disease/probiotics-treatment-gingivitis
- Taboola health supplement guidelines: https://www.taboola.com//wp-content/uploads/2022/11/health-supplement-advertising-guidelines.pdf
- Taboola health and beauty policy FAQ: https://help-center.taboola.com/en/articles/7199777-policy-faq-health-beauty
- Social health ad restrictions 2026: https://www.accelerateddigitalmedia.com/insights/guide-to-social-media-health-ad-restrictions-2026/
- Meta health and wellness policy update 2026: https://adligator.com/blog/meta-health-wellness-ad-policy-update-2026
- Product listings (price / guarantee, inconsistent, not used on pages): https://go-prodentim.com/index.html, https://prodentimchews.com/
