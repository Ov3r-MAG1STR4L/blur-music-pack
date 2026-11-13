# Blur Music Pack

Play **your own music** during races in Blur (PC), with:

- **Next track** during a race: press L3 twice on a controller, or the `9`/`ç` or `0`/`à` key (French AZERTY layout).
- **Shuffle**: every track plays once in a random order, then the order repeats; each game session starts at a
  random point of that order. Works whatever you use to start Blur (Blur.exe, TextMod...).
- **Game effects on the sound** (power-ups, crashes, wrecked, low health): on, partial (softer) or off.

No music is included: you bring your own files (mp3, wav, flac, ogg, m4a).

## Download

Get `Blur_Music.zip` from the [latest release](https://github.com/Ov3r-MAG1STR4L/blur-music-pack/releases/latest),
then follow the step-by-step guide in `README.txt` inside the zip.

In short:

1. Install [Python 3](https://www.python.org/downloads/) (tick "Add python.exe to PATH") and ffmpeg
   (`winget install Gyan.FFmpeg` in a command prompt).
2. Unzip `Blur_Music` into the Blur folder, next to `Blur.exe`.
3. Put your music in `Blur_Music\Music\2 - My playlist\` (each sub-folder of `Music` is a playlist).
4. Run `Choose music.bat`, pick your playlists and the effects mode.
5. Start Blur as usual.

`Uninstall.bat` puts the game back exactly as it was.

## Requirements

- Blur for PC. The next-track key needs AMAX.
- About 3 GB of free disk space: on the first run, the pack unpacks the game's own audio archives (from your
  copy of the game: no game file is included here).

## Antivirus warning

Windows Defender may flag a freshly downloaded `Blur_Music.zip` as `Trojan:Script/Wacatac.B!ml`. The `!ml` suffix
means a machine-learning guess, not a known virus: it is a common false positive for new archives containing
scripts. The zip only contains text files (`.bat`, Python `.py`, `.lua`, `.txt`) that you can read before running
anything.

## Not affiliated

Fan-made, not affiliated with Activision or Bizarre Creations. Blur is a trademark of its owners.
