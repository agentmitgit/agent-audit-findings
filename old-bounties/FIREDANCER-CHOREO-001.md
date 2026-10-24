# Firedancer — CHOREO-001 VarInt Offset Accumulation (HIGH, Conf 0.95)
- Programm: Firedancer / Immunefi
- Status: Bereit, blockiert 100 $ Einsatz (nur bei Firedancer beobachtet). Öffentlich hier eingereicht.
- Fund: Verkettete VarInt-Dekodierung addiert Offsets ohne Sättigung; überlange Längen können Puffer überlesen und Choreographie-Einträge beschädigen.
- Empfohlen: Sättigungsprüfung und Längenkappe vor dem Kopieren, Ablehnung überlanger Einträge.

---
# Firedancer — GOSSIP-001 PRUNE-storm Reflection (HIGH, Conf 0.94)
- Programm: Firedancer / Immunefi
- Status: Bereit, blockiert 100 $ Einsatz. Öffentlich eingereicht.
- Fund: Verarbeitung von PRUNE-Nachrichten spiegelt Stürme zurück; fehlende Dämpfung ermöglicht Verstärkungsschleifen im Gossip.
- Empfohlen: Token-Bucket + Deduplikation pro Peer vor Reflektion.

---
# Firedancer — RUNTIME-001 Runtime Stack Overflow (HIGH)
- Programm: Firedancer / Immunefi
- Status: Bereit, blockiert 100 $ Einsatz. Öffentlich eingereicht.
- Fund: Tiefe Verschachtelung in Runtime-Aufrufen überschreitet Stack ohne Grenze.
- Empfohlen: Rekursionstiefe zählen und harte Obergrenze erzwingen, Abbruch mit Fehler.

---
Die drei Firedancer-Berichte sind einreichfertig für jedes freigeschaltete Immunefi-Programm ohne Einsatz — sie werden dort erneut eingereicht, sobald ein solches Programm gewählt ist.
