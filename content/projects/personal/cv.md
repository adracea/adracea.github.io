---
title: "Crunchyview"
draft: false
toc: false
images:
date: "2023-10-28"
tags:
---

## Story

Crunchroll's APIs,UI and UX are horrendous. At the time I was watching Anime and wanted to also dabble in rust. This angered me to the point where I decided to use crunchyroll-cli to download the episodes for offline watching as a better experience.
The cli is based off of crunchyroll-rs, a rust based reverse engineered API client library for Crunchyroll's horrible APIs, it accounts for a lot of the errors in the UX of Crunchyroll. After contributing to both the CLI and the library, I had enough rust knowledge (or so I thought) to write my own GUI based viewer app using Tauri & Yew (WASM).

## About

This is a fairly minimalistic application that allows for interacting with Crunchyroll through a GUI. I was feeling adventurous enough to build a web-based frontend using only rust.
Tauri is a rust-based, super lightweight alternative to Electron. So it works with javascript frontends mostly.
Yew is a rust-based WASM framework in which you can write only rust code and do away with javascript...nearly completely...as long as you keep it simple...and don't need javascript libraries...that aren't fairly complex themselves...and not directly bindable to rust wasm...

Right now Crunchyview is just a learning project where I'm exploring and expanding my own skills. It should be still hopefully usable?