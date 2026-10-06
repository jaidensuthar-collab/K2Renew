# K2 Renew landowner page

Design source for the redesigned landowner page (Design canvas files).

- `Main.dc.html`: the page (fluid, mobile first, light and dark themes)
- `Mobile.dc.html`: the same page framed at 390px
- `Developers.dc.html`, `Communities.dc.html`: the other two audiences, copy from k2renew.com
- `Faq*.dc.html`: five FAQ pages, answers from k2renew.com/resources and the land criteria (`FaqPage` is the shared template)
- `canvas.json`: canvas layout index

## Still to supply (flagged in gold on the page)
- Lease term: not stated anywhere on k2renew.com. No number until K2 Renew provides one.
- Business hours and who answers the phone: not stated.
- Property-value answer (myth 2): no verified source.
- Real photos of leased sites, landowner stories (x3), team (x3).
- Which legal name belongs in the footer: K2 Renew LLC or K2 Renew NW LLC.
- Acreage: this page uses 100+ everywhere (plus 20 to 100 combined). The live /resources FAQ says "at least 300 acres" and needs correcting on k2renew.com.

## Corrections to the brief
- The live landowner form has ten fields (first and last name, phone, email, are-you-the-landowner, landowner's name, state, county, zip, acreage), not eleven.
- The live consent wording covers SMS and Email, but this page collects no email. Keep it verbatim; ask K2 Renew's counsel whether SMS-only wording is wanted for A2P 10DLC.
- Email on the site: passiveincome@k2renew.com (now in the footer).

## Build notes
- SMS consent wording is taken verbatim from /landowner-form. Store the exact wording shown and a server-side timestamp, not just a boolean.
- "How long am I locked in?" has no FAQ page: k2renew.com has no answer.
- The form is a static design and does not submit yet.
