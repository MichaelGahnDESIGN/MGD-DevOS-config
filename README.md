# MGD-DevOS Config

Öffentliche, minimale Laufzeit-Konfiguration für die App
[MGD-DevOS](https://github.com/MichaelGahnDESIGN/MGD-DevOS) (privates
Repository). Enthält bewusst **keine** Quelltexte, keine Zugangsdaten und
keine sonstigen sensiblen Daten — nur Anzeigetext, öffentliche URLs und
Schalter, die die App beim Start ohne Login abrufen kann.

Dieses Repo ist öffentlich, weil ein Desktop-Client keinen GitHub-Token
sicher aufbewahren kann. Ein privates Repository würde für anonyme
Anfragen 404 liefern.

## mgd-devos-config.json

| Feld | Bedeutung |
|---|---|
| `app_title` | Angezeigter App-Titel |
| `target_url` | Aktuell leer: es existiert noch keine öffentlich erreichbare Web-Version von MGD_AI-Projektmanager. Wird erst gesetzt, wenn es eine gibt. |
| `stripe_donation_url` | Aktuell leer: es gibt noch kein Live-Stripe-System für MGD-DevOS (siehe `docs/mgd-devos/STRIPE-SPENDEN.md` im Quellrepo). |
| `show_donation_button` | `false`, solange kein geprüfter Spendenlink existiert. |

Änderungen an dieser Datei wirken sich beim nächsten App-Start aus (keine
Neuveröffentlichung der App nötig).
