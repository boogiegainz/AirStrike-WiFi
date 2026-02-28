## ⚡ How It Works

AirStrike is a next-generation WiFi auditing platform built on top of the
aircrack-ng suite — redesigned from scratch with a modern dark GUI, async
attack engine, and full Windows support.

### On Windows
1. **Scan** nearby networks using Windows' built-in `netsh` — no drivers, no setup
2. **Import**  />
a `.cap`, `.hccapx`, or `.hc22000` file captured from any device
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
| First-ru<img width="620" height="544" alt="Screenshot 2026-02-28 160727" src="https://github.com/user-attachments/assets/9ccccd9c-7565-4ff7-b1d8-93c3ee363b4f" />
n setup wizard | ❌ | ✅ Guided setup |
| Packaged .exe | ❌ | ✅ Single-file, no install |
<img width="1300" h<img width="619" height="540" alt="Screenshot 2026-02-28 160742" src="https://github.com/user-attachments/assets/c27a1f14-cece-4ca9-ac22-da9a88d373cd" />
eight="706" alt="Screenshot 2026-02-28 160516" src="https://github.com/user-attachments/assets/31c986f2-b52c-4ec9-bd03-ea9<img width="614" height="542" alt="Screenshot 2026-02-28 160540" src="https://github.com/user-attachments/assets/51bcbb64-2e3a-46df-bd13-a4bf3dba0633" />
16cbc1c5b" /><img width="1300" height="706" alt="Screenshot 2026-02-28 160516" src="https://github.com/user-attachments/assets/d11c6866-9cfc-4164-9b12-6563f7eb4693" />

