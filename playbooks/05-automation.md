# 5. Automate the Boring Parts

Uses intake: A3–A4, D14–D15.

| Function | Tools (pick one per row) | Fully automate | Keep a human in the loop | Guardrail |
|----------|------|------|------|------|
| **Research** | Google Alerts, Feedly/RSS + AI summary, Make/Zapier → Claude/ChatGPT digest | Weekly competitor/trend digest; keyword lists | Deciding what to build | Check sources before acting on any claim |
| **Content** | Claude/ChatGPT for drafts and repurposing; Descript/CapCut; Buffer/Typefully for scheduling | Repurposing 1 long piece → 5–10 short ones; scheduling | Ideas, final edit, personal stories | Keep a voice guide + examples file; never publish unreviewed AI text |
| **Support** | Help-center FAQ + AI chatbot (Intercom Fin, Crisp, or a custom GPT), canned email replies | Delivery issues, FAQs, password/download resends | Refunds, complaints, anything emotional | "Talk to a human" always visible; reply within 24h SLA |
| **Marketing** | Kit/Beehiiv/MailerLite automations; Gumroad/Lemon Squeezy workflows | Welcome sequence, abandoned cart, post-purchase review and upsell | Launch emails, offers | Monthly test-send of every sequence; easy unsubscribe |
| **Operations** | Make/Zapier, Notion templates | Sale → spreadsheet/CRM, invoice, delivery, tagging | Finances, contracts | Error alerts to your phone; monthly audit |
| **Analytics** | Stripe/Gumroad + email platform → Google Sheets → AI weekly summary | Weekly KPI email: revenue, subs, conversion, top traffic sources | Interpreting it, deciding what to do | Watch 3–5 numbers max |

## Build this first
**Sale → delivery → welcome/upsell email sequence.** This one sale-triggered flow handles fulfillment, onboarding, review requests, and the next sale. It takes under 2 hours with Gumroad/Lemon Squeezy + Kit, and you never touch it again.

## How close to "runs without me"
*Realistic:* ~2–5 hrs/week of upkeep for one mature product stream. Product decisions, content ideas, and handling exceptions stay with you, and that's on purpose.

## Personalized plan
*Stand 2026-10-15. Stack: Python, Make, Power Automate, Cursor, Replit, HTML/CSS/JS.*

### Zuerst bauen (≤ 1 Wochenende)
**Readiness-Check → Bericht → E-Mail-Sequenz → Kalender-Link**
Formular → Make → LLM erzeugt Kurzbericht (PDF) → E-Mail-Tool versendet ihn + 4-teilige Sequenz (Fallstudie, Audit-Angebot, Cockpit-Demo, letzte Erinnerung) → Kontakt im CRM mit Punktzahl. Das ist gleichzeitig Lead-Magnet, Qualifizierung und Verkauf.

### Danach
| Funktion | Automatisieren | Mensch bleibt drin | Guardrail |
|----------|----------------|--------------------|-----------|
| **Audit** | Fragebogen, Datenauswertung, Berichtsentwurf per LLM | 60-Min-Gespräch, Empfehlungen prüfen | Nie einen Bericht ungelesen versenden |
| **Cockpit-Onboarding** | Zahlung → Konto anlegen → Willkommens-Mails Tag 0/3/7/14 → Nutzungs-Check | Kurzer Onboarding-Call für die ersten 20 Kunden | Kunden ohne Login nach 7 Tagen → Alarm an dich |
| **Abrechnung** | Stripe-Abo bzw. QR-Rechnung, Mahnungen, MWST-Export | Zahlungsausfälle, Rabatte | Monatlicher Abgleich mit Buchhaltung |
| **Support** | FAQ + KI-Chat im Cockpit für Standardfragen | Alles zu Daten, Kündigung, Beschwerden | „Mensch kontaktieren“ immer sichtbar; Antwort ≤ 1 Werktag |
| **Partner** | Provision automatisch berechnen, monatlicher Partner-Report | Neue Partner aufnehmen | Partner-Vertrag mit Datenschutzklausel |
| **Kennzahlen** | Wöchentliche Mail: MRR, neue/verlorene Kunden, Readiness-Checks, Audits, Stunden | Entscheiden, was sich ändert | Max. 5 Zahlen |

### Deine eigenen Zeitfresser (D15)
Manuelle Schnittstellenpflege, Dokumentation, uneinheitliche Auswertungen — genau das löst das Cockpit für KMU. **Löse sie zuerst bei dir selbst mit dem Cockpit.** Das spart Zeit und liefert deine stärkste Fallstudie.

### Wie nah an 5–6 h/Woche
Erreichbar ab ca. **30–50 Kunden**, wenn Onboarding und Support automatisiert sind. Bei 134 Kunden brauchst du wahrscheinlich eine Teilzeit-Hilfe für Support (~4–8 h/Woche, ca. CHF 300–700/Monat) — *Annahme*, aus dem Reinvestitionsanteil bezahlt.
