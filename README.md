# Scoop SpotX Bucket (Unofficial)

<!-- Uncomment the following line after replacing placeholders -->
[![Tests](https://github.com/ast3risk-ops/spotx-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/ast3risk-ops/spotx-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/ast3risk-ops/spotx-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/ast3risk-ops/spotx-bucket/actions/workflows/excavator.yml)

>[!NOTE]
>I don't use Windows anymore, so I can no longer directly test this bucket. The Actions system will automatically resolve hash errors if you file an issue through the link provided by Scoop. I will also continue to maintain this repository and fix issues that are reported.

## What's different?

Nobody merged a PR to fix `spotx-np` in nonportable, so here we are. On a user's suggestion I also added in a tweak from the `spotify` package that preserves user settings on update.

## How do I add this manifest and install spotx?

Run the following:

```bash
scoop bucket add spotx-bucket https://github.com/ast3risk-ops/spotx-bucket
scoop install spotx-bucket/spotx
```
