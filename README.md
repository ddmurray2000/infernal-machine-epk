# INFERNAL MACHINE EPK

Elektronische perskit van INFERNAL MACHINE, alt-metal uit Zuid-Holland. Debuut-EP POISON[ED].

Statische site, geen build nodig. `index.html` staat in de root; alle foto's, logo's, pdf's en tech riders staan in `img/`, `press/` en `pdf/`.

## Deployen op Cloudflare Pages

1. Cloudflare dashboard → Workers & Pages → Create → Pages → Connect to Git.
2. Kies deze repo, branch `main`.
3. Framework preset: None. Build command: leeg laten. Build output directory: `/`.
4. Save and Deploy. Elke push naar `main` zet automatisch een nieuwe versie online.
