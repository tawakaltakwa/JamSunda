# JamSunda
Ngaran jam dina basa sunda

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

## penggunaan
jamsunda.sh defaultna nampilkeun jam jeung ngaran jam bisa di coba di terminal 
bash jamsunda.sh
format 12 jam
bash jamsunda.sh -f 12
nampilkeun poe
bash jamsunda.sh -p
nampilkeun tanggal
bash jamsunda.sh -t
campukeun sadayana
bash jamsunda.sh -t -p -f 12

jamsunda_info.sh nampilkeun harti ti ngaran poe dina notifikasi butuh sajenis aplikasi `mako`
