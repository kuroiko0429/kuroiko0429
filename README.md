<!-- Header -->
<div align="center">

```
██╗  ██╗██╗   ██╗██████╗  ██████╗ ██╗██╗  ██╗ ██████╗
██║ ██╔╝██║   ██║██╔══██╗██╔═══██╗██║██║ ██╔╝██╔═══██╗
█████╔╝ ██║   ██║██████╔╝██║   ██║██║█████╔╝ ██║   ██║
██╔═██╗ ██║   ██║██╔══██╗██║   ██║██║██╔═██╗ ██║   ██║
██║  ██╗╚██████╔╝██║  ██║╚██████╔╝██║██║  ██╗╚██████╔╝
╚═╝  ╚═╝ ╚═════╝ ╚═╝  ╚═╝ ╚═════╝ ╚═╝╚═╝  ╚═╝ ╚═════╝
```

**`If it doesn't work, fix it. If it doesn't exist, build it.`**

[![GitHub followers](https://img.shields.io/github/followers/kuroiko0429?style=flat-square&color=a89984&labelColor=282828)](https://github.com/kuroiko0429)
![Profile views](https://komarev.com/ghpvc/?username=kuroiko0429&style=flat-square&color=a89984&labelColor=282828)

</div>

---

## `$ whoami`

```fish
> kuroiko --info

  role      : CS student / tinkerer / terminal dweller
  os        : CachyOS (Arch-based) + Hyprland
  machine   : Panasonic Let's Note SV1
  editor    : Neovim
  shell     : fish + zsh
  theme     : Gruvbox (always)
  interest  : Linux / Security / TUI / Go / Python
```

- 動かないものは直す。存在しないものは作る。
- ターミナルが主戦場。GUIより速いと本気で思っている。
- システムと深く統合された「使い続けられるツール」を作るのが好き。
- セキュリティの攻守両面を実践的に学習中。

---

## `$ ls ~/projects`

### 🖥️ [Tail-Pulse](https://github.com/kuroiko0429/tail-pulse.git)
> Tailscaleネットワーク内の全デバイス監視TUI — Watch Dogs風デザイン

`Go` `Bubble Tea` `Lip Gloss`

- Pingレイテンシ測定 + スパークライン可視化
- SSH自動検出 & Enterキーで即接続
- OSごとのアイコン / ダイレクト・リレー接続判別

---

### 📅 [daigaku-calendar](https://github.com/kuroiko0429/daigaku-calendar)
> 大学時間割をYAMLで管理してsystemdデーモンで授業前通知を飛ばすツール

`Python` `systemd` `YAML`

- 授業N分前にデスクトップ通知
- 前後期切り替え / 祝日対応
- **現在も毎日稼働中**

---

### 🖱️ [wheelpad-daemon](https://github.com/kuroiko0429/let-s-note-SV1-wheelpad.git)
> Wayland/Hyprland環境でPanasonic Let's Noteのホイールパッドを動かすPythonデーモン

`Python` `evdev` `systemd`

- メーカー非対応のWayland環境でevdevを直接操作して実装
- 慣性スクロール / 水平スクロール / 速度動的調整
- `config.toml`でカスタマイズ可能
- `wheelpad.service`として常駐稼働中

---

### 🚬 [iqos-tracker](https://github.com/kuroiko0429/iqos-tracker.git)
> IQOS消費量トラッキングTUI — ターミナル愛好家のために作った

`Python` `Textual` `SQLite3`

- Vimライクな操作 / テーマのホットスワップ（Gruvbox / Nord / TokyoNight）
- Waybarへのリアルタイム連携（JSON出力）
- Zsh TAB補完 / デスクトップ通知 / Sparklineグラフ

---

### 📰 [johodai-news-cli](https://github.com/kuroiko0429/johodai-news-cli)
> 大学ポータルのニュースをCLIで取得 + カレンダー連携するツール

`Go` `iCal`

---

## `$ cat ~/.config/skills`

**Languages**

![Python](https://img.shields.io/badge/Python-282828?style=flat-square&logo=python&logoColor=a89984)
![Go](https://img.shields.io/badge/Go-282828?style=flat-square&logo=go&logoColor=83a598)
![Rust](https://img.shields.io/badge/Rust-282828?style=flat-square&logo=rust&logoColor=d65d0e)
![JavaScript](https://img.shields.io/badge/JavaScript-282828?style=flat-square&logo=javascript&logoColor=fabd2f)
![Lua](https://img.shields.io/badge/Lua-282828?style=flat-square&logo=lua&logoColor=458588)
![Java](https://img.shields.io/badge/Java-282828?style=flat-square&logo=openjdk&logoColor=b8bb26)

**Infrastructure / Tools**

![Linux](https://img.shields.io/badge/Linux-282828?style=flat-square&logo=linux&logoColor=fabd2f)
![Docker](https://img.shields.io/badge/Docker-282828?style=flat-square&logo=docker&logoColor=83a598)
![Neovim](https://img.shields.io/badge/Neovim-282828?style=flat-square&logo=neovim&logoColor=b8bb26)
![Tailscale](https://img.shields.io/badge/Tailscale-282828?style=flat-square&logo=tailscale&logoColor=d3869b)
![Nix](https://img.shields.io/badge/Nix-282828?style=flat-square&logo=nixos&logoColor=458588)
![Git](https://img.shields.io/badge/Git-282828?style=flat-square&logo=git&logoColor=fe8019)

**Security**

![Metasploit](https://img.shields.io/badge/Metasploit-282828?style=flat-square&logo=metasploit&logoColor=cc241d)
![Wireshark](https://img.shields.io/badge/Wireshark-282828?style=flat-square&logo=wireshark&logoColor=83a598)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-282828?style=flat-square&logo=burpsuite&logoColor=fe8019)

---

## `$ systemctl --user list-units --state=running`

```
dcal.service        ← 自作 大学カレンダーデーモン       [active]
wheelpad.service    ← 自作 Let's Note ホイールパッド    [active]
tailscaled.service  ← VPN メッシュネットワーク          [active]
docker.service      ← Minecraft SMP サーバー           [active]
```

---

## `$ git log --oneline --graph`

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=kuroiko0429&show_icons=true&theme=gruvbox&hide_border=true&bg_color=282828&title_color=fabd2f&icon_color=d79921&text_color=ebdbb2)](https://github.com/kuroiko0429)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=kuroiko0429&layout=compact&theme=gruvbox&hide_border=true&bg_color=282828&title_color=fabd2f&text_color=ebdbb2)](https://github.com/kuroiko0429)

</div>

---

## `$ cat /proc/interests`

```yaml
currently_learning:
  - Rust (systems programming)
  - Elixir (functional paradigm)
  - Embedded (Arduino / PlatformIO)

hobbies:
  - Linux ricing (Hyprland dotfiles)
  - CTF / security research
  - 3D printing (BambuLab)
  - Minecraft SMP server admin
  - Sonic Pi (live coding music)
  - Blue Archive 🎮

philosophy: |
  ターミナルは世界への窓。
  ツールは自分で作れ。
  動かないなら直せ。
```

---

<div align="center">

```
 ／￣￣￣＼
│ ^　 ^ │    "ls -la ~/ shows who you really are"
│  ∪  │
 ＼___／
```

[![](https://img.shields.io/badge/Arch_btw-CachyOS-282828?style=flat-square&logo=archlinux&logoColor=1793d1)](https://cachyos.org)

</div>
