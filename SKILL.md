---
name: copywriting
description: Write or edit marketing copy, headlines and CTAs. Preserve supplied facts and voice; keep point edits within scope.
metadata:
  version: 2.3.2
---

# Copywriting

For controls, errors and onboarding inside an interface, use `ux-copy`.

1. Read existing project context if present: `.agents/product-marketing.md`, `.claude/product-marketing.md`, or their legacy `product-marketing-context.md`. Apply relevant Learnings. Do not create context just to answer a copy request.
2. Identify the requested unit, audience, offer and action. Reuse supplied facts. Ask only if missing information materially changes the result; otherwise mark a needed fact as `[NEED: ...]`.
3. Choose scope:
   - **Point edit:** change only the named headline, CTA or paragraph. Preserve surrounding text.
   - **Existing voice:** preserve angle, vocabulary and emphasis; fix clarity and flow.
   - **New page:** build the argument from the brief; draft by section, then read the assembled page.
4. Use concrete, supportable claims. Do not invent metrics, testimonials, capabilities, free trials or plan entitlements. Keep prices, offers, guarantees, links and qualifiers unless a change is requested. Preserve the user's established prices; never add unrequested discounts.
5. Return usable copy first. A point edit normally needs only the replacement text. Add alternatives, rationale or SEO fields only when requested or useful. Revert changes that are merely different. Check the CTA matches its real destination and every factual claim has evidence or a visible gap.

Read only what the task needs:
- Full page: [style and page guidance](references/style-and-page-guidance.md).
- Headlines/argument: [copy frameworks](references/copy-frameworks.md).
- Repetitive AI wording: [AI tells](references/ai-tells.md).
- Long-copy flow: [transitions](references/natural-transitions.md).

Reference examples are not facts about this product. Named upstream skills are optional only if available; missing ones do not block the draft.
