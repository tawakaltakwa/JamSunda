# JamSunda
Ngaran jam dina basa sunda

bisa dipake di waybar
"custom/jamsunda": {
        "format" : "{text}",
        "tooltip": true,
        "tooltip-format": "Jam Sunda",
        "interval": 60,
        "exec" : "bash ~/.config/waybar/jamsunda.sh -p -t",
        "on-click" : "bash ~/.config/waybar/jamsunda_info.sh"
}
