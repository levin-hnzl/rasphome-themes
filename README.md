# 🏠 RaspHome – A Modern Home Assistant Theme

**RaspHome** ist ein stilvolles, modernes und dunkles Home Assistant Theme mit warmen Farbtönen, ideal für ein elegantes Dashboard-Erlebnis – besonders auf Raspberry Pi Setups optimiert.



## ✅ Features

- Sanftes, kontrastreiches Dark Theme
- Gut lesbare Schriftfarben
- Dezente Transparenzeffekte
- Ideal für Wandtablets, Desktops oder Smartphones
- Raspberry-Pi-freundlich (leichte Darstellung)

---

## 🚀 Installation

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=levin-hnzl&repository=rasphome-themes&category=theme)

### 1. Theme-Datei herunterladen

Lade die Datei `rasphome.yaml` herunter und platziere sie im Ordner `/config/themes/`.

### 2. `configuration.yaml` anpassen

```yaml
frontend:
  themes: !include_dir_merge_named themes
