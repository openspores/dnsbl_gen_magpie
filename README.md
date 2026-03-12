# DNSBL Generator

This repo runs **[PigeonSec's](https://github.com/pigeonsec)** amazing tool **[Magpie](https://github.com/pigeonsec/magpie)** to generate DNS blocklists.

PigeonSec Magpie is a high-performance blocklist aggregator that fetches, deduplicates, validates, and combines domains from multiple sources ..and looks REeal good while doing it.

It's public because GitHub charges for private repo minutes after March 2026.

## What this does

- Runs Magpie daily on GitHub's free servers (Thanks Microslop! 😃)
- Creates a blocklist release for my router to download

## All credit goes to:

- **[StasonJatham](https://github.com/StasonJatham)** ([karl.fail](https://karl.fail/) / [karlcom.de](https://karlcom.de/#home) / [Karl's LinkedIn](https://www.linkedin.com/in/karl-machleidt/)) for his amazing work writing Magpie, hire him NOW!
- **[Magpie](https://github.com/pigeonsec/magpie)** itself – go give it a star! ⭐
- **[PigeonSec](http://pigeonsec.com)** – Visit PigeonSec's website
- **The blocklist maintainers** listed in [`sources.txt`](sources.txt) – you do all the real work. We owe you all a massive debt of gratitude.
- **Microslop** – for free GitHub Actions minutes
