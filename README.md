## Download

Go to the Releases section on the right and download the latest version.

# Discord Resolver

Turn your Discord data export into readable chats and find people from your past.

---

## What is this?

Discord exports contain a lot of raw data filled with user IDs instead of real names.
This tool converts those IDs into readable usernames, organizes your chats, and helps you explore your Discord history.

It is especially useful if you want to:

* find old friends you lost contact with
* read old conversations in a clean format
* identify deleted or unknown users
* make sense of your Discord data export

---

## Features

* Resolves Discord IDs → usernames
* Organizes chats into:

  * dms
  * deleted_dms
  * group_dms
  * servers
* Labels deleted users clearly
* Generates readable HTML chat logs
* Search inside chats (HTML)
* Chat statistics (message counts, top contacts)
* Master CSV file of all messages
* Ignore specific users (ignore_ids.txt)
* Optional API support for better name resolution (token.txt)

---

## How it works

1. You request your data from Discord
2. You run this tool on the exported folder
3. The tool:

   * scans all files
   * builds an ID → username map
   * organizes conversations
   * creates readable outputs

---

## Requirements

You only need these folders from your Discord export:

* Account
* Messages
* Servers

---

## Usage

1. Download your Discord data
2. Extract the ZIP file
3. Drag the folder onto `resolver.exe`

After it finishes, two folders will appear:

* `_resolved` → reports and ID mappings
* `_readable` → readable chat logs

---

## Optional: ignore yourself or others

Create a file called:

ignore_ids.txt

Add IDs (one per line):

123456789012345678

---

## Optional: improve name resolution

Create a file:

token.txt

Paste your Discord bot token inside.

This allows the tool to fetch usernames from Discord.

---

## Important

* All files must be in the same folder as the `.exe`
* Do NOT share your token with anyone
* Your Discord export must be extracted before use

---

## Why this exists

Discord exports are hard to read and full of IDs.

This tool makes them human-readable and helps you reconnect with your past conversations.

---

## Disclaimer

This tool processes your local Discord export files only.
No data is sent anywhere.

---

## Download

Go to the Releases section and download the latest version.
