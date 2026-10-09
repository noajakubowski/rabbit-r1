# rabbit-r1

Egna appar (creations) för Rabbit R1, installeras via QR utan jailbreak.
Publiceras med GitHub Pages: https://noajakubowski.github.io/rabbit-r1/

| App | Mapp | Installera |
|---|---|---|
| R1 Remote – Spotify-fjärrkontroll | `spotify/` | Öppna `spotify/setup.html` på datorn, logga in, skanna QR |
| Nattklocka – alarm med Sveriges Radio | `nattklocka/` | Skanna QR på `nattklocka/install.html` |

## R1 Remote
- Spelas nu med omslag, play/paus, nästa/föregående. Scrollhjul = volym, sidoknapp = play/paus.
- Sök: håll in sidoknappen och prata, eller skriv. Scrollhjul väljer, sidoknapp spelar.
- Listor: dina spellistor. Enhet: välj var musiken spelas (Spotify Connect).
- Kräver Spotify Premium och en app i developer.spotify.com (Development Mode).
- Inloggningen (refresh token) följer med i installations-QR:en och sparas i R1:s säkra lagring.

## Nattklocka
- Sidoknapp: ställ alarm (timme → minut → kanal → på/av). Scrollhjul ändrar.
- Håll in sidoknappen: radio på / insomningstimer 15–30–60 min / av.
- Vid larm: sidoknapp = snooza 9 min, håll in = stäng av.
- Tryck **God natt** innan du somnar och låt R1 ligga i laddaren (docked mode håller skärmen vaken).
- `?test=1` sätter alarmet en minut fram.

Nya appar läggs i egna mappar. Bumpa `?v=` i install-QR:en efter större ändringar (R1 cachar install-URL:en).
