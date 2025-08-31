# Videothek – Custom Jellyfin CSS

Dieses Repository enthält benutzerdefinierte CSS-Anpassungen für Jellyfin.  
Es verändert unter anderem:
- Trickplay: Zeit mittig, größer, Kapitelname ausgeblendet
- UpNext-Dialog: Schrift kleiner, Sterne/Dauer/Endzeit entfernt, Buttons zentriert, runde Ecken
- Detailseite: Autoren und Studios ausgeblendet

---

## Nutzung in Jellyfin

1. Öffne dein **Jellyfin Dashboard → Branding**.
2. Trage im Feld **Benutzerdefiniertes CSS (URL)** folgenden Link ein:

   ```css
   @import url("https://cdn.jsdelivr.net/gh/SMAUB/videothek@main/custom.css");
