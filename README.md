# lightweight-red

![GitHub repo size](https://img.shields.io/github/repo-size/iceeyz1/lightweight-red)
![GitHub stars](https://img.shields.io/github/stars/iceeyz1/lightweight-red?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/iceeyz1/lightweight-red)

My **Hyprland dotfiles** with a lightweight red aesthetic.

This setup focuses on keeping things simple and clean while still looking good. It includes configuration for Hyprland and several common tools.

---

## Preview

![screenshot](https://github.com/iceeyz1/lightweight-red/blob/main/screenshots/screenshot.png)

---

## Included Configs

This repository contains configuration for:

- hyprland  
- waybar  
- rofi  
- eww  
- kitty  
- fastfetch  
- cava  
- spicetify  
- htop  

All configs are intended to be placed inside `~/.config`.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/iceeyz1/lightweight-red.git
cd lightweight-red
```

Copy the configs into your `.config` directory:

```bash
cp -r * ~/.config/
```

Or copy specific configs:

```bash
cp -r hypr ~/.config/
cp -r waybar ~/.config/
cp -r rofi ~/.config/
cp -r kitty ~/.config/
```

---

## Dependencies

Install the required programs.

### Pacman

```bash
sudo pacman -S hyprland waybar rofi kitty fastfetch cava htop 
```

### yay (AUR)

```bash
yay -S hyprland waybar rofi kitty fastfetch cava htop spicetify-cli
```

---

## Folder Structure

```text
.config
├── hypr
├── waybar
├── rofi
├── eww
├── kitty
├── fastfetch
├── cava
├── htop
└── spicetify
```

---

## Notes

These dotfiles were created for a personal setup. You may need to adjust:

- monitor configuration  
- keybinds  
- file paths  
- startup programs  

---

## License

MIT License
