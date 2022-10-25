---
title: "Cara Download File Torrent"
date: 2022-10-26T06:39:00.000Z
draft: false
# tags: ['first']
TocOpen: true
hidemeta: false # show tanggal post
comments: false
description: "Description text coming soon"
# canonicalURL: "https://canonical.url/to/page"
disableHLJS: false # to disable highlightjs
disableShare: false
hideSummary: false # hide preview content di home
searchHidden: false
ShowBreadCrumbs: false # home -> post, sejenis link to page lah
ShowPostNavLinks: false
ShowReadingTime: false
ShowWordCount: true
ShowRssButtonInSectionTermList: true
showToc: true # table of content
UseHugoToc: false # mending false aja
---

Buat lu yang nggapaham cara download .torrent atau pengen download aplikasi tapi males crack IDM, tenang bos, baca dulu dah.

# Requirement

> Ada 3 jalan sebenernya
- Aplikasi GUI
- Aplikasi terminal
- Browser

## Aplikasi GUI
---

### Transmission 
lu coba masuk ke website ini dah buat yang sukanya pake aplikasi bisa di klik2 nih lu masuk ke website [ini](https://transmissionbt.com/download/).

![image - transmission Download](https://i.ibb.co/NTNKjxt/Screen-Shot-2022-10-24-at-13-26-55.png)

Langsung pilih yang .dmg kalau lu pake mac, atau pilih yang x86.msi kalau lu pake windows 32-bit, atau x64.msi kalau lu pake windows 64-bit, searching sendiri da gimana caranya tau lu pake windows 64 atau 32 bit, atau ya kapan2 bakal gua bikin tutorialnya kalau gua pegang windows

### bittorent
ada aplikasi yang gua saranin selanjutnya yaa bittorent 
>note : yang pernah pake utorrent, mending [uninstall sekarang](https://www.reddit.com/r/torrents/comments/kj22c7/comment/ggu9326/?utm_source=share&utm_medium=web2x&context=3) deh

langsung aja ke [sini](https://www.bittorrent.com/products/),
kalau web :

![image - bittorent download](https://i.ibb.co/1bGRhRF/Screen-Shot-2022-10-24-at-13-31-06.png)

kalau applikasi coba download sendiri aja ya tuh, ngga kompatibel sama OS gua soalnye



## Aplikasi Terminal
---

### Aria2c

Pertama lu kenalan dulu sama kawan gua [brew.sh](http://brew.sh) bah ini the best banget kalau lu mau package manager(CMIIW) ya sejenis YAY di linux,

Atau lu buka terminal lu sekarang, trus paste code ini

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Abis itu banyak2 doa dan belajar bahasa inggris dikit2 ye biar paham si script itu nanya apa ke elu, lu searching da cara install brew itu,

Kalau udeh lu install brew, sekarang lu install aria2 di terminal lu lagi

```bash
brew install aria2
```

Tunggu sampe selesai, nanti kalau udah lu coba test pake line ini di terminal lu lagi

```bash
aria2c
```

![Screenshot aria2c](https://i.ibb.co/C5xCWPg/Screen-Shot-2022-10-24-at-14-14-52.png)

Kalau muncul kaya gini, Selamat! lu da berhasil ikutin tutorial yang sederhana banget.

### Browser
---

### Brave browser
**Disclaimer : Bukan iklan**

Langsung download di [website](https://brave.com/) resminya

![Image - downloadb brave](https://i.ibb.co/028qnQ7/Screen-Shot-2022-10-24-at-14-18-36.png)


# Cara download torrent


Sekarang lu udah punya tools nih ye, sekarang lanjut ke cara download file torrent

### Pake Aria2c
---

1. Paste link ke terminal kaya gini

```bash
aria2c 'www.linkyangmauludownload.com'
```

Nih contoh nyatanya : 

```bash
aria2c 'https://github.com/aria2/aria2/releases/download/release-1.36.0/aria2-1.36.0.tar.xz'
```

Karena tadi kita bahas .torrent, oke kita searching ye torrent yang asik

Dislaimer : Karena kondisi bisa beda2, gua ngga include screenshoot yak

2. Searching piratebay di searchengine (kena blokir? nanti di post lain gua bakal kasih tau cara unblocknya)
3. Lu searching di piratebay itu mana yang mau lu download
4. Lu pilih file yang mau lu download dan pilih ‘GET THIS TORRENT’ atau kalau ada sih ‘MAGNET LINK’ tapi lu copy link nya yak jangan lu klik tombolnya
5. Lu buka terminal, trus ke folder yang mau lu tuju misalkan

```bash
cd Download
```

6. Trus lu jalanin script aria2c ‘link’, misalkan :

```bash
aria2c 'magnet:?xt=urn:btih:5A6194C4E92A459A1313B7A4E9F7A9EB18FB9205&dn=Spider-Man%20No%20Way%20Home%20(2021)%20720p%20English%20Pre-DVDRip%20x264%20AAC%202&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.openbittorrent.com%3A6969%2Fannounce&tr=udp%3A%2F%2F9.rarbg.to%3A2710%2Fannounce&tr=udp%3A%2F%2F9.rarbg.me%3A2780%2Fannounce&tr=udp%3A%2F%2F9.rarbg.to%3A2730%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337&tr=http%3A%2F%2Fp4p.arenabg.com%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.torrent.eu.org%3A451%2Fannounce&tr=udp%3A%2F%2Ftracker.tiny-vps.com%3A6969%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce'
```

Selesai da, tinggal lu tunggu, nanti kalau udah kelar lu jangan lupa CTRL + C atau COMMAND + C kalau di mac buat keluar dari seedingnya, atau kalau lu mau seeding sih sippp biar yang laen bisa download juga (searching dah lu istilah seeding itu apa)

### Pake GUI atau browser
---

1. Buka situs torrent (pirate bay, 1337x, atau sejenisnya)
2. Pilih file yang di pingin
3. Pilih magnet link
4. Nanti tinggal add atau mulai aja di aplikasi torrent lu

# NOTE
> Disarankan yang SE (Seeders)-nya tinggi ya, kalau LE(Tinggi disarankan yang rendah), pokonya utamakan yang seedersnya paling banyak, Karena selain lebih aman (banyak yang host/download) kecepatan downlad jadi lebih tinggi

![Image seeders leechers](https://i.ibb.co/L9qt6v9/Screen-Shot-2022-10-24-at-14-28-16.png)

---

Udeh gitu doang, gua prefer aria2 sih soalnya asik banget, modal script di terminal tinggalin da, ntar kelar sendiri.

NOTE : Gua sengaja pake Table of content buat tulisan panjang apalagi instruksi detail kaya gini, biar gampang lu pada bacanya

NOTE LAGI : Kalau lu seneng konten gua, dan mau bikin gua semangat sama tulisan gua kedepannya, gas [kesini](https://sociabuzz.com/muezzaissleeping)

