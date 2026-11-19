<img src="banner.png" alt="Submersion: Dive safe. Log everything." width="100%">

**Submersion** is a free, open source dive log for recreational and technical
divers. Download your dive computer, analyse the profile and decompression,
plan your next dive with the gas you actually have, and keep your whole
logbook on your own hardware.

It runs on iOS, Android, macOS, Windows, Linux and in the browser.

[Website](https://submersion.app) ·
[Web app](https://web.submersion.app) ·
[User guide](https://submersion.app/guide/) ·
[Download](https://github.com/submersion-app/submersion#download)

## Repositories

### The app

| Repository | What it is for |
| --- | --- |
| [submersion](https://github.com/submersion-app/submersion) | The app itself, built with Flutter. Source code, issues, discussions and stable releases all live here. **Start here.** |

### Data the app downloads

| Repository | What it is for |
| --- | --- |
| [site-catalogue](https://github.com/submersion-app/site-catalogue) | The built-in catalogue of about 21,000 dive sites, wrecks and artificial reefs. Holds the source fetchers, the merge, researched sites with their evidence, and the releases the app ships. |
| [species-pack](https://github.com/submersion-app/species-pack) | The model pack behind on-device marine life identification. Holds the pipeline that builds and checks the pack; its releases are what the app downloads. |

### Dive computers

| Repository | What it is for |
| --- | --- |
| [libdivecomputer](https://github.com/submersion-app/libdivecomputer) | Submersion's fork of [libdivecomputer](https://www.libdivecomputer.org/), the library that talks to 350+ dive computers. The app's patches live on the [`submersion-patches`](https://github.com/submersion-app/libdivecomputer/tree/submersion-patches) branch. |

### Builds and hosting

| Repository | What it is for |
| --- | --- |
| [beta-builds](https://github.com/submersion-app/beta-builds) | Beta builds, published after every green merge to the app's `main` branch. Newest features first; a beta may upgrade your dive log ahead of the stable release. |
| [web](https://github.com/submersion-app/web) | The browser build served at [web.submersion.app](https://web.submersion.app). Deployed automatically from the app repository; do not edit it directly. |
| [submersion-website](https://github.com/submersion-app/submersion-website) | The [submersion.app](https://submersion.app) website, including the landing pages for cylinder and gear tags. |

## Get involved

Bug reports, feature requests and dive computer reports all go to the
[app's issues](https://github.com/submersion-app/submersion/issues). See the
[contributing guide](https://github.com/submersion-app/submersion/blob/main/CONTRIBUTING.md)
to help build it.
