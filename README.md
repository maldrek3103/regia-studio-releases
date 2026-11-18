# Regia Studio

**Registra lo schermo, vai in diretta e fai regia video su Windows.**
Scene, transizioni, mixer audio, replay e rimozione dello sfondo con l'IA, in un'unica app nativa e leggera.

*[English below](#english)*

## Scarica

| | |
|---|---|
| **Microsoft Store** (consigliato) | [Regia Studio nel Microsoft Store](https://apps.microsoft.com/detail/9NJWS7HJS9DP): installazione senza avvisi di Windows, aggiornamenti dallo Store. *Il link funziona appena l'app è pubblicata.* |
| **Installer** | `Regia-setup.exe` dall'[ultima versione](https://github.com/maldrek3103/regia-studio-releases/releases/latest). Si installa senza permessi di amministratore e si aggiorna da sola. |
| **Versione portatile** | `Regia-windows-x64.zip` dall'[ultima versione](https://github.com/maldrek3103/regia-studio-releases/releases/latest): estrai e avvia `Regia.exe`. |

> **«Windows ha protetto il PC»?** L'installer scaricato da qui non ha ancora una firma digitale, quindi SmartScreen può mostrare un avviso. Premi **Ulteriori informazioni › Esegui comunque**, oppure installa Regia Studio dal Microsoft Store, dove è firmata da Microsoft.

## Requisiti

- Windows 10 (versione 1809 o successiva) o Windows 11, 64 bit.
- Scheda video con DirectX 11.
- Facoltativi: webcam, microfono. La videocamera virtuale richiede Windows 11.
- Alcune funzioni scaricano un componente gratuito la prima volta che le usi: **FFmpeg** (formati MKV, più tracce audio, dirette) e il modello per la **rimozione dello sfondo**.

## Cosa sa fare

- **Sorgenti:** schermo, finestre, giochi, webcam, immagini, presentazioni, video, pagine web, testi, orologi e conti alla rovescia, scene dentro altre scene.
- **Scene e transizioni:** dissolvenza, scorrimento, stinger e altre, anche diverse per ogni scena; modalità Studio con anteprima e programma.
- **Registrazione** in MP4 o MKV, anche con più tracce audio; **replay buffer** per salvare gli ultimi secondi con un tasto.
- **Dirette** su YouTube, Twitch e qualsiasi server RTMP, SRT o WHIP, anche su più piattaforme insieme.
- **Tela verticale 9:16** per TikTok, Shorts e Reels, insieme a quella orizzontale.
- **Audio:** mixer con riduzione del rumore, noise gate, compressore, limitatore e plugin VST; audio della singola applicazione.
- **Effetti:** rimozione dello sfondo della webcam con l'IA (senza green screen), chroma key, correzione colore, LUT, maschere.
- **Controllo remoto** compatibile con obs-websocket: Stream Deck, Touch Portal, Streamer.bot e app per telefono.
- **Importa le scene da OBS Studio**, script per automatizzare la regia, videocamera virtuale per Zoom e Teams, uscita NDI.
- Interfaccia in **italiano, inglese, spagnolo, francese, tedesco e portoghese**.

## Privacy

Regia Studio non raccoglie dati personali e non usa pubblicità né statistiche: tutto resta sul tuo PC. Leggi l'[informativa sulla privacy](PRIVACY.md).

## Problemi e suggerimenti

Apri una segnalazione nella sezione [Issues](https://github.com/maldrek3103/regia-studio-releases/issues). Se qualcosa non funziona, allega le ultime righe del registro: premi Win+R, scrivi `%APPDATA%\Regia` e apri `regia.log`.

---

<a id="english"></a>

# Regia Studio (English)

**Record your screen, go live and produce video on Windows.**
Scenes, transitions, audio mixer, replay buffer and AI background removal, in one lightweight native app.

## Download

| | |
|---|---|
| **Microsoft Store** (recommended) | [Regia Studio on the Microsoft Store](https://apps.microsoft.com/detail/9NJWS7HJS9DP): no Windows warnings, updates through the Store. *The link works once the app is published.* |
| **Installer** | `Regia-setup.exe` from the [latest release](https://github.com/maldrek3103/regia-studio-releases/releases/latest). Installs without administrator rights and updates itself. |
| **Portable** | `Regia-windows-x64.zip` from the [latest release](https://github.com/maldrek3103/regia-studio-releases/releases/latest): extract it and run `Regia.exe`. |

> **"Windows protected your PC"?** The installer downloaded from here isn't digitally signed yet, so SmartScreen may show a warning. Click **More info › Run anyway**, or install Regia Studio from the Microsoft Store, where it is signed by Microsoft.

## Requirements

- Windows 10 (version 1809 or later) or Windows 11, 64-bit.
- DirectX 11 graphics card.
- Optional: webcam, microphone. The virtual camera requires Windows 11.
- Some features download a free component the first time you use them: **FFmpeg** (MKV, multiple audio tracks, streaming) and the **background removal** model.

## Features

- **Sources:** screen, windows, games, webcam, images, slideshows, videos, web pages, text, clocks and countdowns, nested scenes.
- **Scenes and transitions:** fade, swipe, stinger and more, even a different one for each scene; Studio mode with preview and program.
- **Recording** to MP4 or MKV, with multiple audio tracks; **replay buffer** to save the last seconds with one key.
- **Live streaming** to YouTube, Twitch and any RTMP, SRT or WHIP server, even to several platforms at once.
- **Vertical 9:16 canvas** for TikTok, Shorts and Reels, alongside the horizontal one.
- **Audio:** mixer with noise suppression, noise gate, compressor, limiter and VST plugins; per-application audio capture.
- **Effects:** AI webcam background removal (no green screen), chroma key, color correction, LUTs, masks.
- **Remote control** compatible with obs-websocket: Stream Deck, Touch Portal, Streamer.bot and phone apps.
- **Import scenes from OBS Studio**, scripting, virtual camera for Zoom and Teams, NDI output.
- Interface in **English, Italian, Spanish, French, German and Portuguese**.

## Privacy

Regia Studio collects no personal data and uses no ads or analytics: everything stays on your PC. Read the [privacy policy](PRIVACY.md).

## Issues and suggestions

Open a report in [Issues](https://github.com/maldrek3103/regia-studio-releases/issues). If something doesn't work, attach the last lines of the log: press Win+R, type `%APPDATA%\Regia` and open `regia.log`.

---

© 2026 Camillo Pisanu. All rights reserved.
