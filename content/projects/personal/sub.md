---
title: "rsubs-lib"
draft: false
toc: false
images:
tags:
 - project
 - library
 - personal
---

## How it came to be

Initially started contributing to crunchyroll-cli/crunchyroll-rs as my experience with Crunchyroll had been lacking. This was a stepping stone in my Crunchyview project that I needed as there were no rust libraries providing a way of working with subtitles aside from basic conversions that lacked customization or even all the basic functionality.

## About

The project is meant to provide functionality for working with 3 widely used subtitle formats:
- SSA(SubStation Alpha/Advanced SubStation)
- WebVTT
- srt

WebVTT and SSA both incorporate various advanced styling and features which most other libraries were ignoring and/or setting to default which could mangle certain subtitles. rsubs-lib on the other hand accepts and transpiles the styling and allows you to add your own programmatically.
It also provides full functionality for tuning subtitles timings, positions, etc.

## Rsubs

This is an upcoming project that I'm still thinking on due to...well...at the time of writing this, the answer to https://areweguiyet.com/ being "sort of but you hit your head on walls quite often".
The idea would be to make an application for working with subtitles that is based off of rsubs-lib. I've tested a few GUI frameworks but I still haven't set my mind on one yet.