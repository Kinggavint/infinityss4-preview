# Client intake checklist: Infinity Susanna Smiles

| Item | Value / source | Status |
|---|---|---|
| Latest support inbox email checked | Oct 29 2026 10:25 AM MDT, kcpoletis@gmail.com (Karen) to support@apexailabs.ai, thread 1a16f8f63021bdcc "Re: Your new website preview + a few last items". Earlier: Oct 18 threads 1a140ae4439f734b and 1a142188ae8d25bc | Checked; Oct 29 edits applied (see Edit log) |
| Logo source files | Heart is a redraw, original file not received | Open |
| Photos | Drive folder "Infinity - Susanna Smiles": Logos, ISS Photos, Susanna pictures, Videos only | OK |
| Form backend and links | Application: live site Airtable embed https://airtable.com/embed/appUeSDPPprjxv4yr/shrNsB19K4T88i7gc?backgroundColor=orange now on get-support.html. Live donate page also embeds a volunteer Airtable form (appkk7gxHZ7S4GFH7/shrL9eEGbo92v9rZe); contact, volunteer and newsletter forms on the preview are still placeholders | Application applied; others open |
| Social URLs | Instagram added; Facebook and LinkedIn URLs not received | Open |
| Donation / payment links | Client chose PayPal over Givebutter (Oct 29). No PayPal URL found on the live site, the Oct 29 backup or any email; donate button is a marked placeholder. Dance to Infinity event "Learn More" links still go to the Givebutter event page | Open: need PayPal link |
| Legal / payee name | "Infinity - Susanna Smiles" (spaced hyphen) on every page, per Karen Oct 29 | Applied |
| NAP | Zip 64081 per Oct 18 email | Applied |
| Current hosting end date | Nov 4 2026 (per Mike, Oct 21 meeting) | Deadline |
| Domain and registrar owner | GoDaddy, client account (credentials not stored here) | Website Deployment / Domain Specialist |
| Restricted sources | Do not use receipts, applications, tax, NDA, minutes or database files | Enforced |

## Open items
- Facebook URL, LinkedIn URL
- Airtable links for contact, volunteer and newsletter forms (application done)
- PayPal donation link (client chose PayPal over Givebutter Oct 29)
- Old announcements, newsletters, 4 videos
- Original heart logo file
- Newsletter section (proposed, not built)
- Photos and older flyers for News & Events: Karen wants a call; untouched
- Video: Karen asked to drop the last of her 4 videos; it appears to be the live Announcements mp4 (susannah-smiles-fundraising-vid-1-1-1.mp4), which was never on the preview; confirm with Karen
- Thin white strip under hero wave
- Hosting ends Nov 4 2026

## Copy rule exceptions (approved)
- "Infinity - Susanna Smiles" (spaced hyphen) is the client's legal name, approved Oct 29 2026 as an exception to the no-dash rule. build/verify.sh allowlists this exact string only (ALLOW list); any other dash still fails, and any other spelling of the name (no dash, unspaced hyphen, en/em dash) fails the "org name" lint.

## Edit log
- Oct 29 2026: Karen's Oct 29 edits: name with dash everywhere; home: Kansas City Metro in first paragraph, mission statement trimmed, "In 2024/2025" removed, Step 1 states the Greater Kansas City area; Application blurb and Airtable form from live site; Susanna's Story tightened; Givebutter donate button replaced by PayPal placeholder; Dance to Infinity and Knuckleheads merged.

## Drive sources checked (Oct 29, read-only, folder "Infinity - Susanna Smiles")
- Website detail for SS / "Final Infinity Marks story.docx": primary source for Susanna's Story. Tightened story on susannas-story.html cross-checked: every fact matches; nothing added.
- Website detail for SS / "Potential content for Infinity Susanna Smiles website.docx": same story text (cross-check only). Its FAQ also says donations can be made "through our PayPal link", but no URL is given.
- Testimonials / "Testimonials" (Google Doc): Jamie, Kristen and Kim quotes on index.html already match verbatim, with first-name attributions only.
- Logos / "Infinity Logo.png" and "LOGO - Infinity (Susanna Smiles).pptx" (contains the same PNG); "Infinity Final Logo-01.png" is also there. There is NO standalone heart file: the heart exists only inside the full wordmark logo. The decorative img/infinity-heart.svg was not swapped. Open item: ask Karen for a heart-only file, or approve a crop from Infinity Logo.png.
- ISS Photos / Susanna pictures: filenames listed only. No photos were replaced, pending Karen's photo discussion.

## Live content restored (Oct 29 2026, second add-on)
Source: live backup /workspace/apex_hq/infinity/live-backup-2026-10-29/ (api/pages-1.json + wp-content/uploads). Copy verbatim except org name normalized to "Infinity - Susanna Smiles".
- news.html: A Legacy of Hope (text only; 4th video mp4 omitted), 2026 Announcements & Events (flyers, photos, Dance to Infinity Sponsorship Package + 2026 deck PDF, new Facebook page, Cards Against Cancer flyer + form link, 2025 sponsor thank-you), 2025 Announcements & Events (2025 sponsorship package slides, 2025 deck PDF, sponsorship sign-up, Time Is Ticking promo, BINGO thank-you + flyer PDF, 2025 Event Photos), 2024 Sponsors & Announcements (sponsor logos, Dec 29 2023 kick-off, July 18 2024 event + PDF, tickets flyer PDF, 2024 Event Photos), Quarterly Newsletters (Quarterly-newsletter.pdf), Videos (3 YouTube, no 4th video). Merged Dance to Infinity at Knuckleheads card unchanged. Images in img/news/ (large PNGs re-saved as JPEG, max 1600px, content unchanged); PDFs in files/.
- index.html: "Over $110,000 provided to families in need in 2024" stat beside the $370K stat; Testimonials heading verbatim from live.
- donate.html: Tax-exempt information + Volunteers Needed (live volunteer Airtable form).
- get-support.html: Supportive Pillars (4 paragraphs).
- volunteer.html: volunteer-run / no paid employees line + Ways to Help.
- Dropped (not migrated): live Landing Page, WordPress "Hello world" post, gray placeholder video tiles.
- build/redirects-plan.csv: 301 plan for cutover only.
- COPY FLAGS pending Karen (verify.sh spaced-hyphen rule): donate "Donations ARE Tax-Deductible - the amount" and news "$20+taxes/fees - Standing Room Only" / "$50+taxes/fees - Reserved Seating" shown with colons; originals kept in HTML comments. Live typos "excel" and "provide" in the tax wording kept verbatim. Live FAQ "501c3 – Non-Profit" (en dash) not migrated; FAQs stay on about.html. Live Get Involved lists zip 64063; preview keeps 64081 per Oct 18 email.
