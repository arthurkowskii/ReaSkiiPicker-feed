# ReaSkii Picker feed

Public ReaPack repository for ReaSkii Picker, a visual FX browser for REAPER.

## Install or update

In REAPER, open `Extensions > ReaPack > Manage repositories`, import this URL:

```
https://raw.githubusercontent.com/arthurkowskii/ReaSkiiPicker-feed/main/index.xml
```

Then install `ReaSkii Picker` from `Extensions > ReaPack > Browse packages`. The script is added to the Action List automatically.

After the first install, update it with `Extensions > ReaPack > Synchronize packages`.

## Pre-releases

Versions carrying a suffix such as `-alpha` are ReaPack pre-releases. They appear in `Browse packages`, but automatic upgrades to newer pre-releases require enabling pre-release installation in ReaPack's options. Numeric versions are treated as stable.

ReaImGui 0.10 or newer is required. It is available from the default ReaTeam Extensions repository.

## What this repository contains

Built runtime files and the ReaPack index only. The source repository is private and the code is not open source. No personal data, plugin library or preview image is published here: `library.json` and the previews stay in the REAPER resource folder and are never part of this feed.

The feed is regenerated from a verified release asset by a GitHub Actions workflow.
