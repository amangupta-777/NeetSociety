NEET Society single-page website
================================

Files:
- index.html: responsive single-page website
- neet-society-logo.webp: compressed brand logo used in the header and footer

Latest updates:
- Replaced the NS fallback appearance with the supplied compressed NEET Society logo asset.
- Connected the registration form to the Google Form response endpoint using the field IDs from the pre-filled link.
- Registration details are submitted to Google Forms, not WhatsApp. The optional free-text message field is not sent because the supplied Google Form link did not include a matching field ID.
- Updated the floating WhatsApp button to the supplied community invite and shortened its label to “Join WhatsApp Community”.

Important testing note:
The site uses a direct formResponse POST from a static page. Google Forms may accept the submission, but cross-origin browser restrictions mean the page cannot reliably verify the response. Before publishing, submit a test entry and check the Google Forms Responses tab. If it does not arrive, use an embedded Google Form or a form service/backend for reliable collection.

Before publishing:
- Verify the WhatsApp contact number and community invite.
- Add Instagram URL when ready.
- Add mentor profiles only after recruitment and verification.
- Add appropriate privacy/consent information for lead collection.
