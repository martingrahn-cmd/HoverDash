# HoverDash - Improvements & Roadmap

## Gameplay Improvements

### Wall Gates - Djupare & Bättre Spacing = Fixat
- Gör väggarna ännu djupare (20-30 units) för maximal "whoosh"-känsla
- Förhindra att nya hinder spawnar direkt efter väggar — spelaren ser inte vad som är bakom. Lägg till en "safe zone" (15-20 units) efter varje WALL_GATE där inga obstacles spawnar

### Wall Gate Whoosh — 3-fas tunnelljud
- **Fas 1: Ingång** — kort attack-whoosh vid tunnelns kant
- **Fas 2: Tunnel** — ihållande vindbrus/resonans medan man är mellan väggarna
- **Fas 3: Utgång** — release-whoosh med pitch-shift uppåt vid utgång
- Allt sker extremt snabbt — anpassa durationer efter vägg-djup och hastighet
- Nuvarande whoosh spelas bara vid ingång — behöver utökas till fullständig 3-fas-upplevelse

### Tydligare Lanes i Marken = Fixat
- Neon-ränder längs varje lane-gräns i tunnelgolvet
- Pulsande ljusvågor som rör sig bakåt längs lane-linjerna (speed-synkade)
- Lane-highlight under skeppet som följer med
- Subtil färgskillnad per lane vid zonbyten

### Dubbelhopp (360 Spin) = Fixat
- Om spelaren trycker hopp en gång till i luften → skeppet gör en 360-graders barrel roll
- Ger bonuspoäng (+15 SPIN!)
- Kort invincibility under spin-animationen (0.3s)
- Cooldown: max en spin per hopp
- Visuell effekt: neon-trail i en spiral under spinnet

### Hold för Roll = Avvaktar med denna funktionen.
- Håll nere hopp-knappen i luften → skeppet gör en kontinuerlig roll (rotation runt Z-axeln)
- Långsammare än dubbelhopp-spinn men ser smooth ut
- Ingen poängbonus men stiligt visuellt
- Roll-hastighet: ~2 varv/sekund

---

## Prioriteringslista

| Prio | Uppgift | Status |
|------|---------|--------|
| 1 | Paus-funktion | Kör nu |
| 2 | Ljudeffekter (SFX) | Nästa |
| 3 | Swipe-down duck (mobil) | Snabbfix |
| 4 | Combo/multiplier-system | Brainstorm |
| 5 | Milstolpar/achievements | Brainstorm |
| 6 | Dagliga utmaningar | Design |
| 7 | Fler hindertyper | Design |
| 8 | CrazyGames SDK + Leaderboard + Ads | Sist |

---

## SFX att lägga till

### Spelarkontroller
- **Lane switch** — kort "woosh" vid filbyte
- **Jump** — uppsving-ljud när man hoppar
- **Landing** — mjuk landning efter hopp
- **Duck** — snabbt dyk-ljud vid duckning

### Kollisioner & Hinder
- **Crash/Death** — explosion/krasch vid kollision med laser
- **Shield hit** — metalliskt blockeringsljud när skölden tar en träff
- **Near miss** — subtilt ljud vid nära-ögat-undvikande
- **Boost smash** — krossljud vid boost genom hinder

### Insamling
- **Coin pickup** — kling/ping vid coin-upplockning
- **Shield powerup** — aktiveringsljud för sköld
- **Magnet powerup** — aktiveringsljud för magnet
- **Boost powerup** — turbo/acceleration-ljud

### Spelflöde
- **Countdown beep (3, 2, 1)** — pip för varje nedräkningssteg
- **GO!** — startljud
- **Zone transition** — subtilt ambient-skifte vid zonbyte
- **Speed increase** — eskalerande ljud vid hastighetsökning
- **Ramp launch** — ramp-avfyrningsljud
- **Wave complete** — kort jingle vid wave-byte

### UI
- **Menu click/tap** — knapp-tryck
- **High score** — fanfar vid nytt rekord
- **Game over** — stinger/jingle
