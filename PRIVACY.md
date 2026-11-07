# DoDodo Privacy Policy

Effective date: 2026-11-02

DoDodo is a browser extension that turns your day into a survival story: you take quests (tasks) by day and stay focused, your finished work earns Grace that you send down to a survivor in the town of Hollowmere, and each night that help becomes their defense against what comes after dark. This policy explains what DoDodo records, where it lives, and how you control it.

## The short version

- DoDodo stores your data **only on your own device**, in your browser's local database (IndexedDB).
- DoDodo **never sends anything over the network**. It makes no requests to any server, ours or anyone else's.
- DoDodo uses **no analytics, no advertising and no third-party services**, and it never loads code from the internet: everything it runs, fonts included, ships inside the extension.
- You can **export** all of your data and **delete** all of it at any time from Settings.

## What DoDodo records

All of the following is stored locally and nowhere else:

- **Your tasks**: the title you type, category, whether it is an offline task, deadline, status, timestamps, and any work-site domains you set for that task.
- **Focus records**: while a task is in progress, DoDodo looks at the active browser tab and records only its **domain name** (for example `docs.example.com`), how that domain was classified (work, distraction, neutral or unclassified), and start and end times. A domain is never stored together with a full URL.
- **Day records**: the result of each day's settlement (what was delivered, missed, and growth earned) and that night's outcome.
- **Your survival progress**: your survivor's name, attributes, health, nights and deaths, the lines of the Residents' Code you have recovered or seen through, the charms they carry, the Grace you have earned, the gifts waiting in the Well of Grace, what you have built onto their house, and which story passages you have already read. The morning letters are written from these records and are not stored separately.
- **Your adventurer** (from earlier versions, if you used them): name, attributes, level and story progress. It is kept unchanged so an earlier version can still read it.
- **Your settings**: end-of-work time, the work and distraction site lists you configure, and onboarding status.
- **Internal state**: the date of the last settled day, the current tracking state, so tracking can resume after the browser restarts, and the most recent error message, shown in Settings to help you diagnose problems.

## What DoDodo does not record

DoDodo never stores full URLs, page titles, page content, search queries, form data, screenshots, keystrokes, or browsing history. It does not read the pages you visit. It only learns the domain of the tab you are looking at, and only while you have a task in progress.

## Why DoDodo asks for browser permissions

- `tabs`: to read the domain of your active tab during a focus session.
- `idle`: to pause focus time when you step away from your computer.
- `alarms`: to keep a once-a-minute heartbeat so focus time stays accurate even when the browser suspends the extension.

DoDodo requests no host permissions and cannot read or change the content of any website.

## Sharing, selling and third parties

DoDodo does not sell, rent, transfer or share your data with anyone, because it never leaves your device. Your data is not used for advertising, profiling, or determining creditworthiness or lending eligibility.

## Your control

In **Settings** you can:

- **Export** all of your data as a file you keep.
- **Delete all data** in one step, after a confirmation. This erases every record listed above from your device.

Uninstalling the extension also removes its local data from your browser. Because DoDodo holds no copy of your data, we cannot recover it for you once it is deleted.

## Children

DoDodo is not directed at children under 13 and does not knowingly collect any information from anyone, since it collects nothing off-device.

## Changes to this policy

If this policy changes, the updated version will be published with a new effective date. Any change that would send data off your device would require a new version of the extension and would be described here first.

## Contact

Contact: harryhaber606@gmail.com
