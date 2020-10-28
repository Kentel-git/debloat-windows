# debloat-windows
Some scripts to debloat windows installations, by Chris Titus

### Regular (No OneDrive, Indexing, and Defender)

```bash
powershell -nop -c "iex(New-Object Net.WebClient).DownloadString('https://git.io/JJ8R4')"
```

### Minimal (Only Targets Bloatware/Telemetry)

```bash
powershell -nop -c "iex(New-Object Net.WebClient).DownloadString('https://git.io/JJ5qc')"
```
