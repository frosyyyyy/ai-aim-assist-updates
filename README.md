# AI Aim Assist – Update Channel

Öffentlicher HTTPS-Update-Kanal für **AI Aim Assist 1.3.4**.

## Download

Das Release besteht aus zwei Teilen, weil GitHub einzelne Assets auf 2 GiB begrenzt:

- `AI-Aim-Assist-1.3.4-win64.zip.001`
- `AI-Aim-Assist-1.3.4-win64.zip.002`

Beide Dateien in denselben Ordner herunterladen, dort `cmd.exe` öffnen und ausführen:

```bat
copy /b AI-Aim-Assist-1.3.4-win64.zip.001 + AI-Aim-Assist-1.3.4-win64.zip.002 AI-Aim-Assist-1.3.4-win64.zip
```

Das entstandene ZIP entpacken und `start.bat` starten.

**Größe:** `2.904.273.269` Bytes

**SHA-256:**

```text
799F58ED0D4A8FEB11874F5396DE92DAEEE5EE160982D3AAD49433E7C0251CB4
```

## Automatische Updates

Die App enthält die Manifest-URL bereits:

```text
https://github.com/frosyyyyy/ai-aim-assist-updates/releases/latest/download/latest.json
```

Unter **System > Updates** kann die Aktualisierung manuell geprüft werden. Der
Updater lädt beide Teile, prüft die Einzel- und Gesamt-SHA-256 und setzt das
Paket erst nach erfolgreicher Prüfung zusammen.
