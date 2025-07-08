# ⚡ FKvim

> A modern, minimal, and lightning-fast Neovim setup — designed for performance, aesthetics, and developer productivity.
> 
<img width="1305" alt="image" src="https://github.com/user-attachments/assets/f083ebfa-d89a-4831-86bf-19aed7fdf309" />

---

## 🚀 Features

- ⚡ **Fast Startup** – Powered by [`lazy.nvim`](https://github.com/folke/lazy.nvim)
- 🎨 **Modern UI** – Beautiful, transparent, and distraction-free
- 🧠 **LSP Ready** – Language Server Protocol and smart completion via `nvim-cmp`
- 📁 **Neo-tree** – Smooth file browsing with git indicators
- 🔍 **Telescope** – Blazing fast fuzzy finder
- 🧩 **Treesitter** – Powerful syntax highlighting & better code understanding
- 🔔 **Custom Notifications** – Unified Noice UI with minimal alerts
- 🛠️ **Modular Structure** – Easy to configure, extend, and maintain
- 🧪 **Built-in Terminal**, breadcrumbs, Git signs, and much more...

---

## 📥 Installation

 **Requirements:**
 - Neovim 0.9+  
 - Git  
 - `make` (for native telescope extensions)

```bash
git clone https://github.com/Flash-codes/fkvim.git ~/.config/nvim
nvim
````
> Please refer to our wiki for more detailed installation guide 

>On first launch, FKvim will auto-install plugins. Sit back and relax ☕

---

## 📁 Directory Structure

```
~/.config/nvim/
├── init.lua
├── lua/
│   ├── fk_plugins/
│   ├── fk_configs/
│   └── fk_autoscripts.lua
```

Everything is organized under `lua/` with proper namespaces for ease of maintenance.

---

## 🔧 Configuration

You can customize FKvim easily:

* Theme, transparency, keymaps, and plugins are modular
* Add new plugins via `lazy.nvim` in `init.lua`
* Custom configs live in `lua/fk_configs/` and `lua/fk_plugins/`

---

## 📚 Wiki

Explore the [📘 GitHub Wiki](https://github.com/Flash-codes/fkvim/wiki) for:

* ✅ Getting Started
* 🎨 Theme Customization
* 🔌 Plugin Development
* 🧠 LSP and Auto Completion
* 🛠️ Troubleshooting
* ❓ FAQ

---

## 🧑‍💻 Contributing

Contributions, suggestions, and issues are welcome!
Fork the repo, create a branch, and submit a PR.

---

## 📸 Preview



## 🖼️ Previw
Below are interactive previews of FKvim features. Click to expand each section.

<details><summary>🎯 Dashboard</summary> <br> <img width="1687" alt="image" src="https://github.com/user-attachments/assets/e3c0002a-ae74-417d-8391-bb7094f20f06" width="800"/> <br> <em>Minimal FKvim Dashboard with project access, recent files, and shortcuts</em> </details>

<details> <summary>🔍 Telescope Fuzzy Finder</summary> <br> <img width="1695" alt="image" src="https://github.com/user-attachments/assets/ffd945c2-1b43-48dc-9b19-cb8f7f3d02d8" />
 <br> <em>Fast fuzzy searching for files, text, buffers, and more with Telescope</em> </details>

<details> <summary>📁 Fkvim Tree - File Explorer powered by Neo Tree</summary> <br> <img width="1707" alt="image" src="https://github.com/user-attachments/assets/8bd5ce1e-a206-4616-821d-8f55301c5288" />
 <br> <em>Modern sidebar with Git integration, diagnostics, and icons</em> </details>

<details> <summary>🧠 LSP + Autocomplete</summary> <br> <img width="1423" alt="image" src="https://github.com/user-attachments/assets/b932361a-b5d1-4f13-b303-b0115c58e47f" />
 <br> <em>Intelligent suggestions with LSP, snippets, and inline docs</em> </details>
 
<details> <summary>🔔 Noice + Notify UI</summary> <br> <img width="1674" alt="image" src="https://github.com/user-attachments/assets/5ba70126-6208-45c8-a071-05d9895f479b" />
<br> <em>Modern notification system and command-line interface using Noice + Notify</em> </details>

<details> <summary>📌 Bufferline Navigation</summary> <br> <img width="1710" alt="image" src="https://github.com/user-attachments/assets/f48c9395-10a3-49f0-8a2f-5fad7c71b871" />
 <br> <em>Visual tabs for each open buffer, with Git and diagnostic signs</em> </details>

<details> <summary>🧬 Treesitter Highlighting</summary> <br> <img width="1710" alt="image" src="https://github.com/user-attachments/assets/3432e449-6354-47b0-903f-43cc3079ab76" />
 <br> <em>Accurate and colorful syntax highlighting powered by Treesitter</em> 
</details>

<details> <summary>🧪 Floating Terminal</summary> <br> <img width="1709" alt="image" src="https://github.com/user-attachments/assets/2f794784-3a5a-459b-95db-3d6851030fb1" />
 <br> <em>Run terminals inside Neovim — Python, Git, htop, etc.</em> </details>

<details> <summary>🎨 Transparent Theme</summary> <br> <img width="1710" alt="image" src="https://github.com/user-attachments/assets/3ee9885a-11ca-466b-9262-c04cbd3bc0c9" />
 <br> <em>FKvim with True transparency and Default Catppuccin Mocha theme</em> </details>


---

## 🙏 Credits

FKvim is built on the shoulders of amazing open-source tools including:

* [lazy.nvim](https://github.com/folke/lazy.nvim)
* [catppuccin](https://github.com/catppuccin/nvim)
* [telescope.nvim](https://github.com/nvim-telescope/telescope.nvim)
* [neo-tree.nvim](https://github.com/nvim-neo-tree/neo-tree.nvim)
* [noice.nvim](https://github.com/folke/noice.nvim)
* ...and many others.

---


> FKvim – Made with ❤️ by [Mayank Kumar Jha](https://github.com/flashcodes-themayankjha)



