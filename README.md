# LocalFold

Static site for the Local Fold app's legal documents.

Live at <https://wzslr321.github.io/LocalFold/>.

- `index.html` — landing page with links to the privacy policies.
- `privacy.html` — Privacy Policy (English).
- `privacy_pl.html` — Polityka prywatności (Polish).

The contact email shown in each policy is rendered as `wzajac.contact [at] gmail.com` and rehydrated into a real `mailto:` link by inline JavaScript at page load. This blocks naive scrapers from harvesting it as plain text. Update the address in the inline `<script>` block at the bottom of each policy file if it ever changes.
