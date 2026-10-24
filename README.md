# Einreichungen — richtige Liste

Stand: 2026-10-24. Ehrlich getrennt: Was Geld bringen kann, was nur Ruf bringt, was blockiert ist.

## A. Bezahlbare Einreichungen (echte Schwachstellen-Berichte)

| # | Ziel | Fund | Kanal | Status |
|---|------|------|-------|--------|
| 1 | CometBFT | Vote-Extension DoS Amplifier (HIGH) | HackerOne | Eingereicht, geschlossen |
| 2 | Sui | ExecutionTimeObservation Authority Spoofing (HIGH) | HackenProof | Eingereicht, blockiert: 150 Reputation nötig |
| 3 | Firedancer | VarInt Offset Accumulation (HIGH) | Immunefi | Bereit, blockiert: 100 $ Einsatz |
| 4 | Firedancer | PRUNE-storm Reflection (HIGH) | Immunefi | Bereit, blockiert: 100 $ Einsatz |
| 5 | Firedancer | Runtime Stack Overflow (HIGH) | Immunefi | Bereit, blockiert: 100 $ Einsatz |
| 6 | Circle MALA | Sync Proposer Attribution (HIGH) | HackerOne | Eingereicht, wartet |
| 7 | Circle ARC | chain_id Omission (HIGH) | HackerOne | Eingereicht, wartet |
| 8 | Drift | VAULTS-001 + ORACLE-001 (CRITICAL + HIGH) | Direkt-Mail | Eingereicht, keine Antwort |

Geld bisher aus A: 0 $. Grund: Duplikat-Schließung, Einsatz- und Reputations-Tore, ausstehende Antworten.

## B. Öffentliche Einreichungen (Ruf, kein direktes Geld)

- 40+ Agenten-Funde (Token-Bewertungen), öffentlich auf GitHub: https://github.com/agentmitgit/agent-audit-findings
- Zweck: Reputation aufbauen (öffnet z. B. HackenProof-Tor aus A2).
- Diese Funde sind KEINE bezahlten Einreichungen. Niemand zahlt für Punktelisten.

## C. Test-Handel (Spielgeld, kein Echtgeld)

- Paper-Trading im Rust-Dashboard (http://localhost:8100/): Start 100 Test-Dollar, echte Kurse, Positionen werden laufend bewertet.
- Zweck: Üben ohne Risiko, bis erstes echtes Geld da ist.

## D. Blockiert — wartet auf eine einmalige Nutzer-Aktion

| Tor | Was fehlt | Wer muss es tun |
|-----|-----------|-----------------|
| Bezahl-Wettbewerbe (z. B. Sherlock) | Einmalige Anmeldung mit echtem Namen (Auszahlungs-Identität + privates Contest-Repo) | Nutzer, ca. 2 Minuten, Sprachführung möglich |
| Immunefi Firedancer (A3–A5) | 100 $ Einsatz pro Programm | Nutzer entscheidet über Geld |
| AgentWallet Mainnet | Dienst-API tot (404) + SOL für Deploy, Wallet leer | Warten oder Funding durch Nutzer |

## Regel

Alles aus A und B ist eingereicht oder einreichfertig abgelegt. Neue bezahlbare Funde entstehen nur noch aus echten Programm-Prüfungen (Wettbewerbs-Code), nicht aus Token-Listen.
