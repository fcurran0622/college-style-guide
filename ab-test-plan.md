# A/B Test Plan — The College Edit

**Website:** https://fcurran0622.github.io/college-style-guide/  
**Page:** Homepage (`index.html`)  
**Plan date:** November 8, 2026

## 1. Page and single change
I will test the main Game Day button text on my homepage. **Version A (current):** “Explore game day looks.” **Version B:** “Find Your Game Day Outfit.” Both buttons lead to the same page; all other content and design remain identical.

## 2. Hypothesis and reasoning
I predict **Version B will receive more YES responses** because its wording feels more personal and action-oriented. This could be wrong if visitors prefer the original wording.

## 3. AI visitors, exact prompt, and assignment
**Model:** GPT-6 (same settings throughout). **Persona:** College student seeking affordable game-day outfits. Each trial uses a fresh, memory-free conversation. Before testing, I will save a shuffled list of 50 A and 50 B assignments. I will show the full homepage text, changing only the assigned button wording.

**Exact prompt template (replace only the bracketed page content):**
> You are a college student looking for cute, affordable outfit ideas for a college football game. Read the homepage below. Would you click its main Game Day button to see more outfit ideas? Answer YES or NO, followed by one sentence explaining why.  
>  
> Homepage:  
> [FULL HOMEPAGE TEXT FOR THE RANDOMLY ASSIGNED VERSION]

## 4. One primary outcome
**Primary outcome:** AI visitor click intention (YES = 1, NO = 0), measured as the YES percentage per version; this is not actual click behavior.

## 5. Sample size and stopping date
**100 trials: 50 per version.** Launch by **November 17, 2026**; finish by **November 24, 2026**. Record every result and do not stop early.

## 6. Comparison and support for the hypothesis
Compare **B YES% − A YES%**, using a two-proportion test for chance variation. A higher B rate supports the predicted direction; p < 0.05 would provide stronger statistical evidence. Report uncertain results honestly.

**SEO:** If published separately, Version B will have `noindex` and stay out of `sitemap.xml`.
