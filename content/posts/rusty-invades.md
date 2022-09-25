---
title: "Rusty Invades"
date: "2021-04-11"
tags: ["game", "rust"]
author: "Nicolas Cesar Sabbatini Vrech"
showToc: true
TocOpen: false
draft: false
hidemeta: false 
comments: false
description: "A 'Space Invader' clone made with rust and made for the terminal."
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: false
ShowPostNavLinks: true
editPost:
    URL: "https://github.com/NicolasSabba/rusty-invades"
    Text: "Suggest Changes"
    appendFilePath: false
---
# Rusty Invades
> [Source Code](https://github.com/NicolasSabba/rusty-invades)

A 'Space Invader' clone made with rust and made for the terminal.

Inspired by [invaders](https://github.com/CleanCut/invaders)

## Dependencies on Linux

Audio should work out-of-the-box on macOS, Windows, and iOS. For Linux, the downstream package for actually playing
sound requires the Alsa development libraries to be installed.

### CentOS

```shell
sudo yum install -y alsa-lib-devel
```

### Debian/Ubuntu

```shell
sudo apt install libasound2-dev pkg-config
```

### License

[ Apache License (Version 2.0).](https://github.com/NicolasSabba/rusty-invades/blob/main/LICENSE)

### TODO

⬜ UI.  
✅ Score.  
✅ Lives.  
⬜ Multiple levels.  
⬜ Power ups.  
⬜ Make bullets entities.  

### Run Linux

1. Download binary.
2. Extract.
3. Open directory in terminal.
4. Run ./rusty-invades
