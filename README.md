# FUTURE_PE_03 — AI SEO Blog & Content Cluster Generator

**Track:** Prompt Engineering (PE) · **Task:** 3 · **Tool used:** Claude (Anthropic)

## Objective
Design a prompt system that generates SEO-optimized blog outlines, long-form posts, internal-link clusters, and local-SEO variants for business websites.

## Client Brief (sample client)
- **Business:** Maple & Main Café, Portland, OR (fictional placeholder)
- **Services:** Coffee, pastries, office catering, private events
- **Goal:** Rank for local searches; drive catering and event enquiries
- **Audience:** Portland locals, office managers, event planners

## Prompt Logic (5-step pipeline)
1. **Keyword & intent mapping:** Classify keywords as informational / commercial / local-transactional
2. **Cluster design:** 1 pillar page + 4 supporting posts, each targeting one primary keyword
3. **Outline prompt:** H1–H3 structure matching search intent, with FAQ block
4. **Draft prompt:** Long-form post following the outline; helpful first, promotional second
5. **Local SEO adaptation:** Swap in city + neighborhood signals, local landmarks, and service-area language

Quality rules baked into every prompt: answer the query in the first 100 words, one primary keyword (no stuffing), short paragraphs, real value before CTA, no invented stats.

## Files
- `prompts.md` — pipeline prompts + reusable template
- `outputs/keyword_cluster_map.md` — keywords, intent, cluster, internal links
- `outputs/blog_outlines.md` — H1–H3 outlines for all 5 posts
- `outputs/pillar_blog_post.md` — full long-form pillar post
- `outputs/local_seo_variant.md` — local adaptation example + checklist

## Learnings
- Mapping search intent first prevents writing the wrong kind of page.
- Clusters with deliberate internal links give structure to the whole site, not just single posts.
- Prompts must forbid fabricated statistics; verify any figure before publishing.
- Keyword volume/difficulty should be confirmed with a free tool (e.g., Google Keyword Planner) before finalizing targets.

*Content is AI-generated and human-reviewed. Business details are placeholders.*
