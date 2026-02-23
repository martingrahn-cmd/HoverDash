# HoverDash - Improvements & Roadmap

## Gameplay Improvements

### Hold för Roll = Avvaktar med denna funktionen.
- Håll nere hopp-knappen i luften → skeppet gör en kontinuerlig roll (rotation runt Z-axeln)
- Långsammare än dubbelhopp-spinn men ser smooth ut
- Ingen poängbonus men stiligt visuellt
- Roll-hastighet: ~2 varv/sekund

---

## Prioriteringslista

| Prio | Uppgift | Status |
|------|---------|--------|
| 1 | Paus-funktion | Klart |
| 2 | Ljudeffekter (SFX) | Klart |
| 3 | Swipe-down duck (mobil) | Klart |
| 4 | Combo/multiplier-system | Klart |
| 5 | Milstolpar/achievements | Klart |
| 6 | Dagliga utmaningar | Design |
| 7 | Fler hindertyper | Design |
| 8 | CrazyGames SDK + Leaderboard + Ads | Sist |

---

## Nästa omgång

### UI / Menyer
- [ ] Pausmenyns RESUME-knapp är fortfarande solid turkos — byt till outline-stil som game over-knapparna
- [ ] Pausöverlayens bakgrund har annan opacity än game over — gör dem lika

### Ljud
- [ ] Music ska vara ON som default (är OFF nu)
- [ ] Spara music/SFX-toggle till localStorage och ladda vid start

### Mobil
- [ ] Pausknappen för liten (40x40px) — svår att träffa på mobil, öka storlek
- [ ] Ingen visuell feedback vid swipe (lane change-förhandsgranskning)
- [ ] HUD skalar dåligt på små skärmar — lägg till responsiva media queries

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
