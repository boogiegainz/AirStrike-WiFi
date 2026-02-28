## ⚡ How It Works

AirStrike is a next-generation WiFi auditing platform built on top of the
aircrack-ng suite — redesigned from scratch with a modern dark GUI, async
attack engine, and full Windows support.

### On Windows
1. **Scan** nearby networks using Windows' built-in `netsh` — no drivers, no setup
2. **Import** a `.cap`, `.hccapx`, or `.hc22000` file captured from any device
3. **Crack** it locally using hashcat (GPU-accelerated) or aircrack-ng (CPU)
4. **Copy** the recovered password straight to your clipboard

### On Linux (Kali / ParrotOS)
1. **Scan** live — airodump-ng captures every AP and client in range
2. **Select** a target from the real-time network table
3. **Attack** — AirStrike auto-escalates through the best attack chain:
   - WPS Pixie-Dust → PMKID capture → WPA Handshake → WPS PIN → WEP
4. **Crack** the captured hash with hashcat or aircrack-ng
5. **Report** — export results as HTML, JSON, or CSV

### What makes it better than wifite2
| Feature | wifite2 | AirStrike |
|--------|---------|-----------|
| GUI | ❌ Terminal only | ✅ Full dark-mode desktop app |
| Windows support | ❌ | ✅ Scan + crack on Windows |
| Attack auto-escalation | Basic | ✅ Smart priority queue |
| Session persistence | ❌ | ✅ SQLite — resume anytime |
| Real-time signal graph | ❌ | ✅ Live matplotlib chart |
| First-run setup wizard | ❌ | ✅ Guided setup |
| Packaged .exe | ❌ | ✅ Single-file, no install |
