<div align="center">

# 🚀 Gemini Terminal for Home Assistant

### *AI-Powered Terminal Assistant directly in your Dashboard*

[![Version](https://img.shields.io/github/v/release/oded996/gemini-cli-home-assistant-addons.svg?style=for-the-badge)](https://github.com/oded996/gemini-cli-home-assistant-addons)
[![License](https://img.shields.io/github/license/oded996/gemini-cli-home-assistant-addons.svg?style=for-the-badge)](LICENSE)

**Integrate Google's Gemini CLI with Home Assistant for intelligent control and configuration.**

[Installation](#-installation) • [Features](#-features) • [Documentation][docs]

---

</div>

## ✨ About

**Gemini Terminal** brings the powerful [Gemini CLI](https://github.com/google/gemini-cli) directly into your Home Assistant instance. Experience intelligent configuration editing, system troubleshooting, and direct entity control through natural language and the Model Context Protocol (MCP).

### 🎯 Key Features

<table>
<tr>
<td width="50%">

#### 🤖 **Google Gemini CLI**
Access a full terminal via your browser with the official Gemini CLI pre-installed, providing a powerful AI-driven environment.

#### 🔌 **Home Assistant MCP**
Pre-installed `ha-mcp` server allows Gemini to natively read states, call services, and interact with your entities through natural language.

#### 🛡️ **Session Persistence**
Built-in `tmux` support ensures your conversations and terminal sessions persist, even if you navigate away or refresh the page.

</td>
<td width="50%">

#### 🧠 **Smart Context**
Automatically generates a `GEMINI.md` context file with your system info, architecture, and recent logs so Gemini understands your environment immediately.

#### 🔐 **Auto-Authentication**
Supports `GEMINI_API_KEY` configuration via the add-on UI for headless, persistent login.

#### 📁 **Direct Config Access**
Starts directly in your `/config` directory for easy YAML editing and troubleshooting.

</td>
</tr>
</table>

---

## 📦 Installation

### Quick Install

1. **Add this repository to Home Assistant:**

   [![Add Repository][repo-btn]][repo-add]

   <details>
   <summary>Or add manually</summary>
   
   Go to **Settings** → **Add-ons** → **Add-on Store** → **⋮** → **Repositories**
   
   Add: `https://github.com/oded996/gemini-cli-home-assistant-addons`
   </details>

2. **Install the add-on:**
   - Find **"Gemini Terminal"** in the add-on store
   - Click **Install**

3. **Configure & Start:**
   - Enter your `GEMINI_API_KEY` in the Configuration tab (optional, but recommended).
   - Start the add-on and click **Open Web UI** (or add it to your sidebar).

---

## 📚 Documentation

Comprehensive documentation is available covering all features:

- 📖 [**Full Add-on Documentation**][docs] - Complete guide to all features and configuration
- 📝 [**Changelog**][changelog] - Version history and updates

---

## 🤝 Credits & Inspiration

This project stands on the shoulders of giants:

- **[Tom Cassady (@heytcass)](https://github.com/heytcass)**: Original creator of the excellent **[Claude Terminal for Home Assistant](https://github.com/heytcass/home-assistant-addons)** from which this project was originally forked.
- **[Magnus Overli (@magnusoverli)](https://github.com/magnusoverli)**: Creator of **[OpenCode for Home Assistant](https://github.com/magnusoverli/opencode)**, whose rock-solid container architecture inspired our v2.6+ stability refactor.

---

## 📜 License

This repository is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 
*Note: The Gemini CLI itself is subject to Google's Terms of Service.*

<!-- Links -->
[docs]: ./gemini-terminal/DOCS.md
[changelog]: ./gemini-terminal/CHANGELOG.md
[repo-add]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Foded996%2Fgemini-cli-home-assistant-addons
[repo-btn]: https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg
