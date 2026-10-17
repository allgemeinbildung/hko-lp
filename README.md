# hko-lp

Geschützter Bereich für Lehrpersonen der HKO-Einheiten (Erwartungshorizonte, Lösungen, KN-Prompt).
Jede Seite unter `lp/` ist mit StatiCrypt verschlüsselt (AES-256, PBKDF2-SHA256 600 000) und fragt nach dem Passwort.

Dieser Ordner wird von `hko-content/scripts/hko-lp.mjs` erzeugt (`build/lp/site/`) und 1:1 in dieses Repo kopiert.
Nicht von Hand bearbeiten. Kein Klartext, kein Passwort in diesem Repo.

Seiten: `lp/lj1-konsum-budget.html`
