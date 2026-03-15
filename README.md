# AdGuard Home Allowlists

This repository contains DNS allowlists intended for use with AdGuard Home (and other DNS-based blockers such as Pi-hole). These lists are designed to fix broken functionality when aggressive blocking interferes with legitimate services.

## Contents

- General allowlists for:
  - Whitelists major mobile in‑game ad providers (Unity Ads, AppLovin, ironSource/Supersonic, AdMob/Google Ads, Chartboost).
  - Intended for use **only on specific clients** (e.g. phones/tablets) where rewarded ads are required to function.

## Usage

1. Host a list from this repo directly via its **raw GitHub URL**, for example:

   ```text
   https://raw.githubusercontent.com/<your-username>/adguard-allowlists/main/mobile-game-ads-allowlist.txt
