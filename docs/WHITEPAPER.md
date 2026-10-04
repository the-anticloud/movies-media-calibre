# Technical Whitepaper — CALIBRE

**Model:** PAX L5 Narrow L2 General 27B
**Company:** Anticloud FZ LLE
**Upstream:** https://github.com/nicedoc/calibre
**Category:** MOVIES_MEDIA

## Abstract

This whitepaper describes the Anticloud integration of `CALIBRE` ((swap) Use: github.com/nicedoc/subsonic — Music/media server)
with PAX L5 Narrow L2 General 27B, the offline-first AI model developed by Anticloud FZ LLE.
The integration produces a zero-cloud, single-binary deployment that exceeds upstream
capabilities while eliminating all third-party API dependencies.

## Technical Improvements

1. PAX L5 Narrow L2 General 27B local script analysis, scene breakdown, and subtitles
2. AIOSS provenance chain for all production assets (C2PA aligned)
3. AES-256 encryption for pre-release content and DCP masters
4. Single-binary media management tool with no cloud dependency
5. Zero-cloud: all AI analysis, transcription, and subtitling run locally
6. GPU/CPU equalizer: video encoding and AI analysis scale to hardware
7. Open DCP/MXF format support replacing proprietary media asset management
8. Offline content delivery: local CDN mirror for on-set distribution

## Architecture

See TECHNICAL/01_Architecture.md for the full architectural description.

## Benchmarks

See OFFICIAL_BENCHMARKS/04_PAX_Results.md for performance targets and measured results.