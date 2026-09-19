# Onocoy Monitor

## Table of Contents

- [Overview](#overview)
  - [How It Works](#how-it-works)
  - [Features](#features)
  - [Screenshot](#screenshot)
- [Usage](#usage)
- [Configuration](#configuration)
- [Links](#links)
- [Author](#author)

## Overview

Onocoy Monitor Desklet is a simple Cinnamon desklet that displays the live status of your Onocoy reference station / node directly on your desktop, using the Onocoy public monitoring API.

[Onocoy](https://onocoy.com) is an open GNSS data marketplace that connects RTCM 3 / NTRIP-compliant reference stations to a global, community-powered RTK correction network. With this desklet, station operators can keep an eye on their node without having to open the web console.

### How It Works

- The desklet periodically polls the Onocoy monitoring endpoints for your station / account.
- Status information (online / offline, last seen, data quality, location) is rendered as a compact desklet on the desktop.
- The display refreshes automatically at a configurable interval.

### Features

- Live status of your Onocoy reference station on your desktop.
- Automatic background refresh.
- Compact, themable layout that fits the Cinnamon look and feel.
- Easy configuration through the desklet settings menu.
- Visual look tweaks (size, colors, displayed fields).

### Screenshot

[![Screenshot](https://github.com/airtkey/cinnamon-spices-desklets/raw/master/onocoy-monitor%40alexmm/files/onocoy-monitor@alexmm/screenshot.png)](/airtkey/cinnamon-spices-desklets/blob/master/onocoy-monitor%40alexmm/files/onocoy-monitor@alexmm/screenshot.png)

## Usage

1. Add the Onocoy Monitor Desklet to your desktop via the "Add Desklets" menu in Cinnamon.
2. Open the desklet settings and enter your Onocoy account / station identifier.
3. The desklet will start polling the Onocoy API and display the current status of your node.
4. Configure the desklet's settings — appearance, refresh interval, displayed fields, and other preferences — through the settings menu. This allows you to customize the desklet to suit your needs and preferences.

## Configuration

Currently, the desklet supports monitoring of a single Onocoy reference station. The following options are available in the settings menu:

- Station / account identifier — the Onocoy reference (e.g. station ID or account handle) you want to monitor.
- Refresh interval — how often the desklet polls the Onocoy API for updated data.
- Display options — choose which status fields are shown and how they are laid out.
- Visual tweaks — adjust size, colors and overall look to match your desktop theme.

Future versions will add desktop notifications (e.g. when a station goes offline), multi-station support, and additional metrics from the Onocoy monitoring API.

If you have any ideas for new features, please feel free to ask me to add them!

## Links

- Website - [airtkey.xyz](https://airtkey.xyz)
- Onocoy - [https://onocoy.com](https://onocoy.com)
- Onocoy Docs - [https://docs.onocoy.com](https://docs.onocoy.com)
- Onocoy Console / Explorer - [https://console.onocoy.com/explorer](https://console.onocoy.com/explorer)
- Onocoy Discord - [Join the Onocoy community](https://discord.com/invite/CHKxSpPQ8p)

## Author

Tech Ambassador at Onocoy

- GitHub - [@airtkey](https://github.com/airtkey)
- LinkedIn - [Alexander Gretz](https://www.linkedin.com/in/alexander-gretz-depin/)
- X / Twitter - [@AlexMultiMining](https://x.com/AlexMultiMining)
- Website - [airtkey.xyz](https://airtkey.xyz)
