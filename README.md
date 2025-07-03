# JamSunda

Ngaran jam dina basa sunda.

## referensi istilah

Kuring oge budak jaman ayeuna teu apal detil, nanya kolot jeung tatangga oge ngan aya sa'eutik istilah, ieu nu manggih tina internet ref1 jeunh ref2 sajenis, ref3 rada beda. Asana emang wajar urang sundana oge beda-beda daerah, sok aya beda saeutik. sok remen baheula ngadenge tangange, aya di ref1/ref2 tapi euweuh di ref3, kulantaran kuring leuwih sering ngadenge ti ref1/ref2 jadi we nulis script utamana berdasar ref1/ref2. <br/>

- [ref1](https://www.facebook.com/aksarasastradanbudayasunda/posts/waktu-menurut-ki-sundawaktu-dalam-bahasa-sunda-disebut-dengan-kata-wanci-dan-man/303297150182867/)  

- [ref2](https://www.goodnewsfromindonesia.id/2020/06/12/tak-pakai-angka-ini-cara-orang-sunda-menyebut-waktu-sehari-semalam)  

- [ref3](https://www.sukabumiupdate.com/life/126191/24-istilah-waktu-dalam-bahasa-sunda-wanci-sariak-layung)

## penggunaan

bisa dipake di waybar, contoh di waybar config (.config/waybar/config)

```
"custom/jamsunda": {
        "format" : "{text}",
        "tooltip": true,
        "tooltip-format": "Jam Sunda",
        "interval": 60,
        "exec" : "bash ~/.config/waybar/jamsunda.sh -p -t",
        "on-click" : "bash ~/.config/waybar/jamsunda_info.sh"
}
```

screenshot waybar jeung mun di klik bijil notifikasi:<br/>
![](/Screenshot1.png)

[](/jamsunda.sh) defaultna nampilkeun jam jeung ngaran jam bisa di coba di terminal 

```
bash jamsunda.sh
```

format 12 jam

```
bash jamsunda.sh -f 12
```

nampilkeun poe

```
bash jamsunda.sh -p
```

nampilkeun tanggal

```
bash jamsunda.sh -t
```

bisa dicampurkeun sadayana

```
bash jamsunda.sh -t -p -f 12
```

jamsunda_info.sh nampilkeun harti ti ngaran poe dina notifikasi, mun make windows manager biasana butuh sajenis aplikasi `mako`<br/>

jamsunda2.sh jeung jamsunda_info2.sh, fungsi jeung gunana sami, pedang ngango istilah tina ref3.

## hiburan

istilah Bayeungyang

> mencrangna panas Bayeungyang

[Darso - Kembang Cinta](https://www.youtube.com/watch?v=kLYSby8U6Bo)<br/><br/>
istilah Balebat

> tuh Balebat... geuning geus katembong caang

[Darso - Balebat](https://www.youtube.com/watch?v=F9mksOPjYB4)<br/><br/>
istilah Kongkorongok Hayam

> hayam jalu geus kongkorongok, panon poe tereh bijil

[Doel Sumbang - Ema](https://www.youtube.com/watch?v=GHqfS_4RGyg)
