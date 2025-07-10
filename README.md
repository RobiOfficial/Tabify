# 🌟 Tabify

![Tabify-Logo](https://i.imgur.com/u0CJsYX.png)

**Tabify** is a lightweight and modern **tab list plugin** for Minecraft servers (1.20 – 1.21.7). With support for HEX colors and [PlaceholderAPI](https://www.spigotmc.org/resources/placeholderapi.6245/), Tabify lets you display clean, dynamic messages in your tab list — all through a simple, easy-to-understand config.

---

## ✨ Features

- ✅ **PlaceholderAPI support** (required)
- ⚡ **Lightweight & performance-friendly**
- 🎨 **HEX color support** (`&#rrggbb`, 1.16+)
- 🧾 **Simple and easy-to-use configuration**
- 🧱 Supports **Minecraft 1.20 – 1.21.7**

---

## 📦 Requirements

- **Minecraft Server**: Spigot or Paper (1.20 to 1.21.7)
- **Dependency**: [PlaceholderAPI](https://www.spigotmc.org/resources/placeholderapi.6245/)

---

## 📥 Installation

1. Download the latest release from the [Releases](https://github.com/RobiOfficial/Tabify/releases) tab.
2. Place the `Tabify.jar` into your server's `/plugins` folder.
3. Install PlaceholderAPI if you haven't already.
4. Restart your server.
5. Edit the `config.yml` to customize your tab list.

---

## ⚙️ Configuration Example

```yaml
####################################
#                                  #
#      TABIFY CONFIGURATION        #
#                                  #
####################################

# HEADER SETTINGS

Header: "&a&lLoopify Tablist \n &fWelcome, %player_name% \n &3www.domain.com \n%animations_<shine>------------------------------</shine>%"

# FOOTER SETTINGS
Footer: "%animations_<shine>------------------------------</shine>% \n &7Seconds lived &f- &a%player_seconds_lived% \n &7Health - &c%player_health%"
