FRANKLY LEGAL SITE — SETUP NOTES

Files:
- index.html
- privacy.html
- terms.html
- community-guidelines.html
- contact.html

Before publishing:
1. Create and verify the support email. The current draft uses franklybites.support@gmail.com as a PLACEHOLDER; replace all occurrences if you choose a different address.
2. Review every statement against the actual production app, especially location processing, photo visibility, analytics, retention, and account deletion.
3. These are starter drafts, not legal advice. Consider legal review before public launch.
4. Create a separate public GitHub repository, e.g. frankly-legal, and upload these files to its root.
5. In that repository, open Settings > Pages. Choose Deploy from a branch, select main and /(root), then Save.
6. GitHub Pages site URLs will look like https://OWNER.github.io/frankly-legal/ with pages /privacy.html, /terms.html, /community-guidelines.html, and /contact.html.
7. Wait for GitHub Pages deployment and open each URL to verify it loads before putting URLs in the app.

Do not place app secrets, Supabase service-role keys, or private source files in the public legal-site repository.
