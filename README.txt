AXIOM PAPER TRADING — iPad Web-App MVP 0.1

Enthalten:
- Safari-optimierte Web-App
- Öffentliche Solana-Marktdaten über DexScreener
- Token-Scanner und Suche nach Symbol/Contract
- Virtuelles Startguthaben 1.000 USD
- Paper Buy/Sell, Positionen, P/L, Trade-Historie
- Gebühren und Slippage einstellbar
- Lokale Speicherung im Browser

INSTALLATION:
Eine ZIP-Datei kann nicht direkt als Safari-PWA installiert werden. Für "Zum Home-Bildschirm" muss die App über HTTPS gehostet werden. Danach in Safari öffnen -> Teilen -> Zum Home-Bildschirm. Der nächste Schritt ist, die Dateien über einen Hosting-Dienst (z. B. GitHub Pages) bereitzustellen.

WICHTIG:
Diese App ist KEIN Overlay über Axiom in iPad-Safari. iPadOS erlaubt einer normalen Webseite nicht, sich über eine andere Webseite zu legen oder Axiom intern zu verändern. Sie läuft eigenständig im Axiom-ähnlichen Layout. Eine native Safari-Web-Extension braucht einen separaten App-/Signierweg.

Grenzen:
- DexScreener-Profile/Boosts sind nur eine Kandidatenquelle, kein vollständiger Launch-Scanner.
- Score ist ein heuristischer Filterwert, keine Gewinnwahrscheinlichkeit.
- Datenaktualisierung ca. 45 Sekunden, nicht tickgenau.
- Simulierte Ausführung basiert auf dem letzten abgerufenen Preis plus/minus Slippage.
- Kein Wallet-Zugriff und keine echten Orders.
