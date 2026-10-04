## Zakaria Mamoumi

Python automation and integrations. I build the unglamorous middle layer: the script
that collects, checks and delivers data on a schedule, and the integration between two
tools that were never meant to talk to each other.

I run this stack in production every day on my own infrastructure — live storefronts
with multi-currency checkout, a customer-service assistant answering from real product
and order data, and scheduled jobs that alert me on Telegram when something breaks
instead of when someone notices.

**What I care about in data work**

Most pipelines fail quietly. They return a full spreadsheet with a few wrong rows, and
because the wrong rows are invisible, the whole file has to be treated as unverified.
So I ship provenance with the data: every value carries the page it came from, and
anything that cannot be confirmed is marked rather than guessed or dropped.

That principle is easier to show than to claim, which is why
[b2b-contact-extractor](https://github.com/mzackarrya-stack/b2b-contact-extractor)
is public. Its README documents four ways that kind of tool produces confident, wrong
output — all four found by checking results against live pages, not by reading the code.

**Public projects**

| Project | What it shows |
| --- | --- |
| [wp-quote-calculator](https://github.com/mzackarrya-stack/wp-quote-calculator) | WordPress instant quote form. The browser previews the price, the server recalculates it in integer cents, so the visitor and the email never disagree by a cent. |
| [email-auth-checker](https://github.com/mzackarrya-stack/email-auth-checker) | SPF, DKIM, DMARC and MX checks that explain the silent failures: SPF over 10 lookups, `p=none`, selectors DNS cannot list. |
| [selfhosted-automation-stack](https://github.com/mzackarrya-stack/selfhosted-automation-stack) | n8n on one VPS behind Nginx and Let's Encrypt, with verified backups, Telegram alerts that do not spam, and a restore drill. |
| [b2b-contact-extractor](https://github.com/mzackarrya-stack/b2b-contact-extractor) | Contact data with the source page of every value, and no guessed addresses. |
| [n8n-hardened-lead-pipeline](https://github.com/mzackarrya-stack/n8n-hardened-lead-pipeline) | n8n workflows built to run unattended: dedupe, retries, a watchdog for a trigger that silently stops, one shared error workflow. |

Each one is small, tested, and MIT-licensed. The READMEs spend more time on how the tool
can be wrong than on what it does.

**Working with me**

Everything in writing. I scope before I quote, and if I think an approach will not get
you the result you want, I say so before you pay rather than after.

`Python` · `REST APIs` · `WooCommerce / WordPress` · `Docker` · `Linux` · `OpenAI and Claude APIs`

English · Français · العربية

**En français** : développeur Python freelance basé à Bordeaux, 100 % à distance et par
écrit. Automatisation, intégrations d'API, WordPress / WooCommerce (plugins, paiements,
dépannage) et serveurs Linux. Devis au forfait après un brief écrit.
