# Key Changer — pages

Welcome, uninstall and feedback pages for the Key Changer Chrome extension, served via GitHub Pages.

- `/welcome/` — opens once after installation (`WELCOME_URL`)
- `/uninstall/` — removal survey; Chrome opens it after the extension is removed (`UNINSTALL_URL`)
- `/feedback/` — opened by 1–3 stars in the extension's rating prompt (`FEEDBACK_URL`)
- privacy policy lives in a separate repo: https://github.com/anastasialekasova-hub/key-changer-privacy

Answers from `/uninstall/` and `/feedback/` go to Google Forms. The form ID and entry IDs are the
constants at the bottom of each page; while `FORM_ID` is empty, "Send feedback" only shows the
thank-you message and sends nothing.
