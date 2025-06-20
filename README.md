# JamSunda
Ngaran jam dina basa sunda, sok aya geuningan istilah kolot nyebut janari, tangange tawa, sajenis nu kararitu.

bisa dipake di waybar
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
screenshot
![](/Screenshot1.png)

## penggunaan
jamsunda.sh defaultna nampilkeun jam jeung ngaran jam bisa di coba di terminal 
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

jamsunda_info.sh nampilkeun harti ti ngaran poe dina notifikasi butuh sajenis aplikasi `mako`

## referensi istilah
kuring oge budak jaman ayeuna teu apal detil, nanya kolot jeung tatangga oge ngan aya sautik, ieu nu manggih tina internet ref1 jeunh ref2 sajenis, ref3 rada beda. Asana emang wajar urang sundana oge beda-beda daerah, sok aya beda saeutik. kuring mah leuwih sering ngadenge ti ref1/ref2 jadi we nulis scriptna berdasar ref1/ref2. bilih aya nu sok leuwih sering ngadenge istilah ti ref3 manga edit we nyalira.
[ref1](https://www.facebook.com/aksarasastradanbudayasunda/posts/waktu-menurut-ki-sundawaktu-dalam-bahasa-sunda-disebut-dengan-kata-wanci-dan-man/303297150182867/)
[ref2](https://www.goodnewsfromindonesia.id/2020/06/12/tak-pakai-angka-ini-cara-orang-sunda-menyebut-waktu-sehari-semalam)
[ref3](https://www.sukabumiupdate.com/life/126191/24-istilah-waktu-dalam-bahasa-sunda-wanci-sariak-layung)
