# Pitwall Remote

Pitwall Remote is an Android app to follow and drive the coding sessions that run on your computer through pitwall, from anywhere.

- A general chat that starts sessions in your projects for you.
- Search: find any chat by the words in its title, last message, project or folder.
- Every project and conversation, newest first, with what the agent reads, writes and runs, its sub-agents and a live view of its terminal.
- Permission prompts, questions and plans, answered from your phone with one tap.
- Quick actions for running sessions: send a message, send it at once, stop the current turn.
- Photos and files: attach them to a message and the agent reads them on your computer.
- Several computers: pair with one and switch to the others of the same pitwall network from the header.
- Push notifications when a session needs you or has finished its work.
- Dictation: hold the mic and talk, or tap it to talk hands-free.
- Voice mode (optional): say a wake phrase, even with the phone locked, and talk with the General chat on your computer in a full-screen voice mode; interrupt it by talking, and it answers out loud (a realistic ElevenLabs voice if you set one up on the computer).
- Account usage, cooldowns and the next account to be used.
- English and Spanish, light and dark themes.

## Download

Get the latest APK from [Releases](https://github.com/ParendumOU/pitwall-remote/releases). It is signed by Parendum: install each new version over the previous one to update.

## Requirements

- A computer running `pitwall mobile`, reachable from the phone over Wi-Fi, a VPN or Tailscale.
- Pair the phone once: run `pitwall mobile pair` on the computer and scan the code with the app. The code carries every address of the computer, and the app uses the one that answers.
- For push notifications, set up Firebase on each computer with `pitwall mobile push setup`.

## Source code

This repository only holds the release downloads. The source code is not public.
