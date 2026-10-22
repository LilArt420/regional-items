# 🌏 Regional Items

A Ragnarok Offline mod that gives your client the names, descriptions and icons of items from other servers' clients (kRO, bRO, jRO, …) that your server knows but your client doesn't, so they stop showing as **Unknown Item** 🔍 Renewal only.

## 🌟 What It Adds
- 🇰🇷 **kRO-only items** (237): English names and descriptions, translated from kRO's text. Their sprites come from your kRO fallback GRF.
- 🇺🇸 **iRO's wording** for the 8 official items that follow iRO's descriptions (Fifth Element, Mask of Ifrit, Valkyrie Curse Blight, …).
- 🏷️ **No more "Unknown Item"** for 3,582 items the server has but no client table on your computer names (e.g. jRO's Ancient Royal Scepter 550095): a name, an icon and a description of what the item does.

Client text only: the items themselves come with the server (Ragnarok Offline 1.6.4 and later).

## 💾 Installing
In Ragnarok Offline: **Settings → Mods → Find Mods → regional-items → Install**.
When a new release is out, the Mods tab shows **Update available** 🔔

You can also download `regional-items-v<version>.zip` from the [Releases](../../releases) page and install it with **Install from a folder…**

## 📜 Changes
See [`regional-items/CHANGELOG.md`](regional-items/CHANGELOG.md).

## 🛠️ For Developers
- `regional-items/` is the mod exactly as it installs.
- Every pull request runs [`validate.yml`](.github/workflows/validate.yml): `mod.json`, every YAML file (rapidyaml), the CHANGELOG section for the version, the release zip's layout, and an rAthena map-server `--run-once` with the mod loaded.
- Publishing a GitHub release tagged `v<version>` builds `regional-items-v<version>.zip` and attaches it ([`release.yml`](.github/workflows/release.yml)); the app's mod registry picks it up from there.

## ⚖️ License
GPL-3.0, like rAthena. Item names and descriptions come from Gravity's official clients.
