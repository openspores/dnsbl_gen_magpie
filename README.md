# DNSBL Generator

I take no credit for any of this work whatsoever.

This repo runs **[PigeonSec's](https://github.com/pigeonsec)** amazing tool **[Magpie](https://github.com/pigeonsec/magpie)** to generate DNS blocklists.

Quoting from their GitHub;

"Magpie is a high-performance blocklist aggregator that fetches, validates, and combines domain blocklists from multiple sources. Built in pure Go with a beautiful terminal UI powered by Bubble Tea, it's optimized for speed, reliability, and user experience."

Key Features:

    🎨 Beautiful TUI colorful terminal interface with real-time progress
    🚀 Parallel fetching with 6 DNS resolvers (bypasses Pi-hole)
    🎯 Smart filtering auto-blacklists failing URLs after 3 attempts
    📊 Stats tracking persistent health monitoring in data/stats.json
    ⚡ High performance 100 workers, DNS caching, connection pooling
    🔧 Format support hosts files, plain lists, AdBlock, URLs, wildcards
    🤖 Cronjob ready silent mode for automated scheduled runs


## This repo is only public because GitHub charges for private repo minutes after March 2026..

## What this does

- Runs Magpie daily on GitHub's free servers (Thanks Microslop! 😃)
- Creates a blocklist of domains that I then convert to an rpz file for Bind9 using another script.

## All credit goes to:

- ⭐ **[StasonJatham](https://github.com/StasonJatham)** ⭐ ([karl.fail](https://karl.fail/) / [karlcom.de](https://karlcom.de/#home) / [Karl's LinkedIn](https://www.linkedin.com/in/karl-machleidt/)) for his amazing work writing Magpie🙏🙏, hire him NOW! 🫵 
- ⭐ **[Magpie](https://github.com/pigeonsec/magpie)** ⭐ itself – go give it a star! ⭐
- ⭐ **[PigeonSec](http://pigeonsec.com)** ⭐ – Visit PigeonSec's website
- ⭐ **The blocklist maintainers** ⭐ listed in [`sources.txt`](sources.txt) – you do all the real work. We owe you all a massive debt of gratitude. 🙏🙏
- 🤡 **Microslop** 🤡 – for free GitHub Actions minutes.

## License

Magpie is AGPL-3.0 licensed. See the [LICENSE](LICENSE) file for details.
