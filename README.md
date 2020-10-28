# debloat-windows
Some scripts to debloat windows installations, by Chris Titus

### Regular (No OneDrive, Indexing, and Defender)

```bash
powershell -nop -c "iex(New-Object Net.WebClient).DownloadString('https://bit.ly/3kCHMm9')"
```

### Minimal (Only Targets Bloatware/Telemetry)

```bash
powershell -nop -c "iex(New-Object Net.WebClient).DownloadString('https://bit.ly/2TwRo6n')"
```
